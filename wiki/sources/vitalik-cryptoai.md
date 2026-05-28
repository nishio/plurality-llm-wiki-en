---
type: source
summary: Vitalik Buterin's January 2024 essay categorizing four kinds of crypto-AI intersections, with prediction markets seeded by AI players framed as the "highest viability" near-term application.
raw_sources:
  - vitalik-cryptoai.md
---

## Bibliographic Info

- **Title**: *The promise and challenges of crypto + AI applications*
- **Author**: Vitalik Buterin
- **Date**: 2024-01-30
- **URL**: https://vitalik.eth.limo/general/2024/01/30/cryptoai.html
- **Form**: blog post

## Summary

Buterin classifies crypto-AI intersections into four categories with very different risk profiles: AI as player in a game (high viability), AI as interface (medium, with adversarial-ML risks), AI as rules of the game (treacherous), and AI as objective of the game (long-term, requires FHE / cryptographic obfuscation to survive open-model leaks).

## Key claims

- **AI-as-player is the most mature**: arbitrage bots already work; the next frontier is *AI-populated prediction markets* (AIOmen as demo), where thousands of AIs price questions at sub-dollar stakes that would never attract humans. Once "prediction market" is a micro-primitive, it generalises to "is this post acceptable", "is this a scam", "is `0x1b54…` really Casinu Inu?" — *info defense* questions whose answers cannot safely be centralised.
- **The d/acc connection**: this maps directly to Buterin's earlier ["info defense" section of *My techno-optimism*](https://vitalik.eth.limo/general/2023/11/27/techno_optimism.html#info). Plurality is named alongside d/acc as the social-tech direction he wants to see scale.
- **Adversarial ML is the asymmetric risk**: open-source models are *more* vulnerable than open-source code because attackers can fuzz them indefinitely. So "AI as interface" requires keeping each player AI somewhat closed while keeping the *rules of the game* open.
- **AI judges are dangerous**: at most use AI for clearly-bounded subjective calls (e.g. work-product acceptance) and only with a market for second-opinions.
- **AI-as-objective**: Worldcoin-style fingerprints-of-humanity, decentralised AI training via FHE/MPC. Mostly aspirational; FHE is still ~1000× too slow.

## Concepts touched

- [[Futarchy]] — prediction markets as governance input
- [[Augmented-Deliberation]] — AI as adjudicator in micro-markets is a fine-grained cousin to bridging-based deliberation
- [[Generative-Foundation-Models]]
- [[Quadratic-Funding]] (Gitcoin / Worldcoin Sybil resistance)

## Significance for the wiki

Buterin and the Plurality book occupy adjacent territory on AI governance but with different vocabularies. Where Tang frames AI governance as bounded local Kami under continuous oversight ([[Civic-AI]]), Buterin frames it as decentralised market-based adjudication where AIs are players, not judges. The convergence point is "no centralised authority decides truth" — but the implementation diverges between *bridging deliberation* (Tang) and *micro-prediction-markets with AI participation* (Buterin). The wiki should record this as a real divergence, not paper it over.
