# Built-in features for threadform-os

Purpose: fashion design

1. **prepare a creative project** — run threadform-os-workspace. It creates ~/Documents/threadform-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run threadform-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/threadform-os-session-plans/.
3. **check project and export readiness** — run threadform-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/threadform-os-workspace features/threadform-os-plan features/threadform-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for fashion design:

1. **Krita** — org.kde.krita
2. **Kdenlive** — org.kde.kdenlive
3. **Blender** — org.blender.Blender

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
