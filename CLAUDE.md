# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with this repository.

## Purpose

This is the **overview repository** for the TEG-Blue project. It serves as:
- A central entry point for anyone discovering TEG-Blue on GitHub
- A map of how all TEG-Blue repositories connect
- High-level documentation that doesn't belong in a specific site repo

## Repository Structure

```
emotionalblueprint/
├── teg-blue-overview/     # This repo — project overview
├── teg-blue-site-com/     # Application site (teg-blue.com)
├── teg-blue-site-org/     # Research site (teg-blue.org)
└── Papers/                # Research corpus PDFs
```

## Two-Site Architecture

| Site | Purpose | Audience |
|------|---------|----------|
| **teg-blue.com** | Interactive tools & application | Everyday people, practitioners |
| **teg-blue.org** | Open science & research | Researchers, academics |

Both sites link to each other. Same framework, different purposes.

## When to Update This Repo

Update this README when:
- Adding a new repository to the project
- The two-site architecture changes
- Core claims or structure of TEG-Blue changes significantly

For site-specific changes, update the respective site's README and CLAUDE.md instead.

## Related Files

Each site repository has its own detailed CLAUDE.md:
- `teg-blue-site-com/CLAUDE.md` — Application site conventions, components, design system
- `teg-blue-site-org/CLAUDE.md` — Research platform conventions, content structure

The parent Projects folder also has a CLAUDE.md with cross-project commands:
- `Projects/CLAUDE.md` — Quick commands, site comparison, shared conventions
