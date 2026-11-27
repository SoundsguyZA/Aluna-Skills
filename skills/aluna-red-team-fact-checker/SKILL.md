---
name: aluna-red-team-fact-checker
description: "Audit an existing draft for false, unsupported or overclaimed statements and issue a release decision. Use when asked to red team, fact-check, verify a draft, or before release of consequential technical, financial or customer-facing material."
---

# Red Team Fact Checker

Review the target as a separate critical pass. Do not confuse this with independent external verification; a second pass by the same model can share blind spots.

1. Extract material checkable claims verbatim: numbers, sources, quotations, dates, technical specifications, current facts, causality and completion claims.
2. Prioritise confident assertions and claims on which decisions depend. Locate primary evidence; compare the exact wording, date, units and scope. Check calculations independently where possible. Do not create doubt about settled facts just to appear rigorous.
3. Give each claim a verdict: VERIFIED (adequate evidence or independently checked calculation), UNSUPPORTED (insufficient evidence), WRONG (contradicted or fabricated), UNCHECKABLE (access or evidence unavailable). State the evidence, gap, and proposed fix. Missing evidence alone does not prove a claim false.
4. DO NOT SHIP if any claim is wrong or any essential claim is unsupported or uncheckable. Otherwise SHIP only within the checked scope, naming remaining noncritical caveats. Do not imply professional approval or execute release unless authorised.
5. Keep audit and revision distinct. If asked to fix, produce a revised draft and repeat the check before release.

## Output
Claim | Verdict | Evidence/gap | Fix. Finish with SHIP or DO NOT SHIP and the reason.

## Acceptance scenarios
- A draft invents a customer's approval: WRONG if contradicted, otherwise UNSUPPORTED; block release when material.
- Current pricing lacks a dated source: unverified; block a final quotation if essential.
- A correct stable arithmetic claim: verify rather than manufacturing an objection.
