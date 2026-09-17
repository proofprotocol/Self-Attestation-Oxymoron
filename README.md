---
## ZENODO PUBLIC METADATA — use this as the deposit abstract only
## Deposit now, lock the file behind embargo until after LF/POCI exit
## Do not paste the full document below into the public abstract field

A proof of efficacy cannot originate from the entity whose efficacy is in question. This specification formalizes that claim, the Self-Attestation Oxymoron, and defines why structural independence, not procedural rigor or cryptographic integrity alone, is the only property that resolves it. Companion to PP-SPEC-023 (Structural Independence and the Fidelity-at-Capture Requirement).

## END PUBLIC METADATA — everything below stays inside the embargoed file
---

# PP-SPEC-024: The Self-Attestation Oxymoron

**Status:** Published
**Author:** Craig Ellrod
**Date:** Sept 17, 2026
**License:** CC BY-ND 4.0
**Related:** PP-SPEC-023 (Structural Independence and the Fidelity-at-Capture Requirement)

## Summary

A proof of efficacy cannot originate from the entity whose efficacy is in question. This is not a best practice or a recommendation. It is a structural impossibility, independent of the honesty, competence, or good faith of the entity involved. This spec states the claim precisely and shows why no amount of process improvement inside a self-attestation model can fix it.

## The Claim

Self-attestation, as a category, asks an entity to produce evidence of its own performance and submit that evidence as proof. The word "proof" in this context is doing work it cannot support. Proof requires a standard external to the claim being verified. Self-attestation supplies no external standard. The entity being measured and the entity producing the measurement are the same entity. This is the oxymoron: "self-attested proof" describes something that is definitionally not proof, using the vocabulary of proof to describe its absence.

## Why More Rigor Does Not Fix It

The common objection is that self-attestation can be made rigorous: detailed methodology documentation, internal audit trails, signed executive certifications, published test procedures. None of this changes the structure. Rigor improves the quality of a self-generated claim. It does not convert a self-generated claim into independent evidence, because rigor operates inside the same trust boundary the oxymoron identifies. A more detailed self-attestation is still self-attestation. Adding steps to a process controlled by the party with the incentive to produce a favorable outcome does not remove that incentive from the process.

This is why cryptographic integrity, on its own, does not resolve the oxymoron either. A hash-chained, tamper-evident, timestamped self-attestation is still self-attested. Integrity proves the record was not altered after capture. It says nothing about who controlled what went into the record before capture. See PP-SPEC-023 for the fidelity-at-capture distinction this implies.

## What Resolves It

Only structural independence resolves the oxymoron, defined precisely: no outcome-contingent financial relationship, no ceded operational control, no reporting relationship, and no return-engagement incentive (remediation sales, consulting, repeat certification revenue) tied to producing a favorable result for the party being measured. This is not the absence of payment. An assessor can be compensated for the act of assessment without violating independence, the same way audit independence rules permit paid audits while prohibiting contingent fees and conflicting service relationships. What voids independence is compensation, direct or structural, that depends on the outcome being favorable. This is not a spectrum where more independence is marginally better. Below full structural independence as defined here, the oxymoron still applies in degree, since any residual outcome-dependent relationship reintroduces the same incentive problem the model is meant to eliminate.

This has a direct governance implication. A conformance framework whose working group is chaired by employees of companies holding the certification the framework governs has not solved the oxymoron. It has formalized it. The chair's employer benefiting from the standard the chair helps write is self-attestation at the institutional level, dressed in the language of a standards body.

## Scope

This spec makes a structural claim, not an accusation against any named individual or organization's intent. The failure mode described here occurs regardless of whether anyone involved is acting in bad faith. That is precisely why it cannot be fixed by better people following the same structure. It requires a different structure.

## Provenance

This document is timestamped and anchored via Zenodo, DOI [INSERT DOI], as of the publication date above.
