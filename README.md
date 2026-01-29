# MartenKPITest

This repository contains a minimal, import-ready project structure to keep files organized when you import code.

Suggested folder structure
- .github/workflows/        CI workflows
- configs/                 configuration files (linters, formatters)
- docs/                    documentation and guides
- src/                     source code (place your language-specific code here)
  - app/                   default app folder
- tests/                   unit and integration tests
- examples/                usage/import examples
- scripts/                 helper scripts and Makefile
- docker/                  Dockerfiles and container assets
- assets/                  images and static files

How to use
1. Add your source code under `src/` (e.g., `src/app/` or a language-specific subfolder).
2. Add tests under `tests/`.
3. Update or add a workflow under `.github/workflows/` for CI.

If you want a language-specific starter (Node/Python/Go), tell me and I can add package files and example code.
