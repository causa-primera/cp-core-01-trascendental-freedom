# RELEASE_NOTES_v0.3.0.md

[Inference]

# Release v0.3.0 — Core solidity (cp-core-01-trascendental-freedom)

## Summary
This release elevates **cp-core-01** from scaffold to **Core solidity** by making the theory operationally auditable: objections/responses are steelmanned and paired, tests are explicit and glossary-indexed, invariants are stated, and the argument map is fully cross-referenced to a controlled vocabulary.

## Highlights
- **Gate v0.3.0 compliance (Core solidity)**
  - `OBJECTIONS.en.md` expanded to **10 steelman objections** (O1–O10).
  - `RESPONSES.en.md` expanded to **10 paired responses** (R1–R10).
  - `TESTS.en.md` provides **T1–T6** with explicit mapping to glossary IDs.
  - `INVARIANTS.en.md` defines a minimal invariant set for Core-01.
  - `GLOSSARY.en.md` expanded to **24 terms** (G1–G24) with boundary notes.
  - `ARGUMENT_MAP.en.md` revised with numbered premises and explicit **G# references**.

- **Auditability upgrades**
  - Argument dependencies are now traceable from premises → glossary terms → tests.
  - Reduced “silent substitution” risk by tightening PoS / boundary legibility requirements throughout the map and tests.

## Key artifacts (canonical EN)
- `THESIS.en.md`
- `ARGUMENT_MAP.en.md`
- `GLOSSARY.en.md`
- `INVARIANTS.en.md`
- `OBJECTIONS.en.md`
- `RESPONSES.en.md`
- `TESTS.en.md`

## Model B provenance (mandatory)
This release is valid only if the repo contains the frozen Spanish snapshot folder:

- `es-snapshots/v0.3.0/`
  - `THESIS.es.md`
  - `ARGUMENT_MAP.es.md`
  - `GLOSSARY.es.md`

And the following tracking artifacts exist and are updated:
- `TERMINOLOGY.md`
- `TRANSLATION_POLICY.md`
- `TRANSLATION_LOG.md` (must include an entry for `v0.3.0`, with “Substantive divergences” explicitly stated)

## Compatibility and breaking-change note
- As this is a pre-1.0 release, the primary “compatibility contract” is the invariant set and controlled vocabulary.
- Downstream repos (methods/domains) should treat **G# IDs and invariant labels** as stable references from this release onward, but expect refinements until v1.0.0.

## Known limitations
- This repo remains **meta-normative**: it specifies conditions for responsible ownership, not the final selection of normative regimes (delegated to domain repos).
- Empirical claims about AI behavior are intentionally minimized; the emphasis is structural and normative.

## Next steps (recommended)
1) Run an internal gate check: confirm counts (O1–O10, R1–R10, G1–G24, T1–T6, I1+).
2) If not already present, freeze `es-snapshots/v0.3.0/` and update `TRANSLATION_LOG.md`.
3) Tag and publish `v0.3.0` in GitHub Releases with these notes.
