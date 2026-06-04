# AGENTS.md

## Overview

This is a public template repo for a generic daily work log skill. It must remain safe to view from a work computer and must not contain private employer, customer, or personal details.

## Validate

- List files: `rg --files`
- Check unfinished markers: `rg -n "[T]ODO:|[T]BD:|[待]补"`
- Review git status before finishing: `git status --short`

## Project Structure

- `README.md`: public entry point.
- `skill/daily-work-log/SKILL.md`: reusable agent skill.
- `templates/daily-work-log.md`: daily log template.
- `templates/weekly-summary.md`: weekly summary template.
- `templates/brag-doc.md`: brag doc template.
- `examples/sanitized-daily-work-log.md`: safe generic example.

## Working Rules

- Keep all content generic and public-safe.
- Do not add real employer names, internal project names, customer details, restricted links, unreleased details, metrics, credentials, or personal sensitive information.
- Prefer sanitized examples over real examples.
- If adding workflow guidance, keep it short and directly usable.

## Definition of Done

- New files are linked from `README.md` when relevant.
- No explicit unfinished markers remain unless intentionally left for users.
- Public-safety check is complete before pushing.
