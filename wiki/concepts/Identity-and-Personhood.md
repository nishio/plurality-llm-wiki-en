---
type: concept
summary: A Plural account of digital identity as intersectional, relational and group-aware — built from verifiable credentials, decentralized identifiers, and the social graph rather than from a single state-issued ID.
sources:
  - plurality-book.md
---

## Definition

From [[plurality-book]] chapter **4-1 Identity and Personhood**, Plural identity is **networked and intersectional** rather than atomic. A person's identity is not a single state-issued ID but a bundle of:

- **claims** about them issued by many parties (employers, schools, communities, governments) — typically delivered as W3C Verifiable Credentials;
- **decentralized identifiers** (DIDs) that allow these claims to be presented without going through a closed proprietary namespace;
- the person's position in a **social graph** of relationships, which itself carries identity-relevant signals.

The book treats this as filling one of the "missing layers" of the internet diagnosed in [[The-Lost-Dao]] — no widely adopted non-proprietary identity protocol exists today.

## Why identity matters for Plurality

Many other Plural mechanisms presuppose a workable identity layer:

- [[Quadratic-Voting]] and [[Quadratic-Funding]] collapse under sybil attacks without it.
- [[Liquid-Democracy]] needs reliable individuation to prevent vote concentration.
- [[Adaptive-Administration]] needs to know which constituencies a person belongs to without forcing a single dimension.
- [[Data-Coalitions]] need group-level identity, not just individuals.

## Group identity, not just individual

A distinctive Plural claim: identity systems must represent **groups** — religions, civil-society organizations, communities of fate — as first-class entities, not just individuals. This is reflected in the "hypergraph" model in Figure 4-0-B of [[plurality-book]], where edges (groups) carry as much weight as nodes (people).

## Real-world precedents

The book points to:

- **India Stack** and Aadhaar as the largest-scale precedent for digital ID, with both achievements and concerns.
- Taiwan's identity work as part of its [[Digital-Public-Infrastructure]].
- Estonia's e-residency program.
- The web3 / decentralized-identity community (DIF, W3C VC, DIDComm v2).
- The Trust Over IP Foundation.

## Tension with individualist privacy frameworks

[[plurality-book]] notes that EU-style individual-rights privacy regulation (GDPR), while protective, can **impede** Plural identity by enforcing a strictly individual conception of data rights that struggles with group-level data interests. See [[Data-Coalitions]].

## Related concepts

- [[Association-and-Plural-Publics]] — the next chapter; groups as identity infrastructure
- [[Data-Coalitions]] — group identity in market form
- [[Digital-Public-Infrastructure]]

## Open Questions

- How do Plural identity systems handle bad actors and authoritarian co-option (e.g. a state insisting it is the issuer of a particular credential)?
- Can identity be made portable across jurisdictions without flattening cultural difference?
