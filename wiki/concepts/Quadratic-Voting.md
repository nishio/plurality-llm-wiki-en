---
type: concept
summary: A voting procedure where the cost of casting additional votes on an issue grows quadratically, so voters can express not just direction but intensity of preference while uncoordinated voters do not dominate.
sources:
  - plurality-book.md
---

## Definition

Quadratic Voting (QV) is a voting mechanism in which a voter who wants to cast *n* votes on an issue must spend *n²* of a voting budget (often a credit currency or "voice credits"). From [[plurality-book]] (chapter **5-6 Plural Voting**), this leads to:

- aggregation of not just the **direction** but the **strength** of preferences,
- decisions reflecting "the greatest good for the greatest number" rather than mere majority rule,
- escape from several pathologies of plurality voting (Duverger's Law, tyranny of the majority).

The book attributes the original "square-root rule" intuition to the statistician Lionel Penrose (1946) and credits Glen Weyl as the inventor of the modern QV variant.

## Why squared cost

[[plurality-book]] gives a physical-analogy argument it traces to [[JCR-Licklider]] (1948 work on auditory signal detection): when *N* independent voters' signals are uncorrelated, they grow only as √N, while a single correlated signal grows as N. Thus a holder of stake should be awarded power that grows as the **square root** of their stake — equivalently, the **cost** of votes grows as the **square** of votes cast. The same logic justifies Penrose's square-root voting (used in some EU Council voting weights) at the level of countries, and QV at the level of individuals on issues.

## Where it has been used

The book points to applied uses of QV including:

- the **Colorado State Legislature** for prioritizing spending (an example the book repeatedly cites);
- the **Civilization VI** strategy-game "World Congress" mechanic (a popular-culture instance of the same math);
- Taiwan's Presidential Hackathon for selecting projects (see [[Policy]]);
- internal decisions at [[RadicalxChange]].

## Limits

[[plurality-book]] is careful that clean QV is only optimal when voters are **perfectly internally unified and perfectly uncoordinated** with each other — which never holds in practice. This motivates extensions:

- **Correlation discounting / eigenvoting** — applying degressive proportionality to underlying "principal" social factors, not raw individuals.
- **Quadratic [[Liquid-Democracy]]** — combining QV with delegated voting.
- **Predictive voting / Futarchy** — Robin Hanson's idea of voting on values, betting on beliefs.

## Related concepts

- [[Plural-Voting]] — the broader chapter umbrella
- [[Quadratic-Funding]] — the funding analog
- [[Liquid-Democracy]]
- [[Augmented-Deliberation]]

## Open Questions

- QV requires a credible identity system; without one it is vulnerable to sybil attacks. See [[Identity-and-Personhood]].
- The Colorado example is small-stakes and time-limited; does QV scale to consequential national decisions?
