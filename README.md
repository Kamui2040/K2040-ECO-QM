# K2040 ECO Quick Menu Additions

Compatibility patches for Fallout 4 weapons that add support for the weapon-specific Quick Menu from **Equipment and Crafting Overhaul (ECO) - Redux**.

This repository is the official K2040 GitHub release home for the current ECO Quick Menu Additions projects:

- **AiO installer** — one FOMOD installer with plugin detection.
- **Single Patches** — install only the patches needed for your load order.

The K2040 Gaming Mods website remains the project and presentation layer. Nexus Mods remains an official distribution source.

## Current release

### AiO installer — 1.0.1.11

The current AiO includes support for:

- HK USP
- DKS-501 Sniper Rifle
- Alex's .357 Cattleman Revolver
- Modern Warfare 2019 FAL
- ACR-W17
- DKS-501 Redux
- AQUILA Laser Rifle
- X12 Plasmacaster
- H&K 45C Mk24
- AER15 Modern Laser Assault Rifle, including the MEC-R7 variant

The installer detects supported plugins and presents the matching patch choices.

### Single Patches — 1.0

The current Nexus Single Patches page contains 12 separately downloadable patches covering the same current project line. They are documented in [`single-patches/`](single-patches/).

## Requirements

You need **ECO Redux and its requirements**, plus the weapon mod and any dependencies required by the patch you install. Some weapons also use optional compatibility files such as Munitions, Alex's Attach Points and Keywords, or weapon-specific update patches.

Use the Nexus pages below for the authoritative dependency links for each supported weapon.

## Installation

For the **AiO**, install the required weapon mods and dependencies first, then install the FOMOD and select or allow detection of the patches that match your load order.

For **Single Patches**, install the requirements first, then install only the patch archives for the weapons you use.

All current K2040 patches are ESL-flagged ESP plugins.

## Compatibility notes

Quick Menu options depend on the attachments currently fitted to a weapon. A menu action may not be valid when the matching attachment is not installed. Conditions are used where possible to prevent invalid choices.

Some weapon mods can also remove or replace attached parts when switching between certain attachment combinations. This behaviour comes from how those weapon attachments are set up rather than from the Quick Menu itself.

A short in-game notification confirms when the Quick Menu has been injected successfully.

## Releases and file integrity

GitHub release assets are mirrors of verified K2040 release archives. The archive contents are not repacked for GitHub. Public filenames may be made clearer for identification, while SHA-256 checksums are provided for the actual archive contents.

Current release files and historical/legacy files are kept separate. The older `K2040's Eco Quick Menu Additions` Nexus project (mod 104590) was replaced by the current AiO and Single Patches projects and is not treated as the current release line.

See [`CHANGELOG.md`](CHANGELOG.md) for release history and [`RELEASES.md`](RELEASES.md) for the release model.

## Credits

Thanks to **DankRafft** for ECO Redux, the Quick Menu tooling and help with the system, and to **Systembreakdown** whose ECO Redux Armory work was a useful reference. Thanks also to the authors of the supported weapon mods and compatibility resources.

## Official links

- AiO — Nexus Mods: <https://www.nexusmods.com/fallout4/mods/105461>
- Single Patches — Nexus Mods: <https://www.nexusmods.com/fallout4/mods/105464>
- K2040 Gaming Mods project page: <https://kamui2040.github.io/K2040-Gaming-Mods/projects/project.html?project=eco-quick-menu-additions>
- GitHub Releases: <https://github.com/Kamui2040/K2040-ECO-QM/releases>

## Scope

This repository is only for the released K2040 ECO Quick Menu Additions work. It does not contain the separate in-development Prisma ECO Quick Menu project or unrelated K2040 projects.
