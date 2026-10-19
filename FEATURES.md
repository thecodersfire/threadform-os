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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for fashion design:

1. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
2. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
3. **Ardour** — record and mix multitrack audio (org.ardour.Ardour)
4. **darktable** — develop RAW photos (org.darktable.Darktable)
5. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
6. **VLC** — review media files (org.videolan.VLC)
7. **Mixxx** — prepare and mix DJ sets (org.mixxx.Mixxx)
8. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
2. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
3. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
4. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
5. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
6. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
11. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
12. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
13. **FreeCAD** (org.freecadweb.FreeCAD) — design mechanical parts.
14. **OpenSCAD** (org.openscad.OpenSCAD) — model parametric 3D parts in code.
15. **KiCad** (org.kicad.KiCad) — design circuits and PCBs.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
