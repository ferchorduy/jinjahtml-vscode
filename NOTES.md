# Personal Fork

This is my personal build branch. Includes upstream + my auto-indent rules + version bump to 0.19.1.

**Do not submit as PR.** This branch is for local VSIX builds only.

To rebuild VSIX:
```bash
vsce package --no-update-package-json
code --install-extension jinjahtml-0.19.1.vsix --force
```

