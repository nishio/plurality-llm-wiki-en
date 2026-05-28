---
type: source
summary: Vitalik Buterin's January 2022 essay arguing for non-transferable ("soulbound") NFTs as a primitive for community-based identity, the conceptual seed of the Decentralized Society paper later co-authored with Glen Weyl and Puja Ohlhaver.
raw_sources:
  - vitalik-soulbound.md
---

## Bibliographic Info

- **Title**: *Soulbound*
- **Author**: Vitalik Buterin
- **Date**: 2022-01-26
- **URL**: https://vitalik.eth.limo/general/2022/01/26/soulbound.html
- **Form**: blog post
- **Source repo**: `vbuterin/blog`, posts/soulbound.md

## Summary

Buterin proposes that NFTs could be more interesting if some of them could be made non-transferable — borrowing the term "soulbound" from World of Warcraft, where the most powerful items cannot be traded. The essay sets out three motivating use cases for non-transferable on-chain items: proof-of-attendance (POAP), credentials (driver's licenses, university degrees), and governance rights. The "underexplored design space of non-transferable NFTs" framed here becomes the technical backbone of *Decentralized Society* (DeSoc) and the SBT concept later co-authored with [[Glen-Weyl]].

## Key claims

- **Transferability undermines two distinct goals**: (i) wide distribution (concentrated capital buys up rights) and (ii) competence-based allocation (rights flow to the determined-but-incompetent rather than the meek-but-capable). The proverb "those who most want to rule are least suited" cuts against transferable governance tokens.
- **POAPs as the canonical example**: a proof-of-attendance token loses signaling value if it can be bought; observers want to know whether *you personally* attended, not whether anyone did.
- **Implementation spectrum**: "naive" non-transferability fails because users wrap NFTs in transferable accounts; the strongest extant non-transferability is the proof-of-humanity protocol's revocation feature (original owner can record a video and a Kleros court rules whether the seller is the original creator).
- **Privacy is part of the design, not bolted on**: soulbound items must support ZK-SNARK-based selective disclosure or the on-chain map of "everything bound to your face" becomes a coercive social signal.
- Closing motivation: web3 today is "too money-oriented"; soulbound primitives expand what NFTs can represent beyond wealth.

## Concepts touched

- [[Identity-and-Personhood]] — proof-of-humanity as anchor for soulbound items
- [[Plural-Voting]] — Buterin's critique of bought-up governance rights echoes the case for non-transferable voting power
- [[Quadratic-Funding]] — Gitcoin Passport later uses POAP-like attestations as Sybil-resistance signals
- Web3 / Ethereum identity primitives (POAP, ENS, Proof of Humanity, Kleros)

## Significance for the wiki

This is the seed essay for *Decentralized Society: Finding Web3's Soul* (Weyl, Ohlhaver, Buterin, May 2022) — the paper that gave the Plurality movement its web3-side technical vocabulary. Buterin's framing of "items that represent more of who you are and not just what you can afford" is the bridge from financialised NFTs to the Plurality-adjacent identity-and-association primitives in the book's Section 4.
