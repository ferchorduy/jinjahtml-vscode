# Personal Fork

This is my personal build branch. Includes upstream + my fixes, used for local installs only.

**Do not submit as PR.** PRs go through dedicated feature branches off `main`.

## Changes included

- **0.19.1** — Added `onEnterRules` for HTML tag and Jinja block auto-indent
- **0.19.2** — Fixed snippet tabstops (`$0` instead of trailing numbered tabstop)

## To rebuild VSIX

\`\`\`bash
vsce package --no-update-package-json
code --install-extension jinjahtml-<version>.vsix --force
\`\`\`