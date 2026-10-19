# Built-in features for laserline-os

Purpose: laser cutting design

1. **prepare a creative project** — run laserline-os-workspace. It creates ~/Documents/laserline-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run laserline-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/laserline-os-session-plans/.
3. **check project and export readiness** — run laserline-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/laserline-os-workspace features/laserline-os-plan features/laserline-os-check "$HOME/.local/bin/"
