---
type: source
summary: "Sources attempted but not accessible to the wiki's automated tooling. Human help (manual fetch + drop into raw/) is welcome; subsequent ingest passes will then incorporate them."
raw_sources:
  - "(none yet — by design; this page lists URLs awaiting manual fetch)"
---

# Wishlist (fetch help needed)

This page records source URLs we tried to fetch but could not access from the wiki's automated tooling. The current sandbox restricts WebFetch to the `plurality.net` and `github.com` allowlist; sources that live elsewhere need a human to mirror them into `raw/` (gitignored) before ingest can proceed.

Conventions:

- Each entry names the *intended* canonical URL, the expected substance, the attempt date, the failure mode, and the help action.
- If a URL is found to be dead, mark it `dead: true` and note an alternative.
- After a human drop into `raw/`, leave the wishlist entry in place but add an `Ingested` line with the source page that resulted; this preserves the audit trail of what was unreachable when.

## Allison Stanger essays / talks

### https://allisonstanger.com (and any successor personal site)
- **Expected content**: Stanger's solo essays beyond her *Plurality* book contribution; she is co-credited in the *Plurality* book front matter and is the Russell J. Leng '60 Professor of International Politics & Economics at Middlebury College, an AI ethics specialist with previous public work on Edward Snowden / whistleblowing and *Whistleblowers: Honesty in America from Washington to Trump* (Yale UP, 2019). Her post-2024 *Plurality* contributions are likely on her personal site or institutional page.
- **Attempted**: 2026-05-28 via WebSearch (denied) and the standard URL guess.
- **Result**: WebSearch permission denied; WebFetch is restricted to plurality.net and github.com; Stanger has no public GitHub profile (404 on github.com/AllisonStanger).
- **Help action**: A human could (i) visit www.middlebury.edu/faculty/astanger or allisonstanger.com and mirror her current publications list, (ii) save any Plurality / AI-ethics essays into `raw/` with descriptive names.

### https://www.middlebury.edu/faculty/astanger
- **Expected content**: Stanger's official Middlebury faculty page with publications and CV.
- **Attempted**: 2026-05-28.
- **Result**: WebFetch denied (domain not on allowlist).
- **Help action**: Manual fetch.

### Stanger's recent op-eds / public commentary (2024–2026)
- **Expected content**: Stanger has been a frequent commentator on AI policy and democracy; she likely has Project Syndicate, Foreign Affairs, or Lawfare pieces post-*Plurality*.
- **Attempted**: 2026-05-28 — exact URLs not known.
- **Result**: WebSearch denied (can't discover URLs).
- **Help action**: A human could search Project Syndicate, Lawfare, and Foreign Affairs author pages and surface a list of candidate URLs.

## RadicalxChange Foundation blog

### https://www.radicalxchange.org/media/blog/
- **Expected content**: Blog posts authored by Glen Weyl, Matt Prewitt, and other RxC contributors — likely several post-*Plurality* essays elaborating Plurality-adjacent themes (Quadratic Funding, social markets, pluralistic data).
- **Attempted**: 2026-05-28 via WebFetch.
- **Result**: WebFetch denied (radicalxchange.org not on allowlist). The RxC GitHub website source (`RadicalxChange/www`) does *not* contain blog content — it is a content-managed Eleventy site fetching posts from elsewhere (Fathom-tracked, daily Zapier rebuild).
- **Help action**: A human can fetch the blog index page and the 10–20 most recent posts, then mirror them to `raw/rxc-blog/`.

### Glen Weyl's personal essay archive
- **Expected content**: glenweyl.com personal essays (per his GitHub profile description, he points there for writings). Likely includes "Why I am a Pluralist" (2022, already cited in the book), and post-book solo essays on Plurality vs Radical Markets.
- **Attempted**: 2026-05-28 via WebFetch.
- **Result**: WebFetch denied.
- **Help action**: Manual fetch.

### Microsoft Research Plural Technology Collaboratory blog
- **Expected content**: Weyl directs MSR's Plural Technology Collaboratory; their blog / news page on microsoft.com is the likely home for institutional Plurality essays.
- **Attempted**: 2026-05-28.
- **Result**: WebFetch denied.
- **Help action**: Manual fetch.

## Foreign Affairs / Noema / Wired / Lawfare reception

### https://www.foreignaffairs.com — Plurality / Audrey Tang / Glen Weyl
- **Expected content**: Post-2024 reception essays of *Plurality* in the Foreign Affairs orbit (Anu Bradford has written for them; Tang and Weyl have published there before).
- **Attempted**: 2026-05-28.
- **Result**: WebFetch denied (foreignaffairs.com not on allowlist). Many Foreign Affairs essays are also paywalled — even with WebFetch enabled, paywalls would limit access to abstracts.
- **Help action**: A human with Foreign Affairs access can survey the "Plurality" / "Tang" / "Weyl" tag pages and download relevant essays.

### https://www.noemamag.com
- **Expected content**: Noema (the Berggruen Institute magazine) has been a frequent home for Plurality-adjacent essays since 2022; Weyl has likely published there.
- **Attempted**: 2026-05-28.
- **Result**: WebFetch denied.
- **Help action**: Manual fetch. Noema is generally not paywalled, so URLs once known should download cleanly.

### https://www.wired.com — Plurality reception
- **Expected content**: Wired's coverage of *Plurality*; Wired covered Tang frequently during the COVID era, and the book's December 2024 launch likely generated review coverage.
- **Attempted**: 2026-05-28.
- **Result**: WebFetch denied; WebSearch denied.
- **Help action**: Human search for "Wired Plurality Tang Weyl 2024 2025 2026."

### https://www.lawfaremedia.org (formerly lawfareblog.com) — Plurality / Tang
- **Expected content**: Lawfare's national-security-and-tech coverage of Plurality, Civic AI, Taiwan digital governance. Particularly likely to have engaged with Tang's Senate of Canada and Kyndryl Institute talks ([[good-enough-ancestor-senate-canada]], [[safer-sovereignty]]).
- **Attempted**: 2026-05-28.
- **Result**: WebFetch denied.
- **Help action**: Manual fetch.

## Civic AI Conference 2026 — non-Tang speaker primary sources

The conference agenda page ([[civic-ai-conference-2026]]) names ~14 speakers beyond Tang and Green. Some of them have video segments hosted on civic.ai itself (we have already ingested Slaughter's [[civic-ai-self-actualisation-and-care]] and Buterin's [[civic-ai-with-us-vitalik]]). Others are referenced but with no civic.ai-hosted primary content:

### Rosalind Picard's keynote — *The 6-Pack unpacked from a tech-builder perspective*
- **Expected content**: a transcript or recording of Picard's MIT-affective-computing-perspective talk at the Oxford conference.
- **Attempted**: 2026-05-28 — no dedicated permalink found in the civic.ai/audreyt repo.
- **Result**: not in the civic.ai source repo; her own page (affect.media.mit.edu) is not in the allowlist.
- **Help action**: Manual fetch; check whether Oxford podcasts published the conference recording.

### Joan Tronto's keynote — *From care loop to solidarity — name the unhealth*
- **Expected content**: Tronto's keynote was the conference's opening academic keynote. A primary source beyond the agenda blurb would significantly strengthen the [[Joan-Tronto]] entity page.
- **Attempted**: 2026-05-28.
- **Result**: not in the civic.ai source repo.
- **Help action**: Manual fetch; Tronto's CUNY graduate-center page may have it.

### Iason Gabriel (DeepMind) / Gina Neff (Oxford Internet Institute) / Jeni Tennison (Connected by Data) — *Rewriting the Defaults* panel
- **Expected content**: a transcript or recording of the afternoon panel on AI defaults.
- **Attempted**: 2026-05-28.
- **Result**: not in the civic.ai source repo.
- **Help action**: Manual fetch.

### Geshe Lobsang Negi and Tenzin Gayche — *Accessible Intelligence* panel
- **Expected content**: Emory–Tibet ethics perspective; complements [[civic-ai-compassion-and-ai]] (Green × Geshe Lodoe Sangpo, also from Dharamsala March 2026). Negi and Lodoe Sangpo are different people, both Tibetan-Buddhist scholars at Emory's compassion-meditation lineage.
- **Attempted**: 2026-05-28.
- **Result**: not in the civic.ai source repo.
- **Help action**: Manual fetch.

### Clenton Farquharson — *Accessible Intelligence* panel
- **Expected content**: UK disability-rights / Think Local Act Personal perspective on Civic AI; a relatively rare voice in the conversation from a non-academic disabled-people's organisation.
- **Attempted**: 2026-05-28.
- **Result**: not in the civic.ai source repo.
- **Help action**: Manual fetch; check the Think Local Act Personal website (tlap.org.uk) and Clenton Farquharson's own writing.

### Karina Palyutina and Zarinah Agnew — *Putting Civic AI into Practice* panel
- **Expected content**: practitioner / operator perspective. Zarinah Agnew is the founder of Embassy Network (residential community network) — relevant to Buterin's "tribes need hubs" thesis in [[vitalik-let-a-thousand-societies-bloom]].
- **Attempted**: 2026-05-28.
- **Result**: not in the civic.ai source repo.
- **Help action**: Manual fetch.

## Plurality book reception in Japan / Korea / China

(Not part of the original 5 candidate groups but worth recording as the natural next gap, since the EN wiki should know what the JA and ZH-TW wikis are likely to ingest.)

- **Audrey Tang interviewing Takahiro Anno** (Japanese-language sources)
- **Ken Suzuki / Nameraka Society** reception (mostly Japanese)
- **Plurality.tw / civic.ai/tw/** translations (already in the `audreyt/civic.ai` repo as `tw-*.md` files; could be cross-linked from [[civic-ai-manifesto]] etc. without re-ingest)

## Successfully ingested in the 2026-05-28 pass

For audit-trail clarity, the candidate groups *successfully* fetched (no help needed for these) were:

- **Vitalik Buterin** essays via `vbuterin/blog` on GitHub: [[vitalik-soulbound]] (2022-01-26), [[vitalik-three-transitions]] (2023-06-09), [[vitalik-techno-optimism]] (2023-11-27), [[vitalik-cryptoai]] (2024-01-30), [[vitalik-let-a-thousand-societies-bloom]] (2025-12-17). All 5 fetched from `vbuterin/blog`. A new [[Vitalik-Buterin]] entity page was created.
- **Civic AI Conference 2026 non-Tang speakers** via `audreyt/civic.ai` on GitHub: [[civic-ai-conference-2026]] (agenda + speaker roster), [[civic-ai-with-us-vitalik]] (Buterin video), [[civic-ai-self-actualisation-and-care]] (Slaughter video), [[civic-ai-gentle-bridge]] (Tenzin Yangtso essay), [[civic-ai-democracy-podcast]] (Tang × Green podcast Aug 2025), [[civic-ai-compassion-and-ai]] (Green × Geshe Lodoe Sangpo podcast March 2026).
