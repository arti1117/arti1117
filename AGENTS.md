# Repository Instructions

This file provides repository-specific instructions for coding agents and human contributors.

Workspace-level rules (publication boundary, single-copy rule, honesty constraints) live in `../AGENTS.md` and govern everything here.

## What this is

JY's GitHub profile repo — `README.md` renders on `github.com/arti1117` (GitHub's special same-name-as-username repo behavior; don't remove the HTML comment at the bottom of `README.md` explaining that). Content-only repository; no build or tests.

- `README.md` — Korean, short. Current backend profile, job-search status, verified stack, and links to the résumé, LinkedIn, and blog. Keep changes small and infrequent — this is a landing page, not a changelog.
- `RESUME.md` — the **published** résumé. Per the single-copy rule, its source of truth for edits is `arti1117.private/JY_resume_ko_v11.md`; this file is the public copy. They sync deliberately, not automatically — don't assume they match, and don't edit `RESUME.md` directly for content changes that should originate in the private draft.

## Sibling learning repositories

`fleet-master-controller` and `sentinel-systems` remain sibling learning and research repositories, but they are not current profile flagships. Do not promote them on the profile without a new JY decision. Read each repository's `AGENTS.md` and `README.md` before changing it.

## File placement (MECE, 2026-09-13)

All three files have distinct responsibilities: `README.md` is the GitHub profile entry point, `RESUME.md` is the approved public resume snapshot, and `AGENTS.md` contains contributor instructions. Keep these at the root because their locations are part of the public profile contract. Private drafts, career planning, certificates, and source photos belong in `../arti1117.private/`; blog posts and learning notes belong in their respective blog repositories. File organization does not approve a new public career statement or synchronize private material.
