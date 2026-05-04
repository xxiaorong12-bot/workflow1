# Feedback Inbox

This file is the default remote feedback inbox for Codex collaboration.

## Operating Rule

From 2026-05-04 onward, user feedback and collaboration preferences should be recorded in GitHub instead of being kept only in local files.

Default behavior across projects:

- Record feedback in a GitHub repository whenever a remote repository is available.
- Prefer `feedback/inbox.md` for lightweight ongoing feedback.
- Convert feedback into issues, Skill Delta, docs, or PRs when it becomes actionable or structural.
- Do not leave important feedback only in local workspace files.
- Keep sensitive/private content out of public repositories unless the user explicitly approves it.

## Entries

### 2026-05-04

User preference: Upload recurring feedback to Git/GitHub rather than keeping it only locally. Apply this as the default behavior for all projects when a suitable GitHub repository is available.

Repository selected for this workflow: `xxiaorong12-bot/workflow1`.

User workflow preference: Use `skills-sh-importer` to discover, inspect, audit, and install useful Skills from `skills.sh`; use `plugin-creator` only when a discovered or installed Skill should become a durable Codex Plugin with marketplace visibility, bundled scripts/assets, or cross-project reuse. Keep one-off or experimental capabilities as Skills instead of promoting everything into Plugins.
