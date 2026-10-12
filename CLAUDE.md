# Project CLAUDE.md - chiefmikey

## Project Overview

GitHub profile repository (github.com/chiefmikey) containing profile README, resume PDF, and logo assets.

## Tech Stack

- **Language:** Markdown, HTML
- **Runtime:** Node.js (dev tooling only)
- **Linting:** mikey-pro (ESLint 10 flat config)
- **Formatting:** Prettier via `mikey-pro/prettier`, Stylelint via `mikey-pro/stylelint`

## Architecture

```text
README.md                 # GitHub profile README (HTML table with logo)
README.html               # HTML mirror (GitHub renders README.md only; style/target attrs here are cosmetic)
img/                      # Logo and image assets (mikl-logo.svg, etc.)
mikl-wolfe_software-engineer.pdf  # Resume/CV (kept, intentionally not linked from the READMEs)
eslint.config.js          # Re-exports mikey-pro
```

## Contact

Public contact is `wolfe@mikl.io` (matches resume and package author) and LinkedIn `/in/miklwolfe`. Never use the legacy `miklbarton` address. Keep README.md and README.html content identical.

## Commands

No scripts defined in package.json. This is a static profile repository.

## Conventions

- ESM only (`"type": "module"`)
- ESLint via `mikey-pro` base config
- Conventional commits: `feat:`, `fix:`, `chore:`, etc.

## Testing

No test framework configured. No test scripts defined.
