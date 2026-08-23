# Release model

This repository contains two current public release tracks: the **AiO installer** and the **Single Patches** collection.

## Current release line

- AiO: Nexus mod 105461, current version 1.0.1.11.
- Single Patches: Nexus mod 105464, current version 1.0 with 12 current optional patch files.

The older Nexus project 104590 is a replaced predecessor. Its files are legacy material and must not be mixed into a current release without explicit verification that the same patch was carried forward.

## Before publishing

For every GitHub release, verify the exact release track, version or release identifier, filename, checksum, source artifact, release notes, licence terms, permissions, and required attribution. If any of these do not match the intended public release, stop rather than publishing a best guess.

When mirroring an already published K2040 archive, keep the archive contents byte-for-byte unchanged. A clearer outer filename may be used for GitHub as long as the archive itself is not rebuilt or repacked.

Keep the original local backup untouched. Create renamed staging copies for GitHub publication and generate public checksum files from those final asset names.

## File naming

Use readable release-asset names that identify the project, target weapon or variant, and version where applicable. Avoid Nexus-added download suffixes and avoid exposing local filesystem paths.

Recommended patterns:

- AiO: `K2040_ECO_QuickMenu_AiO_v<version>.7z`
- Single patch: `K2040_ECO_QM_<weapon-or-variant>_v1.0.7z`
- Checksums: `SHA256SUMS.txt`

## Release notes

Each GitHub release should clearly state:

- whether it is **AiO installer**, **Single Patches**, or a clearly labelled historical/legacy release;
- the release version or identifier;
- what changed;
- the corresponding Nexus Mods page;
- the checksum for each K2040-published downloadable file when a checksum is provided;
- any dependency, permission, licence, or attribution information that needs to accompany the release.

## Official Nexus pages

- AiO installer: <https://www.nexusmods.com/fallout4/mods/105461>
- Single Patches: <https://www.nexusmods.com/fallout4/mods/105464>

Creating or changing a public GitHub release, tag, release artifact, official checksum, or published release note changes official release state and requires maintainer approval.
