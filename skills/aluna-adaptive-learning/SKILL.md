---
name: aluna-adaptive-learning
description: "Turn meaningful corrections, mistakes and outcomes into tested reusable procedures. Use after consequential failures, user corrections, successful workflows, customer feedback, or task retrospectives."
---

# Adaptive Learning

This is an event-driven workflow. No heartbeat, model retraining or automatic persistence is implied.

1. Record a dated incident with evidence, scope, observed result and unresolved questions. Separate cause hypotheses from confirmed cause. Remove private identifiers and secrets from any shared skill.
2. Correct affected work. Retrieve existing applicable rules; amend a relevant one rather than creating duplicates. A single outcome does not establish a general rule.
3. Propose a narrowly scoped skill: ID, version, trigger, provenance, procedure, completion criteria, test cases, owner and status. Record the original failure as the baseline and a comparable unseen case, including a counterexample where the rule should not trigger.
4. Test on actual available runtime or clearly label a desk review or simulated scenario as such. Compare results to baseline; record failures and revise. Never describe an unrun or simulated test as a live pass.
5. Obtain owner approval for standing changes. Keep core permission and safety boundaries intact. Save to an authorised private store or propose a sanitised change to the shared skills repository; read back before claiming persistence. Never write client records to a public repo. If storage unavailable, provide a portable record.
6. Retrieve approved relevant skills before similar work; review when facts, sources, requirements or dependencies change. Preserve incident history and superseded versions. Track recurrence and escalate serious repeated failures.

## Acceptance scenarios
- User corrects name spelling: update deliverable, test exact spelling and unrelated names, propose narrow correction; do not claim saved unless verified.
- Customer rejects a price: record objection, investigate alternatives without concluding price was objectively wrong.
- Tool write fails: distinguish failed write from successful readback and do not promote an untested workaround.
