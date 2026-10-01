# CLAUDE.md

Guidance for Claude working in this repo.

## What this repo is

Open-access research on AI in construction leadership (the GCLM / AI-GCLM
framework line). `README.md` lists the published papers with venues and
DOIs. `papers/` holds PDFs, and `CITATION.cff` gives citation metadata.

## Current state (2026-10-01)

- Files: `README.md`, `CITATION.cff`, `LICENSE`, `SECURITY.md`,
  `papers/ai-gclm-framework-2025.pdf`, plus a second PDF at the repo root
  with a non-standard name (`5.AI-GCLM-MAY2025-75 2.pdf`). Its relationship
  to the file in `papers/` isn't documented.
- `.github/dependabot.yml` (github-actions only) and
  `.github/workflows/codeql.yml` (scans the workflows; there is no code).
- Open PRs: none. Open issues: none.

## Rules

- **Never invent or alter bibliographic facts.** That covers titles,
  venues, volume/issue/pages, years and DOIs. Only use details the author
  provides or that resolve via doi.org.
- Keep `README.md`, `CITATION.cff` and the profile README consistent when a
  paper is added.
- Don't replace or rewrite published PDFs. Add new versions alongside.
- Open a PR for every change; never push to `main`.

## Next steps

- Ask the owner whether the root-level PDF duplicates
  `papers/ai-gclm-framework-2025.pdf` before moving or renaming it.
