# Log

> 直近 7 日分のみ。全件 compact 履歴は [log.txt](log.txt)、それより古い entry の詳細は `git log -- wiki/log.md` で参照。
> 更新は `python3 scripts/refresh_logs.py` で log.txt と log.md を再生成する。

## [2026-05-27 05:30] sync | pluralitybook/plurality upstream の PDF snapshot 以降の差分を取り込み


- Upstream survey via `gh api`: pluralitybook/plurality `main` is at commit `c82704e1` (2026-04-06), **~1,737 commits ahead** of the 2024-03-10 PDF snapshot (tag `20240226`, commit `a5cb02ea`) across ~300 files. 50+ merged Pull Requests reviewed plus 14 substantive Issues.
- Sources of substantive English-language additions adopted: PR #918 (Ken Suzuki endorsement), PR #939 (Synthetic Party / Denmark), PR #1040 (Australian compulsory voting), PR #1042 (multi-source validation footnote), PR #1043 (Takahiro Anno 2024 Tokyo campaign), PR #1049 + #1056 (Hal Seki / sinsai.info / Code for Japan), PR #1050 (divicracy footnote rewrite), PR #1051 (PICSY repositioned as intertemporal mechanism), PR #1055 (entire new sub-section "Quality Control and Nameraka Society" in 3-3, ~37 lines), PR #1059 (Simmel ↔ Deleuze dividual footnote in Japanese), PR #1061 (Clancy + Lowry footnotes in 5-1), PR #1062 (ChoreWheel + Reinventing Organizations), PR #1063 (Colony + GlassFrog in 6-1), PR #1066 (Henry George property-in-land sharpening), PR #1117 (UNGA Resolution 2758 factual correction, derived from Issue #1116 by nishio).
- Substantive Issues recorded as observations (no PR yet): #1100 (Genetic Algorithms / *Tierra* for Edge of Chaos), #1101 (clearer affirmative justification for human Plurality vs AGI), #1113 (Stuart-Landau dynamical-systems framework for 5-4 / 5-6).
- New pages: `sources/pluralitybook-upstream-2024-2026.md` (single audit-trail source), `entities/Ken-Suzuki.md`, `entities/Takahiro-Anno.md`, `entities/Hal-Seki.md`, `concepts/Nameraka-Society.md`. 5 new pages total.
- Existing pages with appended `## Updates`: `concepts/The-Lost-Dao.md` (another lost Dao / Hal Seki / Anno cross-ref), `concepts/Augmented-Deliberation.md` (Anno upstream-confirmed + Synthetic Party), `concepts/Liquid-Democracy.md` (divicracy footnote refresh), `concepts/Social-Markets.md` (PICSY repositioning + ChoreWheel + Reinventing Organizations), `concepts/Plural-Voting.md` (compulsory voting), `concepts/Connected-Society.md` (Henry George correction), `concepts/Post-Symbolic-Communication.md` (Clancy/Lowry footnotes), `sources/plurality-book.md` (link to upstream source). 8 existing pages updated.
- `index.md` now lists Nameraka-Society, Ken-Suzuki, Takahiro-Anno, Hal-Seki, and pluralitybook-upstream-2024-2026 in their respective sections.
- Most interesting findings:
  1. **JA → EN reverse integration is a real and ongoing pattern**. The 2024-12-21 batch of merged PRs by the Japanese contributor cluster (Taiyou + nishio) folded Ken Suzuki's Nameraka Society lineage, Hal Seki's Civic Tech work, and Takahiro Anno's 2024 Tokyo campaign into the English root manuscript. The EN manuscript as it stands today contains a non-trivial Japanese-language footnote (PR #1059's `[^dividual]`) about a Japan-side reading of Simmel and Deleuze.
  2. **The book now contains "another lost Dao"** (PR #1055). The principal Lost Dao (Licklider/Engelbart/Nelson, US, networking) is paralleled by a second cybernetic lineage: Wiener → Deming → JUSE / Deming Prize / Toyota PDCA-Kaizen → Stuart Kauffman → Ken Suzuki / Nameraka Society. The book frames this as a second cybernetic descendant, with Takahiro Anno's 2024 Tokyo campaign as its contemporary realisation. The asymmetry is that PDCA / Kaizen were *adopted, not lost* in industry; what was "lost" is the social-theoretical extension (Nameraka itself).
  3. **The previous second-pass inference was right**: the prior `## Updates` section on Augmented-Deliberation had inferred (from civic-ai-manifesto) that "the book likely already describes Anno's campaign." PR #1043 (merged 2024-12-21) is the actual upstream commit that added the Anno paragraph and its 5 footnotes — including the specific telemetry (~7,400 questions in 16 days at ~77% answer rate; 232 GitHub issues in 15 days, 85 adopted proposals; 150,000 votes = "highest for a 30-something in 22 past Tokyo gubernatorial elections"). The previous inference is now upstream-confirmed; the entity page Takahiro-Anno.md formalises it.
- Lint to follow: rebuild index.txt + refresh logs + run lint_wiki.py.

## [2026-05-27 01:30] second-pass | book re-read with post-book Civic-AI context



- Re-read core book chapters (2-0, 3-0, 3-1, 4-1, 4-2, 4-4, 5-4, 5-5) with the post-book Civic-AI / 6-Pack-of-Care / Kami / Alignment-Assembly material in mind, and added 13 `## Updates` entries to 12 existing concept/entity pages.
- Pages updated: Identity-and-Personhood (Mulu vignette → rights to know/contest; Anon-Aadhaar → COVID zk; contextual integrity → data as soil), Association-and-Plural-Publics (Spritely/ActivityPub → ROOST.tools; contextual confidence → Civic-AI substrate), Property-and-Contract (Polanyi fictitious commodities → data as soil; customary norms → Tronto care ethics; MIDs → Kami), Augmented-Deliberation (book already covers Anno 2024 Tokyo; Anthropic/OpenAI seeds of model-spec lever; Cortico/Fora → RLCF; Latour Lorax → Kami), Adaptive-Administration (AI4Bharat/Karya → transcultural sovereignty; "ethnographers of old" → Verdania Metro; SERVIR Amazonia → Kami of a forest), Generative-Foundation-Models (Lorax → Kami), Plurality (corporation-as-game → enterprise Kami; ecology/Proudhon → permaculturists), Monist-Atomism (open question: is techno-communitarianism same as Plurality or a Tronto/Deneen refinement?), Data-Coalitions (ex post facto over-sharing → Taiwan joint platform liability), Policy (transnational digital-ministry networks → interoperable governance), Sunflower-Movement (Sunflower-built Polis → X.com Community Notes), vTaiwan (2015 Uber case as Alignment Assembly template), AGI (book rejects term → transparent-horse reclaims it as socio-technical achievement).
- Highlights of the most interesting connections:
  1. The book's chapter 5-4 mention of **Bruno Latour's "parliament of things" and Dr. Seuss's Lorax** ("speaks for the trees and animals that cannot speak for themselves") is essentially the Kami metaphor *avant la lettre* — Tang's Civic-AI just extends the same intuition from *representation in deliberation* to *active stewardship under continuous oversight*.
  2. The book's **"Mediators of Individual Data" (MIDs)** in chapter 4-4, with explicit reference to fiduciary duties and "prohibitions against unilateral strikebreaking against unions," is a direct structural ancestor of the bounded Kami — same primitive (bounded delegate with explicit charter) applied to *action authority* rather than *data*.
  3. The book's chapter 5-5 cautionary line that **"ethnographers of old became tools of colonial subjugation rather than voices of inclusive translation"** is the conceptual ancestor of [[transparent-horse]]'s **Verdania Metro** (2034) speculative warning — both name the same failure mode of "succeeded just enough to hide" adaptive systems.

## [2026-05-26 23:45] ingest | EN-language Tang/Weyl talks survey




- Surveyed Audrey Tang's post-book talks and essays beyond *Plurality* (2024). WebSearch and arbitrary WebFetch are restricted in this run, so material was sourced via the GitHub allowlist: audreyt/audreyt (her audreyt.org source repo) and audreyt/civic.ai (Oxford 6-Pack of Care site, CC0).
- 8 source pages added: audreyt-org-profile, civic-ai-manifesto (Google DeepMind, Sep 2025), ai-alignment-cannot-be-top-down (AI Frontiers, Nov 2025), collaborative-immune-system (LDP HQ Tokyo, Dec 2025), transparent-horse (speculative 2040, 2025), inside-the-kami (March 2026), democracy-needs-civic-ai (March 2026), safer-sovereignty (Kyndryl Institute, Apr 2026), good-enough-ancestor-senate-canada (Apr 2026).
- 1 new concept page: Civic-AI (the 6-Pack of Care framework, with Audrey Tang's "Kami" design pattern).
- 2 new entity pages: Joan-Tronto (ethics-of-care theorist), Caroline-Green (Tang's Oxford collaborator).
- 9 existing pages updated under `## Updates`: Audrey-Tang, Glen-Weyl, Plurality, Augmented-Deliberation, Digital-Democracy, Generative-Foundation-Models, Adaptive-Administration, Policy, vTaiwan, Sunflower-Movement, Data-Coalitions.
- Glen Weyl coverage thinner due to access restrictions (his solo essays at glenweyl.com / RadicalxChange Blog / Foreign Affairs / Noema not WebFetch-able in this run); his post-book trajectory is covered indirectly through "Community by Design" (Tang+Weyl, arXiv 2502.10834, Feb 2025) and his Civic AI Conference 2026 keynote.
- index.md updated with a new "Post-book extensions" subsection and a Sources subsection listing the 8 new talks/essays.
- 96 pages total (was 84).

## [2026-05-26 19:30] ingest | brief-mention pages backfill






- Created 34 entity pages and 10 concept pages for people and abstract concepts the book mentions only briefly.
- Each page opens with the book's exact treatment, then adds concise factual context from general knowledge.
- Entities: Lost Dao trio completion (Doug-Engelbart, Ted-Nelson); Connected Society pre-history (Mark-Granovetter, Georg-Simmel, Norbert-Wiener, John-Dewey, Henry-George); Tridemism / Taiwan figures (Sun-Yat-Sen, Hu-Shih, Chiang-Kai-Shek, Jaclyn-Tsai, Academia-Sinica); Plural Voting lineage (Lionel-Penrose, Charles-Dodgson, Robin-Hanson); Technocracy bench (Sam-Altman, Elon-Musk, Reid-Hoffman, Andrew-Yang, Ray-Kurzweil, Nick-Bostrom, Isaac-Asimov, Iain-M-Banks); Libertarianism bench (Peter-Thiel, Curtis-Yarvin, Balaji-Srinivasan, Ayn-Rand, John-Perry-Barlow, Neal-Stephenson); other thinkers cited briefly (Anu-Bradford, Cass-Sunstein, Daron-Acemoglu, James-Robinson, Shoshana-Zuboff, Marc-Andreessen).
- Concepts: Technocracy, Libertarianism, Monist-Atomism, AGI, Universal-Basic-Income, Narrow-Corridor, Surveillance-Capitalism, Network-State, Futarchy, Cybernetics.
- Updated existing concept pages (Plurality, Connected-Society, The-Lost-Dao, Tridemism, Digital-Democracy, Sunflower-Movement, Quadratic-Voting, Liquid-Democracy, Plural-Voting, Augmented-Deliberation, Policy, Generative-Foundation-Models) and the source page (plurality-book) to wikilink the new pages, so none of the new entries is orphan.
- Pattern: opening sentence states the book's treatment ("mentioned briefly in chapter X as..."), then Background / In the book sections.
- Lint: 0 broken wikilinks, 0 orphans, 0 frontmatter issues; 84 pages total (was 38).

## [2026-05-26 18:30] ingest | Plurality book (English edition) full ingest







- Extracted PDF text via Read tool's PDF support; the PDF itself remains under raw/ (gitignored).
- Created source page `sources/plurality-book.md` (CC0, Weyl + Tang + community, 2024 edition).
- Created 23 concept pages covering Plurality and its three-part definition, the Section 4 rights/OS stack (Identity, Association, Commerce, Property, Data Coalitions, Access), the Section 5 collaboration spectrum (Post-Symbolic, ISR, Creative, Augmented Deliberation, Adaptive Administration, Plural Voting, QV, Liquid Democracy, Social Markets, QF, Plural Management Protocol, GFMs), Section 7 (Policy, DPI), plus genealogy (Tridemism, Sunflower Movement, The Lost Dao, Connected Society, Digital Democracy, Collaborative Technology and Democracy).
- Created 10 entity pages: Audrey Tang, Glen Weyl, Hannah Arendt, Danielle Allen, JCR Licklider, RadicalxChange, vTaiwan, Join, g0v, Gitcoin, ARPA.
- Updated `index.md` with curated nav grouped by book section.
