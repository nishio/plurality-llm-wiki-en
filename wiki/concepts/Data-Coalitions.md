---
type: concept
summary: Organizations that collectively steward and bargain with data on behalf of groups whose interests in that data are inherently shared — modeled on labor unions for the data economy.
sources:
  - plurality-book.md
---

## Definition

From [[plurality-book]] (chapters **4-4 Property and Contract**, **5-7 Social Markets**, **7-0 Policy**), Data Coalitions are organizations that:

- aggregate the **collective** data interests of groups (patients, drivers, neighborhoods, ethnic communities, professions),
- bargain over data licensing, sharing terms, and revenue share with the firms that train models on or build products from that data,
- exercise rights analogous to those labor unions exercise for workers — collective bargaining, the right to organize, legal protection against retaliation.

The book argues this organizational form is needed because data is **inherently relational** — virtually no data is purely individual — and so purely individual data rights (e.g., the GDPR-style framework) cannot capture the actual structure of interests.

## Why now

The rise of [[Generative-Foundation-Models]] (GFMs) has dramatically raised the stakes. Models trained on undisclosed data sets produce enormous value, yet:

- the data contributors are unaware and unpaid;
- traditional intellectual-property law is rigid and a poor fit (focused on "transformativeness" of a single use rather than continuous value flows);
- individual creators have no leverage against major model builders.

The book proposes that judges, legislators and regulators work with technologists to develop new standards that "back-propagate" value to data creators in proportion to the role their contributions play in model outputs — using tools like differential privacy, watermarking, and influence functions to estimate that role.

## Legal barriers

[[plurality-book]] notes that current law in many jurisdictions, especially the EU with its emphasis on individual data rights, may effectively **prevent** Data Coalitions from forming. The book draws an analogy: labor coalitions were illegal in many countries until the 19th century until labor law evolved; data law will need a parallel evolution.

It also points to other innovative organizational forms (Distributed Autonomous Organizations / DAOs, transnational non-profits) that currently lack supportive legal frameworks outside a few jurisdictions like Wyoming.

## Concrete near-precedents

- **Patient data unions** in some health contexts.
- **Gaia-X** in Europe and the **India Stack**'s data-sharing experiments.
- Performing-rights organizations (ASCAP, etc.) as a music-industry analogy.

## Related concepts

- [[Property-and-Contract]]
- [[Social-Markets]] — Data Coalitions are a key Plural market structure
- [[Identity-and-Personhood]] — group identity is presupposed
- [[Policy]] — legal reform is essential
- [[Adaptive-Administration]]

## Open Questions

- Who legitimately speaks for a "group" whose data is in question? Especially for genetic and demographic data, group boundaries are contested.
- How are revenue and governance rights split inside a Data Coalition itself? The book gestures at this but does not propose a specific design.

## Updates

### "Coalition" vs. "aggregation" (zero-knowledge)

From [[good-enough-ancestor-senate-canada]]: Tang sharpens a distinction the book leaves implicit. A **data coalition** is *not* the same as an **aggregation of data**. Multiple stakeholders can join a coalition without sharing any raw data at all — using **zero-knowledge technology** that allows proving capability or membership without revealing personally identifiable information.

Worked example from the testimony: Taiwan's COVID privacy-preserving contact tracing. A venue printed a random number in a QR code at the front door. A person scanned it and sent it to the trusted number 1922 via their telecom. "The telecom knew nothing about what the random number meant. The venue learned nothing — not even the phone number of the visitor. The state learned nothing whatsoever." Yet on infection, contact tracing and recursive notification still worked — without sacrificing the privacy of people outside the affected area.

### "Data as soil" — domain-specific local models

From [[safer-sovereignty]] and [[good-enough-ancestor-senate-canada]]: Tang's preferred slogan now is **data is not oil. Data is soil.** Domain-specific local models, trained inside the community that generates the data, are energy-efficient and continuously correctable.

Taiwan TCloud (台灣雲市集) subsidises up to 80% of SaaS purchases for small/medium enterprises — including the agricultural sector — letting users choose among thousands of solutions and switch freely. The result is interoperability, data sovereignty, and sector-trained models. Tang gives the **drone agricultural service platform** as an emblem: many small operators pooling equipment, certifying pilots, and sharing compliance records, achieving "a horizontal scale previously available only to large agribusiness." A financial-sector data coalition among banks and insurers is reported as adopting the same pattern.

### Enterprise application

From [[safer-sovereignty]]: when applied to enterprise AI, the data-as-soil principle becomes **decision sovereignty** — control not only over where data resides but over how AI may interpret it, what actions may follow, and how authority can be brought back in-house. The "first wave of data sovereignty asked, 'Where does data live?' The next must ask, 'Where does decision-making live?'"

### 2026-05-27: "Ex post facto" punishment for over-sharing → Taiwan's joint platform liability

[[plurality-book]] chapter 4-2 (Association and Plural Publics) notes that protecting against unilateral data over-sharing has "generally been thought essentially impossible to externally enforce", and that strategies have "focused on norms against over-sharing... attempts to make it hard to secretly over-share and policies to punish *ex post facto* those who do engage in oversharing." [[collaborative-immune-system]] reports that Taiwan's *Fraud Crime Hazard Prevention Act* now operationalises exactly this: **joint civil liability** for platforms that fail to remove infringing content within 24 hours (Article 32), with a safe harbour for good-faith removal (Article 38) — making *ex post facto* punishment for institutional over-sharing concrete and enforceable. The book identified the design pattern; the Taiwan fraud act executed it for AI-generated scam advertising.
