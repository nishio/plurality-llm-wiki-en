---
type: concept
summary: The protocols and rights for forming groups and "publics" online — federated messaging, end-to-end encryption, secure multi-party computation — so that civil society can exist independently of platform monopolies.
sources:
  - plurality-book.md
---

## Definition

From [[plurality-book]] chapter **4-2 Association and ⿻ Publics**, this is the Plural account of freedom of association in digital form: protocols and rights that let people form groups, hold private conversations, and constitute "publics" without being captive to a single corporate platform.

The chapter treats this as the digital analog of historic freedom-of-assembly and freedom-of-association rights, with the added challenge that on contemporary platforms the protocols (messaging, group membership, federation) are almost entirely controlled by a small number of proprietary firms.

## Technologies the book highlights

- **End-to-end encrypted messaging** standards (Messaging Layer Security / MLS, the IETF MIMI working group on Instant Messaging Interoperability, DIDComm v2 from the Decentralized Identity Foundation).
- **Secure multi-party computation (SMPC)** and **homomorphic encryption** — allowing many parties to compute on shared inputs without revealing them.
- **Federated learning / data federation** — training models or computing statistics across organizations without centralizing the underlying data.
- **Confidential computing** as a centralized but verifiable alternative.

## Plural publics

A central concept in the chapter is the "**Plural public**" — a group with internal common knowledge that is *not* automatically transparent to outside observers (including the state or platforms). Group-level privacy is treated as foundational to civil-society function, not as a luxury.

This contrasts with both:

- **Libertarian individualism**, which protects only individual privacy and treats groups as derivative;
- **Technocratic / surveillance** models, which treat group-level common knowledge as something to be either transparent to the state or non-existent.

## Related concepts

- [[Identity-and-Personhood]] — the prior layer; groups need identity
- [[Commerce-and-Trust]] — the next layer; groups underwrite trust
- [[Data-Coalitions]] — economic application of group-level computation

## Open Questions

- How do Plural publics interact with criminal investigation and counter-terrorism law? The book does not deeply engage with the encryption-vs-investigation debate.
- Federated messaging has historically lost out to single-platform dominance for network-effect reasons; what policy or design changes break the pattern?

## Updates

### 2026-05-27: Spritely / ActivityPub as precursor for federated trust & safety

The chapter explicitly names **Christine Lemmer-Webber**'s ActivityPub standard (foundation of Mastodon) and her **Spritely** project — "to create self-governing and strongly connected private communities in the spirit of Plural publics, allowing individual users to clearly discern, navigate and separate community contexts in open standards." Read with [[civic-ai-manifesto]] and [[collaborative-immune-system]], this prefigures Tang's post-book "federated trust & safety" lever: **ROOST.tools** (Robust Open Online Safety Tools, board member: Tang) is essentially Spritely-style federation applied not just to messaging but to *moderation infrastructure* — bridging the security and open camps so that small Plural publics can share trust-and-safety capabilities without consolidating into a single platform. The Utah Digital Choice Act's mandate for ActivityPub/AT Protocol/DSNP portability ([[ai-alignment-cannot-be-top-down]]) is the policy lever that turns ActivityPub's protocol promise into law.

### 2026-05-27: "Contextual confidence" as the Civic-AI substrate question

The chapter cites **Jain, Hitzig and Mishkin's "Contextual Confidence and Generative AI"** (arXiv 2311.01193, 2023) as the conceptual frame for Plural publics in the age of GFMs: "where participants in a system can easily establish and protect the context of their communications." This essay is now visible as the conceptual bridge between the book's *Plural publics* and Tang's post-book Civic-AI **Pack 3 (Competence)** and **Pack 6 (Symbiosis)**: bounded local models that operate within an established context cannot strain it because they are not trained to optimise outside it. Bengio's *Scientist AI* truthification pipeline ([[inside-the-kami]]) addresses precisely this same gap — separating "X is true" from "someone wrote X" is contextual confidence at the model level.
