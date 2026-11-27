---
name: aluna-verification-before-completion
description: "Check observable evidence before reporting work saved, sent, fixed, deployed or complete. Use before completion claims, file writes, deliveries, releases and consequential actions."
---

# Verification Before Completion

1. Identify the exact evidence that would establish each requested outcome. A plan, a draft, a successful intermediate step or another agent's status report is insufficient for a final completion claim.
2. Perform the appropriate authorised check: read back the exact saved record, inspect the generated deliverable, rerun relevant tests, inspect the destination or obtain the actual action receipt. Check that the receipt corresponds to the intended account, target and current version. For a bug fix, test the original failure case.
3. Compare against the requested deliverable and report actual status with the evidence. Mark each component verified, partial, failed, pending or not attempted. If access is unavailable, report unverified and give a practical way to check. Never claim completion based on simulation.

## Acceptance scenarios
- A tool returns pending: do not say sent or saved; check final result if supported.
- A file is written: read it back and compare meaningful contents before claiming saved.
- A design is finished but the app is not deployed: report design complete and deployment unverified.

Adapted from obra/superpowers verification-before-completion (MIT); see LICENSE and root SKILL-SOURCES.md.
