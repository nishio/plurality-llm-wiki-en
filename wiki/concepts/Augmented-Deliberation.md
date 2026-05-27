---
type: concept
summary: Using digital tools — bridging algorithms, AI facilitation, broad listening — to scale high-quality deliberation across diversity, beyond the historic trade-off between depth and breadth.
sources:
  - plurality-book.md
---

## Definition

From [[plurality-book]] chapter **5-4 Augmented Deliberation**, this is the use of digital technology to relieve the historic trade-off between **diversity of voices** and **bandwidth of conversation**. As Herbert Simon noted, "a wealth of information creates a poverty of attention"; methods of broadcast have improved enormously while **broad listening** — one person thoughtfully digesting a range of perspectives — remains expensive and rare.

Augmented Deliberation seeks to use software, AI, and facilitation methods to make broad listening, structured small-group dialog, and consensus-finding feasible at scale.

## Concrete tools the book highlights

- **Pol.is** — the participatory polling tool used in [[vTaiwan]] that surfaces statements with cross-cleavage agreement (used in 2-2 case studies).
- **Community Notes** (formerly Birdwatch) on X — a bridging-based fact-checking system in which notes are surfaced when raters from across the platform's left/right opinion spectrum agree they are helpful. The book devotes a Figure (5-4-A) to Community Notes and cites the Birdwatch research literature.
- **Citizen deliberative councils** — sortition-selected small groups, sometimes paired with software for harvesting outputs.
- **World Café** and **Open Space Technology** facilitation patterns.
- **Liberating Structures** and the **National Coalition for Dialogue and Deliberation** as a research/practitioner network.

## Bridging algorithms

A central technical idea: rather than recommending content predicted to maximize engagement (which tends to entrench filter bubbles per [[Cass-Sunstein]]'s *#republic*), bridging algorithms surface content that earns approval from **diverse** clusters of users. The book argues bridging algorithms — like Community Notes — are exposed to hundreds of millions of people weekly and constitute the largest-scale concrete instance of Plurality on the contemporary internet.

## Broad listening

The book attributes the concept of "broad listening" to Andrew Trask (no published reference; the book documents this attribution explicitly). It pairs the term with augmented-deliberation tools that summarize large bodies of input for a single reader.

## Selection of participants

Augmented Deliberation typically combines technology with methods for choosing whose voice enters the conversation:

- **Election** (campaigns, voting),
- **Sortition** (random selection, used in citizen assemblies),
- **Administration** (bureaucratic assignment by merit),

each with different trade-offs of legitimacy, expertise, and participation.

## Related concepts

- [[Plural-Voting]] — voting is thin where deliberation is thick
- [[vTaiwan]], [[Join]] — instances in the wild
- [[Adaptive-Administration]] — administrative-side counterpart
- [[Connected-Society]] — the social theory underpinning bridging

## Open Questions

- Bridging algorithms depend on platform owners' willingness to optimize for cross-cleavage agreement rather than engagement; ownership changes can reverse the optimization overnight.
- AI facilitation risks introducing the facilitator's biases at scale; the book leaves this open.

## Updates

### "Alignment Assembly" as the post-book canonical instance

From [[civic-ai-manifesto]], [[ai-alignment-cannot-be-top-down]], [[collaborative-immune-system]], and [[good-enough-ancestor-senate-canada]]: the **Alignment Assembly** is now the canonical Tang/Civic-AI instance of Augmented Deliberation. The Taiwan 2024 anti-deepfake-scam case used a "diamond" structure: 200,000 SMS messages (a "democracy lottery") for *Discovery* (open) → 447 demographically-representative citizens deliberating in 44 virtual tables of ~10 for *Definition* (protected) → AI assistants (similar to Google Jigsaw's Sensemaker) providing real-time transcripts, facilitation, and proposal synthesis. The output earned 85%+ cross-partisan support and translated within months into the *Fraud Crime Hazard Prevention Act*.

### The "duck-rabbit" legitimacy logic

From [[civic-ai-manifesto]]: an Alignment Assembly is intentionally a "duck-rabbit" — from one side it looks like a deliberation, from the other it looks like a rigorous demographically-stratified poll. Both readings produce legitimacy for the legislature.

### Group size and the YIMBY/NIMBY → MIMBY shift

From [[civic-ai-manifesto]]: "When polled individually, people tend toward YIMBY or NIMBY (Yes/Not In My Backyard). But when deliberating in small groups (e.g., groups of 10), people shift to MIMBY (Maybe In My Backyard, if…)." Group deliberation "engages a different aspect of us and inoculates against outrage, an effect that can last for years."

### Collaborative Notes: AI-drafted, human-corrected

From [[good-enough-ancestor-senate-canada]]: X.com's new *Collaborative Notes* are drafted by AI and instantly corrected by humans, "so AI can learn what can translate across communities. For example, between the climate-justice community on one side and biblical creation care on the other, so they can translate across their vocabularies."

### Concrete spread

From [[civic-ai-manifesto]]: **Takahiro Anno** ran for Tokyo governor (Japan, 2024) using AI sensemaking and a phone-callable AI voice clone for crowdsourcing policy; his Team Mirai is now a national party in Japan's Diet. **Engaged California** (with Governor Newsom's team) was pivoted from teen-social-media deliberation to LA wildfire recovery planning; a later 10-week deliberation engaged 1,400+ state employees and generated 2,600+ ideas on government efficiency that informed executive action.

### 2026-05-27: Anno's Tokyo campaign is described in the book itself

The book's "Frontiers of augmented deliberation" section already chronicles Anno's 2024 Tokyo gubernatorial run in detail (citing the AnnoManifest, the **AI-Anno virtual avatar** on YouTube that answered ~7,400 questions in 16 days at 77% of the rate of a single human respondent, and the resulting 150,000 votes / 5th-place finish — "the highest number of votes for a candidate in their 30s in the 22 past Tokyo gubernatorial elections"). What [[civic-ai-manifesto]] adds is the *political trajectory*: Anno's Team Mirai became a national party in Japan's Diet. The book captured the technical innovation in real time; the post-book material captures the political payoff.

### 2026-05-27: Anthropic Collective Constitutional AI / OpenAI Collective Alignment Team prefigure the "industry norms" lever

The chapter explicitly cites **Anthropic's Collective Constitutional AI** (with the Collective Intelligence Project, sourcing the Claude 3 constitution via Polis) and **OpenAI's "Democratic Inputs to AI" grant program** leading to a "Collective Alignment Team." Tang's [[ai-alignment-cannot-be-top-down]] (Nov 2025) takes these as the seeds of the three-pillar Civic-AI policy stack: **public model specifications with clause-level reasoning citations** (Anthropic's Constitution, OpenAI Model Spec, ROOST's `gpt-oss-safeguard`), **market design** (Utah Digital Choice Act), and **community-scale assistants** (Polis, RLCF). The book sketched the experiments; the post-book essay names them as the substrate for *industry norms* — the first pillar of horizontal alignment.

### 2026-05-27: Cortico/Fora as precursor of bridging-based RLCF

The chapter highlights **MIT Center for Constructive Communication's Cortico/Fora platform**, which "uses a mixture of the identity and association protocols... and natural language processing to allow recorded conversations to remain protected and private while surfacing insights that can travel across these conversations and spark further discussion" — and which helped inform Michelle Wu's 2021 election as Boston's first Taiwanese-American mayor of a major US city. This combination of *protected local conversation* + *cross-community insight surfacing* is exactly the design intent of **RLCF (Reinforcement Learning from Community Feedback)** named in [[ai-alignment-cannot-be-top-down]] and **Collaborative Notes** (X.com AI-drafted, human-corrected) named in [[good-enough-ancestor-senate-canada]] — "so AI can learn what can translate across communities."

### 2026-05-27: Latour's "parliament of things" / The Lorax → Kami

The chapter's most striking speculative passage cites **Bruno Latour's "parliament of things"** and Dr. Seuss's **Lorax** — "Dr. Seuss's mythical creature who speaks for the trees and animals that cannot speak for themselves" — as candidates for GFM-mediated representation of natural systems. [[civic-ai-manifesto]] introduces the **Kami** metaphor (Japanese Shinto guardian spirits) with almost the same phrasing: "There might be a local Kami of a specific river, a particular forest, or even an old tree. Whatever the form, its entire existence and purpose are interwoven with the health of that one thing." The book offered the *representation* angle (a Lorax speaks for the trees in deliberation); Tang's post-book frame extends it to *stewardship* (a Kami acts as bounded administrator of that one thing).
