---
type: concept
summary: Plural protocols for sharing digital assets — storage, computation, and especially data — that decompose the rights to use, alter and profit, and treat data as inherently relational rather than individually owned.
sources:
  - plurality-book.md
---

## Definition

From [[plurality-book]] chapter **4-4 Property and Contract**, this concept covers protocols for shared use of the three central digital assets — **storage**, **computation**, and **data** — modeled on real-world property law's decomposition into:

- **usus** (the right to use),
- **abusus** (the right to alter or dispose),
- **fructus** (the right to the value created).

In the physical world, rental contracts assign these differently (a tenant has *usus*, the landlord retains *abusus* and *fructus*). The book argues digital assets need similar but more nuanced decomposition — and that this is hardest for data because granting *usus* tends to leak *abusus* and *fructus*.

## Examples and existing protocols

[[plurality-book]] surveys:

- **Storage**: IPFS / Filecoin from Protocol Labs (an explicit homage to [[JCR-Licklider]]'s "Intergalactic Computer Network"), used by Taiwan's Ministry of Digital Affairs.
- **Computation**: Cloud providers (AWS, Azure, GCP) dominate; the book argues this is essentially a regression to a more centralized "mainframe" model.
- **Data**: the most spectacular failure, with no widely adopted sharing standard. Gaia-X (EU), India's National Data Sharing and Accessibility Policy, Singapore's Trusted Data Sharing Framework, and Taiwan's Plural Innovation strategy are all flagged as attempts.

## Data as inherently relational

A central Plural claim of the chapter: **data is rarely individual**. Genetic data implicates relatives; geolocation implicates everyone you meet; social-media data implicates everyone you mention. Quick fixes built on individual privacy rights (GDPR-style) consequently impede progress rather than facilitating it.

The remedy the book proposes is [[Data-Coalitions]] — organizations that aggregate group-level data interests with legal protections analogous to labor unions for the data they steward.

## Smart contracts are not enough

The chapter is explicit that "smart contracts" cannot substitute for the slow co-evolution of contracts with **customary expectations, legal precedent, and mutual norms**. Self-enforcing digital contracts can implement norms smoothly only once those norms exist socially.

## Tools the book highlights for safe data sharing

- **Differential privacy** — a "privacy budget" limiting what can be inferred from queries.
- **Watermarking** — signatures embedded in outputs to detect provenance.
- **Influence functions** — tracing how a particular data input shapes a model's output, enabling partial attribution.
- **Federated learning** and confidential computing (also discussed in [[Association-and-Plural-Publics]]).

## Related concepts

- [[Data-Coalitions]]
- [[Identity-and-Personhood]], [[Association-and-Plural-Publics]], [[Commerce-and-Trust]]
- [[Access]]
- [[Adaptive-Administration]]

## Open Questions

- The book acknowledges that traditional intellectual-property regimes are a poor fit for back-propagating value from generative models to data creators; what should replace them?
- Group-level data ownership requires identifying which group "owns" the data — a contested question for indigenous knowledge, genetic ancestry, etc.

## Updates

### 2026-05-27: Polanyi's "fictitious commodities" → "data as soil"

The chapter cites Karl Polanyi's argument that "land, fuel, labor and capital" are "fictitious commodities" — heterogeneous, "tied to places, people and cultures" — and notes that "in some ways they are even more severe for digital assets." This Polanyian framing is the conceptual ancestor of Tang's post-book slogan **"data is not oil. Data is soil"** ([[safer-sovereignty]], [[good-enough-ancestor-senate-canada]]). What the book frames as a *commodification problem* (the simplifying fiction that data behaves like a uniform commodity), the Civic-AI manifesto reframes as a *cultivation principle* (data is the living ground in which decisions take root, and so must be tended locally).

### 2026-05-27: Customary expectations → Tronto's care ethics

The chapter is emphatic that "smart contracts" cannot substitute for the slow co-evolution of contracts with "customary expectations, legal precedent, and mutual norms" — that "self-enforcing digital contracts can implement norms smoothly only once those norms exist socially." Read with [[civic-ai-manifesto]], this prefigures Tang's argument for why **care ethics** (Joan Tronto) is the only viable AI-governance frame: consequentialism cannot foresee fast outcomes, and deontology breaks when "one interpreter runs 10,000× faster" than humans. Both the book and the manifesto reject *contract-as-complete-specification* in favour of *practice-grounded relational norms* — the book at the level of digital property, Tang at the level of AI behaviour.

### 2026-05-27: MIDs as direct precursor of bounded Kami

The chapter introduces **"Mediators of Individual Data" (MIDs)** — "unions for creative workers representing their content, or Wikipedia representing the collective interest of its volunteer editors" — with "fiduciary duties and norms or laws protecting against unilateral disclosure by a member (analogous to prohibitions against unilateral strikebreaking against unions)." The post-book Civic-AI **Kami** ([[civic-ai-manifesto]]) is structurally the same primitive applied to *action authority* rather than to *data*: a bounded local steward operating within a defined mandate for a defined community, with explicit charters, sunset clauses and federation rules. [[safer-sovereignty]] makes this lineage explicit by extending it to enterprise: decision sovereignty as bounded delegation.
