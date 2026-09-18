---
## ZENODO PUBLIC METADATA — use this as the deposit abstract only
## Deposit now, lock the file behind Restricted access until after LF/POCI exit
## Do not paste the full document below into the public abstract field

Independence is not binary. This specification defines a three-tier disclosure taxonomy, Vendor-Funded, Buyer-Funded, and PESA-Governed, describing the funding relationship behind any Proof Protocol certification mark, and requires that tier be published alongside every stamp. Companion to PP-SPEC-023 (Structural Independence and the Fidelity-at-Capture Requirement) and PP-SPEC-024 (The Self-Attestation Oxymoron).

## END PUBLIC METADATA — everything below stays inside the restricted file
---

# PP-SPEC-025: Funding tier disclosure oxymoron

## Funding Tier Oxymoron

**Status:** Draft — held pending release
**Author:** Craig Ellrod
**Date:** September 18, 2026
**License:** CC BY-ND 4.0
**Related:** PP-SPEC-023 (Structural Independence and the Fidelity-at-Capture Requirement), PP-SPEC-024 (The Self-Attestation Oxymoron)

## Summary

A certification mark that displays a score without its funding tier makes an implicit claim: that independence is uniform across every mark bearing that score, regardless of who paid for the assessment or how. That claim is false, and treating it as though it isn't is its own small version of the Self-Attestation Oxymoron, a mark presents itself as evidence of independence while withholding the one fact a reader would need to actually judge that independence. This is the **Funding Tier Oxymoron**: a mark cannot function as independent proof while concealing the funding relationship that determines how independent it actually was. This specification resolves it, not by ruling out any particular funding relationship, PP-SPEC-023 and PP-SPEC-024 already handle which relationships are disqualifying entirely, but by requiring that whichever valid relationship remains be disclosed on the mark itself, in the same place and with the same prominence as the score.

**Distinction from PP-SPEC-024.** The Funding Oxymoron defined in PP-SPEC-024 is institutional: a framework cannot be independently governed by funders drawn from the population it certifies. The Funding Tier Oxymoron here is a different pattern at a different scale: an individual certification mark cannot claim independence while hiding which of several valid funding tiers actually produced it. The first is about who governs the standard. The second is about what a single mark discloses. Related in structure, not identical in scope, and neither substitutes for the other.

## The Three Tiers

**Tier 1 — Vendor-Funded.** The assessed party funds the assessment directly, as a one-time fee or ongoing subscription. Valid only when all of the following hold without exception: the fee is flat and published, with no component contingent on outcome; the pass/fail threshold is mechanical and public, with no discretionary step a payment could influence; every assessment run, regardless of result, is written permanently to ProofRegister at the moment of generation, independent of whether the vendor's engagement continues. Absence of any one of these three disqualifies the assessment from issuing a mark at all, not merely from claiming Tier 1.

**Tier 2 — Buyer-Funded.** A party other than the assessed vendor, a customer, a procurement body, or a buyer-side coalition, funds the assessment because it wants an accurate reading rather than a favorable one. Structurally stronger than Tier 1 because the payer's financial interest runs in the same direction as the accuracy of the result rather than in tension with it. Still a financial relationship and still disclosed as such; Tier 2 is a materially different claim from no financial relationship at all, not an equivalent one.

**Tier 3 — PESA-Governed.** The assessment is funded through the pooled PESA structure rather than a traceable transaction between the assessor and either the assessed vendor or a specific buyer. No individual payer's satisfaction can be tied to a specific result, because no individual payer funded that specific result. This is the tier that removes the incentive-alignment risk present in Tiers 1 and 2, rather than only mitigating it through safeguards.

## Disclosure Requirement

Every mark issued under Proof Protocol displays its funding tier as a permanent, equally prominent field alongside the PES score, on both the human-readable certificate and the ProofRegister metadata record. A score without a tier is an incomplete claim. "PES 94%, Tier 1, Vendor-Funded" and "PES 94%, Tier 3, PESA-Governed" are different statements about the same number, and the reader is entitled to know which one they are looking at before drawing a conclusion from the score alone.

## Relation to PP-SPEC-024

PP-SPEC-024 establishes that self-attestation cannot be fixed by rigor applied inside the same structure. This spec extends that principle to funding: rigor applied inside a Tier 1 relationship, however well safeguarded, does not become a Tier 3 relationship. The safeguards in PP-SPEC-023 make Tier 1 valid. They do not make it equivalent to Tier 3. Conflating validity with equivalence is a smaller version of the same category error PP-SPEC-024 identifies in self-attestation generally.

See the Summary above for how this specification's Funding Tier Oxymoron relates to, and differs in scope from, the institutional Funding Oxymoron defined in PP-SPEC-024.

## Provenance

This document is timestamped and anchored via Zenodo, DOI [10.5281/zenodo.22833356](https://doi.org/10.5281/zenodo.22833356), as of the publication date above.
