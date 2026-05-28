---
type: source
summary: Vitalik Buterin's June 2023 essay on the three near-simultaneous transitions Ethereum must undergo (L2 scaling, smart-contract wallets, privacy), framing the keystore-contract architecture and identity-not-address ideas relevant to Plurality's Section 4 (Identity / Association / Data).
raw_sources:
  - vitalik-three-transitions.md
---

## Bibliographic Info

- **Title**: *The Three Transitions*
- **Author**: Vitalik Buterin
- **Date**: 2023-06-09
- **URL**: https://vitalik.eth.limo/general/2023/06/09/three_transitions.html
- **Form**: blog post

## Summary

Three technical transitions — L2 scaling, smart-contract wallets, privacy — must happen together, and each one weakens the "one user ≈ one address" mental model. The post sketches a *keystore-contract* architecture that separates verification logic from asset holdings, and pushes the addressing problem from "20-byte hashes" toward a richer payment-information bundle (spending pubkey, encryption pubkey, stealth meta-address, etc).

## Key claims

- The naive idea of "an address = a user" is breaking because: each L2 is its own account, smart contract wallets give different addresses on different chains, and stealth-address privacy may give *one address per transaction*.
- A user's "payment information" must now include both a spending pubkey and an encryption pubkey — and this is also what enables Ethereum-native encrypted email and PGP-equivalent functionality.
- **Keystore contract**: one verification-logic contract per user (possibly on mainnet or one specific L2); addresses on other L2s point to it. Recovery copies the new pubkey into the keystore once, not into N separate addresses.
- Privacy compatibility requires Zupass-style local data holdings, which in turn means *wallets must secure data, not just keys* — a wallet hack now leaks history, not just funds.
- **Your name is not you**: ENS-centric identity is critiqued because ties to a single name make portability brittle and break counterfactual addresses. The keystore contract is offered as a name-free identity anchor.

## Concepts touched

- [[Identity-and-Personhood]] — a granular technical account of "an identifier" vs "the person"
- [[Data-Coalitions]] — wallets-as-data-custodians mirror the book's MIDs (Mediators of Individual Data)
- [[Access]] — addressing complexity as a UX barrier

## Significance for the wiki

Useful as a web3-stack-side complement to the book's Section 4-1 (Identity and Personhood) and 4-4 (Property and Contract / data as fiduciary). The book describes the *normative* requirements for plural identity; this essay supplies one concrete technical realisation. The "your name is not you" line is also a useful counterpoint to ENS-as-identity narratives that some Plurality-adjacent projects rely on.
