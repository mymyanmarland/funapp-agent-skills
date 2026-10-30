# Customization log — Funapp Agent Skills v1 starter

- Date built: 2026-10-31, on the owner's tap "ဒီပုံစံနဲ့ Funapp version စလုပ်ပေးပါ" in the side chat about the Poshan Pandey reel.
- Upstream: Addy Osmani agent-skills, short commit eb07f19, cloned 2026-10-31 to a temporary folder and copied (excluding .git) to this folder.
- Upstream LICENSE kept verbatim. Upstream README moved to UPSTREAM_README.md. At publish time plugin.json was updated to name funapp-agent-skills, version 0.1.0, repository https://github.com/mymyanmarland/funapp-agent-skills, author Funapp (upstream credit kept in README).
- Published 2026-10-31: repo https://github.com/mymyanmarland/funapp-agent-skills, v1 commit 865df5157e997fc7c4cd5be3e71326b0f2641eef (258 files). First push-tree attempt failed 403 on tree creation because the tree contained .github/workflows/test-plugin-install.yml and the token lacks workflow scope (same limit as earlier workflow uploads); that one file was omitted from the GitHub push (kept locally, noted in README, add manually via web UI if wanted) and the push was retried without it.
- Beautiful README: assets/banner.svg and assets/lifecycle.svg animated SVGs added at publish time, per the owner's standing GitHub-beauty rule.
- Added: references/funapp-rules.md — verbatim copy of ~/workspace/funapp-agent-pack/rules/AGENT_RULES.md (Funapp Agent Pack v1, sections 1-7).
- Edited (override block only, frontmatter and upstream body unchanged): spec-driven-development, planning-and-task-breakdown, incremental-implementation, test-driven-development, code-review-and-quality, shipping-and-launch, security-and-hardening, frontend-ui-engineering.
- Not edited in this starter (upstream verbatim): the other 17 skills in skills/.
- Correction applied during build: skill internal names and folders were NOT renamed to funapp-* (an earlier chat suggestion). Renaming would risk breaking commands/*.toml and plugin.json mappings. Repo/folder name funapp-agent-skills is the Funapp identity for v1; skill names stay upstream.
- Not done: Ko Pai deploy, Cursor deploy. Both need separate owner go. GitHub publish is done (see above).
