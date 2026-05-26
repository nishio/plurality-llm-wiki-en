# Log

> 直近 7 日分のみ。全件 compact 履歴は [log.txt](log.txt)、それより古い entry の詳細は `git log -- wiki/log.md` で参照。
> 更新は `python3 scripts/refresh_logs.py` で log.txt と log.md を再生成する。

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
