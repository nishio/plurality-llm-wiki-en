---
type: concept
summary: A voting method in which any voter may delegate their vote(s) to others, who may then re-delegate, allowing bottom-up emergent representation; combined with quadratic rules to avoid power concentration.
sources:
  - plurality-book.md
---

## Definition

From [[plurality-book]] chapter **5-6 Plural Voting**, Liquid Democracy (LD) extends proportional representation by letting any voter **delegate their vote(s) to anyone else**, who may **re-delegate** in turn, producing dynamic, emergent patterns of representation rather than fixed elected bodies.

The book traces the idea to [[Charles-Dodgson]] (the mathematician better known as Lewis Carroll, *The Principles of Parliamentary Representation*, 1884), who first studied the question of weighting votes for people holding multiple votes — the same line of thinking that later led to [[Quadratic-Voting]].

## Where it appears

[[plurality-book]] notes LD's use in:

- corporate and DAO governance (decentralized autonomous organizations),
- a limited set of political contexts (Iceland is mentioned),
- the Ethereum / web3 ecosystem.

## Tendency toward concentration

A core limitation flagged in the book: LD has an "**unfortunate tendency to concentrate power**", since delegations tend to flow toward a small number of high-trust hands. This has somewhat soured initial enthusiasm.

The book offers a Plural fix: **Quadratic Liquid Democracy** (implemented by [[RadicalxChange]] internally for its own governance), which applies degressive proportionality (the square-root rule) to delegated voting weights, preventing super-delegates from accumulating disproportionate power.

## Related concept: divicracy

A footnote in [[plurality-book]] flags a related concept — **dividual democracy ("divicracy")** — originated by Ken Suzuki. Unlike standard LD, divicracy allows splitting one's vote across multiple positions on a single issue (drawing on Gilles Deleuze's notion of the "dividual" against the indivisible "individual"). The book treats this as a political extension of LD into a richer identity model.

## Related concepts

- [[Quadratic-Voting]] — same intellectual lineage ([[Lionel-Penrose|Penrose]], [[Charles-Dodgson|Dodgson]])
- [[Plural-Voting]] — umbrella term
- [[Identity-and-Personhood]] — LD presupposes a workable identity layer
- LD is implemented at internet scale only when paired with adequate identity infrastructure

## Open Questions

- Is the tendency to concentration a flaw of LD itself, or of the specific contexts (DAOs, corporate governance) where it has been tried?
- How does LD interact with delegation in non-political settings such as open-source maintainership?

## Updates

### 2026-05-27: divicracy footnote refreshed by upstream PR #1050

From [[pluralitybook-upstream-2024-2026]] (PR #1050, Taiyou, merged 2024-12-21): the chapter 5-6 footnote that defines divicracy has been **renamed and rewritten** in the upstream EN manuscript. The footnote tag changed from `[^PICSY]` to `[^Divicracy]` (PICSY moved to chapter 5-7 in PR #1051), and the body now reads:

> "Dividual democracy a.k.a 'divicracy', originated with Ken Suzuki. Unlike LQ, divicracy includes not only delegation of one's vote to others but also splitting one's vote to multiple political issues. Divicracy is a political extension of the concept, 'dividual', by the influential 20-century French philosopher, Gilles Deleuze, allowing diverse and potentially contradictory ideas within a person as opposed to the 'individual' concept of identity. Suzuki introduced the concept in 2000s and elaborated in his book in 2013. Ken Suzuki, 'The Nameraka Society and its Enemies', Keiso Shobo Publishing (2013)."

The new wording makes the **vote-splitting** mechanism (not just vote-delegation) explicit, and now anchors divicracy in [[Ken-Suzuki]]'s broader [[Nameraka-Society]] vision. See those pages for the full context.
