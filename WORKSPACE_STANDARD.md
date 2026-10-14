# Niceone Workspace Standard

This repository is part of the unified Niceone workspace, alongside OIS core and Universal Social Intelligence.

- Keep repository boundaries and release histories separate.
- Open repositories together in a local multi-root VS Code workspace; do not move them into a monorepo without a separate architecture decision.
- Python repositories use CPython 3.15.0 as the proposed developer target, with a separate virtual environment per repository.
- Standardize Python interpreter provisioning with pinned `uv`; retain compatibility CI and require a green Python 3.15 gate before production promotion.
- Share formatting, lint, test, security, and dependency-locking policies, but do not force identical application dependencies into every repository.
- This repository had no Python package manifest at the audited revision, so no Python runtime was changed here.

Canonical policy: https://github.com/niceoneobsidian/niceone-obsidian/blob/main/docs/engineering/UNIFIED_WORKSPACE_STANDARD.md
