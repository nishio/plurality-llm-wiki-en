---
type: source
summary: The pluralitybook/plurality upstream English manuscript as it has evolved since the March 2024 PDF snapshot — Pull Requests, Issues, and commits that revise or extend the printed book.
raw_sources:
  - github.com/pluralitybook/plurality
---

## What this source is

[[plurality-book]] was originally ingested from the **2024-03-10 PDF release** (`Plurality-english.pdf`), which corresponds to upstream tag `20240226` (commit `a5cb02ea`). The book is a **living, CC0, git-versioned manuscript** — `main` keeps moving. As of the second-pass survey (2026-05-27), `main` is at commit `c82704e1` (2026-04-06), **~1,737 commits ahead** of the PDF baseline across **~300 files**, with **80+ merged PRs** and a non-trivial Issues backlog.

This page is the EN wiki's single registered source for **English-language additions made after the PDF snapshot**. Individual claims in concept / entity pages cite this source plus a specific PR / Issue number for traceability.

## Scope (what is in scope vs. out of scope)

In scope for this EN wiki:
- English manuscript edits in `contents/english/*.md` between `a5cb02ea` (2024-02) and `c82704e1` (2026-04).
- Substantive English-language Issues that propose factual or theoretical revisions.
- Merged Pull Requests that add new sections, examples, footnotes, or endorsements.

Out of scope (handled by sibling language wikis):
- `contents/traditional-mandarin/*` and other-language translations.
- PRs that are pure typo / grammar fixes (#1119 typos, #1120 credits generation, #1066 grammar polish on the Henry George sentence, #1064 "tax fillings" → "tax filings", etc.).

## Substantive PRs adopted into this wiki

The following merged Pull Requests added **English-language material** that this wiki has filed into its concept / entity pages:

### Major: new sections / new entities

- **PR #918** (nishio, 2024-05-16) — adds Ken Suzuki's endorsement to `0-0-endorsements.md`. Quotes Suzuki on Plurality as a third way beyond Libertarianism and Technocracy whose essence is "the emergence of life at the edge of chaos." Filed into the new `entities/Ken-Suzuki.md`.
- **PR #1055** (Taiyou, 2025-01-23) — adds an entire new sub-section **"Quality Control and Nameraka Society"** (~37 lines) to `3-3-the-lost-dao.md`. Connects Wiener's cybernetics → Deming / PDCA / Kaizen / Toyota → Stuart Kauffman's complex systems → Ken Suzuki's **Nameraka Society** vision (2000s, summarised in his 2013 book *The Nameraka Society and Its Enemies*) → divicracy → PICSY → Takahiro Anno's 2024 Tokyo campaign. Subsequent PR **#1056** (Taiyou) refined the same section's reference to Hal Seki / sinsai.info / Code for Japan. Subsequent PR **#1059** (Taiyou) added a Simmel-bridging footnote on dividual.
- **PR #1043** (nishio, 2024-12-21) — adds ~11 lines to `5-4-augmented-deliberation.md` documenting **Takahiro Anno's 2024 Tokyo gubernatorial campaign**. Cites the AI-Anno virtual avatar (~7,400 questions in 16 days, ~77% answer rate), Talk to the City for opinion visualisation, the GitHub-driven manifesto with 232 issues and 85 adopted proposals, the 150,000-vote / 5th-place outcome ("highest number of votes for a candidate in their 30s in the 22 past Tokyo gubernatorial elections"), and the October 2024 use of TttC to confront incumbent politicians. Derived from issue #1007.
- **PR #1049** (Taiyou, 2024-12-21) — adds Hal Seki / Code for Japan to `3-3-the-lost-dao.md` as the Japanese counterpart to Pahlka / Code4America and Noveck / GovLab. Refined by PR #1056 to mention **sinsai.info** (data collection and visualisation after the 2011 Great East Japan Earthquake).
- **PR #1050** (Taiyou, 2024-12-21) — rewrites the divicracy footnote in `5-6-⿻-voting.md`. Defines **dividual democracy ("divicracy")** as Ken Suzuki's extension of liquid democracy: not only delegation but also **splitting one vote across multiple political issues**, drawing on Deleuze's "dividual" against the indivisible "individual." Cites Suzuki, *The Nameraka Society and its Enemies* (Keiso Shobo, 2013).
- **PR #1051** (Taiyou, 2024-12-21) — rewrites the PICSY footnote in `5-7-social-markets.md` and attaches it explicitly to the **inter-temporal economic systems** bullet (intergenerational matching funds / "ministry for the future"). Defines PICSY (Propagational Investment Currency SYstem) as "a value propagation system which tracks past transactions as contributions and assigns a portion of recent contributions to past contributors."

### Substantive: new examples, footnotes, corrections

- **PR #939** (ComputerLars, 2024-06-12) — adds **The Synthetic Party** (Det Syntetiske Parti, Denmark, founded 2022) as a worked example in `5-4-augmented-deliberation.md`: "officially the world's first political party driven by artificial intelligence", fine-tuned on >200 sub-electoral-threshold Danish micro-parties' data to represent the ~15-20% abstention rate.
- **PR #1042** (SamRoizen, 2024-12-21) — adds a footnote to `6-3-media.md` defining **multi-source validation** as a journalistic norm.
- **PR #1040** (SamRoizen, 2024-12-21) — adds a passage on **compulsory voting in Australia** to `5-6-⿻-voting.md` with the AEC's 2022 *Compulsory Voting in Australia* report as a footnote: compulsory voting can both raise turnout and intensify the "lesser of two evils" pressure under plurality rule.
- **PR #1061** (kronosapiens, 2025-02-19) — adds Kelly Clancy's 2024 *Playing With Reality* footnote in `5-1-post-symbolic-communication.md` (speculation that the *Homo sapiens* pre-frontal cortex evolved for one highly complex romantic-partner relationship, not for large social groups) and a Lois Lowry *The Giver* footnote on shared experience across generations.
- **PR #1062** (kronosapiens, 2025-02-19) — adds **ChoreWheel** (Kronovet, Frey, DeSimone 2024, "Cybernetic Governance in a Coliving House") and **Reinventing Organizations** as ⿻ workplace / market-design examples to `5-7-social-markets.md`.
- **PR #1063** (kronosapiens, 2025-02-19) — adds **Colony** and **GlassFrog** to `6-1-workplace.md` as "neutral and transparent 'substrates' onto which flexible organisational cultures can be built."
- **PR #1066** (garethjwhelan, 2025-02-19) — small factual correction to the Henry George sentence in `3-2-connected-society.md` (private property *in land* — Henry George did not oppose private property in general).
- **PR #1117** (audreyt, 2026-02-19, derived from issue #1116 by nishio) — corrects `2-1-a-view-from-yushan.md`'s claim about US "supporting" UNGA Resolution 2758 in 1971. The US in fact voted against. The new wording says the US "pursued accommodation with the PRC, a move that signaled shifting global alignments, amid which an Albanian-sponsored Resolution 2758 passed."

### Unmerged but substantive (recorded as observations, not folded into wiki)

- **PR #1052** (Taiyou) — an earlier, longer version of the Nameraka section. Replaced by the merged PR #1055.
- **PR #1048** (Taiyou) — Nameraka in `3-2-connected-society.md`. The eventual decision was to place Nameraka in 3-3 lost-dao (PR #1055) rather than 3-2.
- **PR #960** (vicstanski) — proposes adding Common Good AI and CrowdSmart to 5-4 augmented-deliberation. Unmerged.
- **PR #1026** (albert-tomanek) — proposes globally replacing "capitalism" with "market economy". Unmerged — the authors evidently preferred to keep the term *capitalism* with its specific meaning.

## Substantive Issues recorded but not yet merged

- **Issue #1113** (rysh, 2026-01-01, open) — proposes adding a Stuart-Landau "dynamical systems" framework to chapters 5-4 and 5-6 to address the "Equilibrium Trap" (why bridging-statement *discovery* doesn't automatically yield social *action*; the Reusability Paradox; Optimization/Gaming Risk). Linked to a draft PR #1112.
- **Issue #1100** (earthwalker20075-coder, 2025-09-26, open) — proposes referencing **Genetic Algorithms / Artificial Life (e.g., Tom Ray's *Tierra*)** in Chapter 3 to give "edge of chaos" computational grounding.
- **Issue #1101** (earthwalker20075-coder, 2025-09-26, open) — proposes a clearer affirmative justification for choosing imperfect human Plurality over AGI governance in Chapter 3 / Chapter 7.

## What this tells us about the manuscript's trajectory

The post-PDF additions are **disproportionately Japan-flavoured** (PRs #918, #1043, #1048-#1052, #1055-#1059 — almost all merged in a single 2024-12-21 batch driven by Taiyou + nishio): a Japanese reader / contributor cluster has actively folded Ken Suzuki's *Nameraka Society* lineage, Hal Seki's Civic Tech work, and Takahiro Anno's 2024 Tokyo campaign into the English manuscript. This is precisely the kind of "language carves the conceptual space differently" trace that the multilingual *plurality-llm-wiki* 森 was set up to observe — except that here the trace is running in the *opposite* direction from the canonical "EN → JA translation" assumption: ideas first articulated in Japanese discourse have been retro-integrated into the English root manuscript.

The remaining merged substantive PRs cluster around (a) examples of bottom-up corporate / cooperative governance (Colony, GlassFrog, ChoreWheel, Reinventing Organizations — Kronovet, 2025-02), (b) historical and factual corrections (Henry George scope, US-vs-Resolution-2758), and (c) compulsory voting in Australia.

## Open observations

- A large cleanup commit in 2024 **renamed every chapter file** (from `01-preface.md` → `1-preface.md`, `02-00-...` → `2-0-...`, etc.) which is why a raw `git compare` shows 30+ "removed" files and 30+ "added" files even where content was largely preserved.
- The book's `mkdocs.yml` and `docs/` infrastructure was significantly built out after the PDF release. This is a structural rather than content change; out of scope for this wiki.

## Related sources

- [[plurality-book]] — the PDF-baseline source page
- [[civic-ai-manifesto]], [[ai-alignment-cannot-be-top-down]] — the post-book Tang/Civic-AI corpus that the previous second-pass already ingested
