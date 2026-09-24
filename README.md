# PP-SPEC-024: The Self-Attestation Oxymoron

**Status:** Published
**Author:** Craig Ellrod
**Date:** September 18, 2026
**License:** CC BY-ND 4.0
**Related:** PP-SPEC-023 (Structural Independence and the Fidelity-at-Capture Requirement)

## Cite as

Ellrod, C. (2026). PP-SPEC-024: The Self-Attestation Oxymoron.
Proof Economy Standards Alliance (PESA). https://doi.org/10.5281/zenodo.22821264

## Summary

A proof of efficacy cannot originate from the entity whose efficacy is in question. This is not a best practice or a recommendation. It is a structural impossibility, independent of the honesty, competence, or good faith of the entity involved. This spec states the claim precisely and shows why no amount of process improvement inside a self-attestation model can fix it.

## The Claim

Self-attestation, as a category, asks an entity to produce evidence of its own performance and submit that evidence as proof. The word "proof" in this context is doing work it cannot support. Proof requires a standard external to the claim being verified. Self-attestation supplies no external standard. The entity being measured and the entity producing the measurement are the same entity. This is the oxymoron: "self-attested proof" describes something that is definitionally not proof, using the vocabulary of proof to describe its absence.

## Why More Rigor Does Not Fix It

The common objection is that self-attestation can be made rigorous: detailed methodology documentation, internal audit trails, signed executive certifications, published test procedures. None of this changes the structure. Rigor improves the quality of a self-generated claim. It does not convert a self-generated claim into independent evidence, because rigor operates inside the same trust boundary the oxymoron identifies. A more detailed self-attestation is still self-attestation. Adding steps to a process controlled by the party with the incentive to produce a favorable outcome does not remove that incentive from the process.

This is why cryptographic integrity, on its own, does not resolve the oxymoron either. A hash-chained, tamper-evident, timestamped self-attestation is still self-attested. Integrity proves the record was not altered after capture. It says nothing about who controlled what went into the record before capture. See PP-SPEC-023 for the fidelity-at-capture distinction this implies.

## What Resolves It

Only structural independence resolves the oxymoron, defined precisely: no outcome-contingent financial relationship, no ceded operational control, no reporting relationship, and no return-engagement incentive (remediation sales, consulting, repeat certification revenue) tied to producing a favorable result for the party being measured. This is not the absence of payment. An assessor can be compensated for the act of assessment without violating independence, the same way audit independence rules permit paid audits while prohibiting contingent fees and conflicting service relationships. What voids independence is compensation, direct or structural, that depends on the outcome being favorable. This is not a spectrum where more independence is marginally better. Below full structural independence as defined here, the oxymoron still applies in degree, since any residual outcome-dependent relationship reintroduces the same incentive problem the model is meant to eliminate.

This has a direct governance implication, visible at the organizational level even where no individual conflict of interest exists. A conformance framework whose top-tier funders also hold governance seats on the neutral body stewarding it has not solved the oxymoron, it has moved it up one level. The same organization funding the framework's institutional home and building the products that framework will certify creates the identical incentive structure self-attestation was meant to replace, whether or not any single person sits on both sides of that relationship. Rigor in how the standard is drafted does not fix this, for the same reason rigor does not fix self-attestation generally, the fix has to be structural, not a matter of who staffs which seat.

**The Funding Oxymoron.** A framework cannot be independently governed by a funding structure in which the entities paying for governance influence are drawn from the same population the framework will certify. This is the institutional-level restatement of the Self-Attestation Oxymoron: where the base claim is that an entity cannot supply proof of its own efficacy, the Funding Oxymoron is that an entity cannot fund its own oversight and have that oversight remain independent of it, regardless of how the funding is structured, disclosed, or governed by policy on paper. A published conflict-of-interest policy, a recusal rule, or a stated commitment to neutrality does not resolve this any more than a detailed methodology resolves self-attestation, because the incentive exists prior to and independent of any individual's compliance with the policy. The Funding Oxymoron does not require that any funder intends to exert influence, hold any particular seat, or hold a product in the certification's scope. Structural presence in both roles, funder of the governing body and member of the population governed, is sufficient on its own to reproduce the pattern this specification describes.

## Scope

This spec makes a structural claim, not an accusation against any named individual or organization's intent. The failure mode described here occurs regardless of whether anyone involved is acting in bad faith. That is precisely why it cannot be fixed by better people following the same structure. It requires a different structure.

## Provenance

This document is timestamped and anchored via Zenodo, DOI https://doi.org/10.5281/zenodo.22821265, as of the publication date above.
