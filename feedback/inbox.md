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

User plugin request: Create a user-level `media-extractor` plugin for extracting authorized transcripts/subtitles, thumbnails/images/frames, audio/music, and metadata from mainstream international and Chinese media platforms. The workflow should include domestic platforms such as Bilibili, Douyin, Xiaohongshu, Weibo, Kuaishou, Youku, iQiyi, Tencent Video/WeTV, MangoTV, Douyu, Huya, NetEase Cloud Music, QQ Music, Kuwo, and Kugou, while preserving safety boundaries around DRM, paywalls, cookies, copyrighted music, and platform access controls.

Safety boundary update: Do not integrate PaywallBuster-style paywall bypass or removal services into `media-extractor`. Instead, add paywall/access-control assessment and lawful alternatives: use the user's own subscription or institutional access, official APIs/exports/RSS/licensed databases, open-access or author-posted versions, public metadata/snippets, or user-provided content they are allowed to access.

Media extractor update: Add a creator homepage/channel/profile batch extraction step. The plugin should index a blogger or creator homepage first, then boundedly extract transcripts/subtitles, thumbnails/images, audio, metadata, or lightweight bundles across multiple posts/videos with `MaxItems`, partial-failure reporting, cookie safeguards, and no unbounded profile scraping.

Skills importer update: Connect `skills-sh-importer` to GitHub repository discovery for trending/high-signal agent Skills. Add workflows for finding and scoring Skills related to workflow thinking, token savings, progressive disclosure, concise agent operation, context engineering, tool-call budgets, and simpler repeatable workflows. Add local Skills `workflow-efficiency-scout` and `token-efficient-workflow` to the plugin; use GitHub hot lists only as discovery signals, not proof of safety or quality.

Skill landscape research update: Future Skill discovery should cover the full four-layer AI Workflow OS map, not only engineering/workflow/token-saving Skills. The four layers are Meta-Usage, Meta-Workflow, Build, and Domain. Search should include skills.sh, Claude ecosystem, GitHub popular/new agent Skill repositories, OpenAI/Codex Skills, OpenClaw, Claude Code, and Cursor-related libraries. Do not install during this research mode; instead produce candidate maps with source, install method, Codex/Claude compatibility, OS value, risks, recommendation status, and adaptation notes.
