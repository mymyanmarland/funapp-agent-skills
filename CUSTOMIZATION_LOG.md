# Customization log — Funapp Agent Skills v1 starter

- Date built: 2026-10-31, on the owner's tap "ဒီပုံစံနဲ့ Funapp version စလုပ်ပေးပါ" in the side chat about the Poshan Pandey reel.
- Upstream: Addy Osmani agent-skills, short commit eb07f19, cloned 2026-10-31 to a temporary folder and copied (excluding .git) to this folder.
- Upstream LICENSE kept verbatim. Upstream README moved to UPSTREAM_README.md. Upstream plugin.json kept verbatim for now; update name/repository at publish time.
- Added: references/funapp-rules.md — verbatim copy of ~/workspace/funapp-agent-pack/rules/AGENT_RULES.md (Funapp Agent Pack v1, sections 1-7).
- Edited (override block only, frontmatter and upstream body unchanged): spec-driven-development, planning-and-task-breakdown, incremental-implementation, test-driven-development, code-review-and-quality, shipping-and-launch, security-and-hardening, frontend-ui-engineering.
- Not edited in this starter (upstream verbatim): the other 17 skills in skills/.
- Correction applied during build: skill internal names and folders were NOT renamed to funapp-* (an earlier chat suggestion). Renaming would risk breaking commands/*.toml and plugin.json mappings. Repo/folder name funapp-agent-skills is the Funapp identity for v1; skill names stay upstream.
- Not done: GitHub publish, Ko Pai deploy, Cursor deploy. All need separate owner go.
