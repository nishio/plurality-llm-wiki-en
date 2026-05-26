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
