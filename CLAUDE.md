# plurality-llm-wiki-en

## Theme
Plurality concepts as carved by **English-language discourse**. Sources include the *Plurality* book (EN edition), Audrey Tang's talks, the 6pack.care site, Plurality Events, and surrounding community discussion.

Part of the multilingual [plurality-llm-wiki](https://github.com/nishio/plurality-llm-wiki) wiki森. This wiki is **autonomous** — pages are not required to be translations of, or aligned with, the ja-side wiki ([plurality-llm-wiki-ja](https://github.com/nishio/plurality-llm-wiki-ja)).

> Each language carves the conceptual space differently. The differences themselves are what this wiki森 aims to observe and analyze — diversity creates value.

## Directory Structure

```
plurality-llm-wiki-en/
├── CLAUDE.md                          # this file
├── raw/                               # raw sources (gitignored)
├── wiki/
│   ├── index.md                       # human-facing curated navigation
│   ├── index.txt                      # AI-facing full catalog (auto-generated)
│   ├── log.md                         # human-facing recent 7 days (full detail)
│   ├── log.txt                        # AI-facing compact full history (auto-generated)
│   ├── concepts/                      # concept pages
│   ├── entities/                      # people, tools, projects
│   ├── sources/                       # source summaries
│   └── analyses/                      # analyses born from inquiry
├── scripts/
│   ├── lint_wiki.py                   # wiki health check
│   ├── build_index_txt.py             # regenerate index.txt from frontmatter
│   └── refresh_logs.py                # sync log.txt + 7-day window in log.md
├── quartz/                            # Quartz for GitHub Pages delivery
├── quartz.config.ts / quartz.layout.ts
├── package.json / pnpm-lock.yaml
└── .github/workflows/deploy-pages.yml # auto-deploy on push to main
```

## Cross-language correspondences

Inter-language concept mapping lives in the parent's [correspondences.yaml](https://github.com/nishio/plurality-llm-wiki/blob/main/correspondences.yaml). It's the Wikipedia interlanguage-link equivalent — a row asserts "these concepts are about the same/related topic" without claiming content equivalence.

When you add a new concept page here:
- Either add a row to `correspondences.yaml` pairing it with the ja-side concept (or null for "no equivalent"),
- Or explicitly leave a gap (ja: ~) — that's a recorded observation, not an oversight.

## Page Rules

### Common to all pages
- Start with YAML frontmatter: `type`, `summary`, `sources`
- Cite sources with `[[source-name]]より` (or `from [[source-name]]`)
- Use `## Open Questions` for unresolved contradictions
- Update by appending under `## Updates`, not by overwriting
- Wikilinks use `[[Page Name]]` (Wikipedia double-bracket style)

### Frontmatter example
```yaml
---
type: concept
summary: 1-sentence description
sources:
  - source-page-name.md
---
```

## Operations

### Index maintenance (AI/human split, kouchou pattern)

- **`wiki/index.md`** — human-curated navigation. Edit manually. Holds onboarding, Concepts/Entities curated entries.
- **`wiki/index.txt`** — AI-facing full catalog. **Do not edit by hand.** Regenerate after adding/renaming/deleting any page or changing a frontmatter `summary`:
  ```sh
  python3 scripts/build_index_txt.py
  ```

### Log maintenance (AI/human split, kouchou pattern)

- **`wiki/log.md`** — human-facing recent 7 days, full detail, newest first. Add entries to the top manually with `## [YYYY-MM-DD HH:MM] <type> | <title>`.
- **`wiki/log.txt`** — AI-facing all-history compact log. **Do not edit by hand.** Regenerate after adding a new log.md entry:
  ```sh
  python3 scripts/refresh_logs.py
  ```

`refresh_logs.py` drops lint-type entries (no-finding lints are not logged) and prunes log.md entries older than 7 days while preserving them in log.txt.

### Ingest (raw → wiki)
1. Read new files in `raw/` (rename meaningfully if needed)
2. Cross-reference with existing wiki pages
3. Update existing pages or create new ones (frontmatter required)
4. Run `python3 scripts/build_index_txt.py` after page set changes
5. Add `## [YYYY-MM-DD HH:MM] ingest | <description>` to top of log.md
6. Run `python3 scripts/refresh_logs.py`
7. If new concepts may correspond to ja-side concepts, update parent's `correspondences.yaml`

### Query
1. Search `wiki/` for the answer
2. File back useful answers into `analyses/`
3. Log as `filing-back` and run `refresh_logs.py`

### Lint
1. Mechanical: `python3 scripts/lint_wiki.py`
2. Semantic: contradictions, stale claims, missing concept pages, new questions
3. Only log lints that actually found and fixed something (no-finding lints are silently dropped by `refresh_logs.py`)

## GitHub Pages

`main` push triggers `.github/workflows/deploy-pages.yml` which builds the Quartz site and deploys to https://nishio.github.io/plurality-llm-wiki-en/.

## Operating principles

- Sources are *references*, not authoritative — adopt critically
- Don't force translation parity with the ja wiki — differences are the point
- The schema (this file) evolves through use
