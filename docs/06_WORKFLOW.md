# Two-Developer Workflow
**Suggested cadence, not required:** Monday plan and select GitHub Issues; Tuesday–Thursday build separately and push often; Friday review PRs, tests and decision changes.

1. Both clone the same private repo. `git pull` before editing.
2. Give each Issue a single primary owner, boundaries, and acceptance test.
3. Branch per Issue; Codex/Claude Code must read AGENTS.md and current docs before edits.
4. Commit/push, open a PR; partner reviews and tests before merge.
5. Store notes in `docs/` via Obsidian, then commit/push those Markdown files.
6. Large raw datasets go outside Git; link to their location in test metadata.

## Hand-off record
Issue / owner / what AI suggested / what actually changed / files / tests and results / unverified / decisions needed / next action.
