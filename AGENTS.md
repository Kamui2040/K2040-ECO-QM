# K2040 ECO Quick Menu Repository Instructions

## Purpose

This public repository is the GitHub release home for the released K2040 Fallout 4 ECO Quick Menu projects:

- ECO Quick Menu Additions — AiO installer
- ECO Quick Menu Additions — Single Patches

Keep the two release tracks clearly separated. Do not use this repository for unrelated projects or for the separate in-development Prisma ECO Quick Menu project.

## Public-safe repository

- Everything committed or uploaded here must be safe for public distribution.
- Do not store credentials, signing or recovery material, personal data, device IDs, private URLs or IDs, machine-specific paths, private QA, sensitive logs, backups, or maintainer-only records.
- Do not use this repository as temporary private storage.
- Do not add unexplained binaries, archives, assets, or third-party material.
- Preserve required licence, permission, provenance, and attribution information for every published file.

## Release tracks

- `aio/` documents the AiO installer release track.
- `single-patches/` documents the individual Single Patches release track.
- GitHub release titles, tags, notes, files, and checksums must make the release track unambiguous.
- Keep the official Nexus mapping unchanged unless live project evidence confirms a deliberate move:
  - AiO: `https://www.nexusmods.com/fallout4/mods/105461`
  - Single Patches: `https://www.nexusmods.com/fallout4/mods/105464`

## Release integrity

- Before publishing a GitHub release or file, verify the exact project, track, version, filename, checksum, release notes, licence terms, and attribution.
- When mirroring an already published file, use the exact verified artifact rather than rebuilding or repacking it without a documented reason.
- Stop if the source, version, checksum, permissions, or release notes are uncertain or contradictory.
- Do not publish placeholder, test, debug, or private files as normal releases.
- Creating or changing GitHub Releases, release artifacts, tags, official checksums, or published release notes is an official release action and remains maintainer-controlled.

## Repository work

- Keep `main` stable and use focused branches and pull requests for normal changes.
- GitHub Actions and other cloud CI are disabled and must not be created, queried, triggered, or relied on.
- Use simple, natural public-facing language.
- Keep the K2040 Gaming Mods website as the presentation layer and this repository as the GitHub release home.
- Routine repository maintenance and documentation updates are allowed when they do not change official published release state.

## Validation

Before accepting changes, review the complete changed-file scope and verify relevant links, release-track separation, public-safety, licence/provenance information, and formatting. Run `git diff --check` when local Git validation is available; do not claim it was run when only GitHub-side review was possible.
