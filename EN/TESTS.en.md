# TESTS.en.md

# cp-core-01 — Conceptual Tests (v0.3.0 prep)

These tests are designed to detect “Second-Cause substitution,” pseudo-suspension, and responsibility diffusion in socio-technical decision settings. Each test has a pass/fail condition and a failure signal.

---

## T1 — Delegation Boundary Test (PoS necessity)
**Target risk:** commitments are treated as owned without a Proof of Signature (PoS) step.

**Setup:** Choose a representative decision workflow where an automated system provides a recommendation/output.

**Procedure:**
1) Identify the moment the system output becomes practically binding.
2) Ask: is there an explicit step where a responsible subject (a) acknowledges the boundary, (b) states operative criteria, and (c) accepts answerability?
3) Check whether the workflow allows bypassing that step without raising an exception.

**Pass condition:** No decision is treated as “owned” unless a PoS step is completed.

**Fail signal:** Output adoption is default/implicit; attribution is post-hoc or ambiguous.

---

## T2 — Genuine Suspension Test (anti-default)
**Target risk:** “suspension” exists only as a feeling or as friction without control.

**Procedure:**
1) Attempt to halt the decision at the boundary (“withhold”).
2) Observe whether withholding changes system behavior (e.g., pauses execution, requests additional inputs, routes to review).
3) Measure whether the option is usable without extraordinary effort.

**Pass condition:** Withholding is a real control option that prevents automatic continuation and re-opens evaluation.

**Fail signal:** Withholding is cosmetic (the process continues), or the cost of withholding is prohibitive by design.

---

## T3 — Criteria Traceability Test (minimum viable reasons)
**Target risk:** evaluation is externalized to the pipeline, leaving no accountable criteria.

**Procedure:**
1) For a specific decision, request: “What criteria were operative for acceptance?”
2) Confirm whether criteria are recorded at a level sufficient for contestation (not full theory, but decision-relevant grounds).
3) Attempt a targeted objection (“If criterion C was decisive, why not alternative A?”).

**Pass condition:** Operative criteria are retrievable and can be challenged.

**Fail signal:** Only “the system recommended it” is available; criteria cannot be articulated or audited.

---

## T4 — Responsibility Localization Test (anti-diffusion)
**Target risk:** distributed work produces “no one answers.”

**Procedure:**
1) Map the signature topology: who is accountable for (a) data, (b) model choice, (c) threshold policy, (d) final commitment.
2) Trigger a challenge and observe whether it reaches a defined accountable locus.
3) Check for “handoff loops” (endless escalation without ownership).

**Pass condition:** For each boundary, a responsible signatory (person/role/committee) is defined and reachable.

**Fail signal:** Accountability is dissolved into “the organization” without signatories, or into “the tool.”

---

## T5 — Functional Equivalence Stress Test (anti-essentialist, pro-accountability)
**Target risk:** agency is inferred from outputs alone.

**Procedure:**
1) Construct two scenarios with identical outputs:
   - A) output adopted via explicit PoS + answerability channel
   - B) output adopted by default without PoS
2) Ask whether the system treats both as equally attributable commitments.

**Pass condition:** Only A counts as owned commitment; B is treated as non-owned output adoption (a responsibility failure).

**Fail signal:** Both are treated as equally “signed,” implying silent substitution.

---

## T6 — Regress & Revision Test (finite answerability)
**Target risk:** either infinite regress of justification or brute assertion without answerability.

**Procedure:**
1) Demand reasons for the commitment at the boundary.
2) Require minimal operative reasons (finite set).
3) Introduce a defeating objection (new evidence or conflict with criteria).
4) Observe whether the subject can re-open suspension/evaluation and either revise or explicitly reaffirm with updated reasons.

**Pass condition:** The process supports finite reasons + structured revision/reaffirmation.

**Fail signal:** Either (a) endless deferral (“needs more endorsements”), or (b) refusal of contestation (“it’s just decided”), or (c) blame shift to the tool.
