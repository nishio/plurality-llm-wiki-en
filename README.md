# plurality-llm-wiki-en

The **English-language** member of the [plurality-llm-wiki](https://github.com/nishio/plurality-llm-wiki) multilingual wiki森. Plurality concepts as carved by English-language discourse — the *Plurality* book (EN edition), Audrey Tang's talks, the 6pack.care site, Plurality Events, and surrounding community discussion.

**Live site:** https://nishio.github.io/plurality-llm-wiki-en/

## How this wiki relates to its siblings

This wiki is **autonomous**. Pages here are not required to be translations of, or aligned with, the [ja-side wiki](https://github.com/nishio/plurality-llm-wiki-ja). Each language carves the conceptual space differently, and the differences themselves are what the parent wiki森 observes and analyzes.

Cross-language correspondences (and explicit gaps) are tracked in the parent's [correspondences.yaml](https://github.com/nishio/plurality-llm-wiki/blob/main/correspondences.yaml). A row there is the equivalent of a Wikipedia interlanguage link: it asserts "these pages are about the same/related topic" without claiming content equivalence.

## Repository layout

```
wiki/
├── index.md             human-facing curated navigation
├── log.md               human-facing recent-7-days activity log
├── concepts/            concept pages
├── entities/            people, tools, projects
├── sources/             source summaries
└── analyses/            analyses born from inquiry
```

`index.txt` and `log.txt` are AI-facing auto-generated files — do not edit by hand.

## For contributors

- Operational details, page conventions, and frontmatter schema: [CLAUDE.md](CLAUDE.md)
- After adding/renaming/deleting any page: `python3 scripts/build_index_txt.py`
- After adding a log entry: `python3 scripts/refresh_logs.py`
- Mechanical health check: `python3 scripts/lint_wiki.py`

## Operating principles

- Sources are *references*, not authoritative — adopt critically
- Don't force translation parity with the ja wiki — differences are the point
- The schema (CLAUDE.md) evolves through use
