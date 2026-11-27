# Aluna executive skills V1.3 — provenance and release notes

Seven self-contained, runtime-neutral skills; no scripts, hooks, credentials, personal profiles, client records or new memory backend. Existing skills untouched. New names use the aluna- prefix to avoid collisions. The active MCP registry may require refresh or reconnection after merging; this is not yet verified.

## Upstream research

- [blader/humanizer](https://github.com/blader/humanizer/blob/main/SKILL.md), inspected blob bc51a89764e96c0178c707a2a7158d8dca4e6920, MIT. Adapted a compact humanizer for client communication; license retained in its folder.
- [obra/superpowers verification-before-completion](https://github.com/obra/superpowers/blob/main/skills/verification-before-completion/SKILL.md), blob 7d45333cc4a49c57a80df6c1fe2fa777a207afbc, MIT. Adapted to files, business work and agent actions; license retained in its folder.
- [obra/superpowers writing-skills](https://github.com/obra/superpowers/blob/main/skills/writing-skills/SKILL.md), blob 09d76b79dd4080fe4dcc9bfb3c54d05dbff8a563. Reviewed the test-driven documentation approach; no wholesale import or runtime dependencies.
- [pskoett/self-improving-agent](https://github.com/pskoett/self-improving-agent/blob/main/self-improving-agent/SKILL.md), blob ed6c7793a866fe6b6de91a16483bba65e0f78e00. Reviewed for comparison; upstream license not located and implementation targets OpenClaw, so not imported.

The remaining protocols are newly authored generic Aluna/VERITAS adaptations based on the owner's earlier design: truth, red-team fact checking, event-triggered learning, commercial feedback and technical site surveys. No private archives or user-specific data are included.

## Validation

Each skill includes named triggers and acceptance scenarios. Structural checks and repository readback are distinct from live agent behavioural tests. Run the acceptance scenarios in a fresh assistant context after enabling the MCP. Compare baseline and skill-assisted outputs; record actual results before promotion. Do not claim the MCP has refreshed or the assistant has learned until observed.
