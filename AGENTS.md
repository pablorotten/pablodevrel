# AGENTS.md

Context for AI agents working in this repo.

## What this repo is

The public CV website for Pablo (source of truth for the site), deployed on
GitHub Pages and live at https://pablodevrel.com. Job-search and personal
material live in a separate private repo (`cv`), not here.

## Critical rules

- **Never commit.** The user reviews and commits manually.
- `CNAME` pins the custom domain (pablodevrel.com); DNS zone file is in `BIND/`.
  Do not change these without asking.
- Markdown resumes (`dev/resume-dev.md`, `devrel/resume-devrel.md`) are the
  editable sources; `index.html` and PDFs are rendered artifacts. Update the
  Markdown first, then regenerate artifacts; ask before regenerating.

## Writing style

For content written here (resume sections, site copy, README, any prose), read
and apply https://claudisms.ai/ first (a living banlist of AI-writing tics:
banned phrases like "delve", "it's worth noting", cleft constructions, "not
just X but Y", em dashes, emoji bullets, etc.). Download the MD version and
check drafts against it before showing them.
