---
type: concept
summary: A matching-funds formula for public-goods funding in which the matching pool weighs the square root of each contribution and squares the sum, so projects with broad small-donor support get more matching than projects funded by a few large donors.
sources:
  - plurality-book.md
---

## Definition

Quadratic Funding (QF) is the canonical Plural funding formula presented in [[plurality-book]] chapter **5-7 Social Markets**. Each project's matching allocation is computed roughly as:

> *matching* ∝ (Σᵢ √cᵢ)² − Σᵢ cᵢ

where *cᵢ* is the contribution of donor *i*. The "minus the sum" piece is the donors' direct contribution; the matching pool covers the rest.

The effect is that **breadth of support across socially distant contributors** is weighted far more than **depth of support from a few large donors**. Two $10 donations from two people produce more matching than one $100 donation; a million pennies from a million people matches more than one million-dollar check.

## Where it is used

[[plurality-book]] cites:

- **[[Gitcoin]] Grants** — the largest-scale deployment; over $100M channeled in total at the time of the book.
- **Web3 / Ethereum** public-goods funding rounds.
- Funding for the [[plurality-book]] itself ($332.84 from 87 contributors per the book's screenshot of its own Gitcoin page).
- Use in Taiwan civic-tech and increasingly outside open-source software (environment, local business).

## Why it is "Plural"

The book frames QF as the funding analog of [[Quadratic-Voting]] and as the most direct embodiment of [[Connected-Society]] in market form: the formula rewards funding that crosses **social distance** rather than funding from a single concentrated bloc. The book points to extensions:

- **Pairwise / clustering QF** — additional discounting when contributors are correlated (e.g. members of the same DAO or geographic cluster) to defend against collusion.
- Application to [[Data-Coalitions]] and other Plural markets.

## Theoretical grounding

[[plurality-book]] grounds QF in the concept of **supermodularity** (the whole greater than the sum of parts) discussed in chapter 5-0. Where ordinary capitalism treats deviations from bilateral exchange as "externalities" or "frictions", Plural markets like QF treat **group-level effects** as the central object to be funded.

## Related concepts

- [[Quadratic-Voting]] — the voting analog
- [[Social-Markets]] — the chapter umbrella
- [[Data-Coalitions]] — another Plural market structure
- [[Connected-Society]] — the social-theory underpinning
- [[Gitcoin]]

## Open Questions

- QF needs identity systems robust against sybils; without them the formula collapses. See [[Identity-and-Personhood]].
- Plural funding outside open-source software (where contributor identity is partly self-policing) is more vulnerable to manipulation; the book acknowledges this is an open problem.
