# Continuity Studio — Council Edition

A shared workspace for maintaining reusable character, scene, place, comparison, and production-pass references across Digital Utopia Serenity.

## Start here

1. Open the [Council continuity folder](https://github.com/Digital-Utopia-Serenity/DigitalUtopia/tree/main/continuity).
2. Read this guide, then download `workspace.json` and import it into the app before editing.
3. Browse the Reference library. Update the existing concept when it matches; add a new entry only when it is genuinely distinct.
4. Keep unsettled details **Tentative**. Set conflicting details to **Needs review** instead of silently changing canon.
5. Compare image or prompt versions. Link each comparison to its character or scene, then record the decision in Production log.
6. Export the workspace JSON, inspect the diff, and submit the update as a GitHub pull request or commit.
7. Import the accepted JSON before the next pass so the Council starts from the same version.

## Sharing and privacy

This repository is public. Anything committed here, including workspace JSON updates and attached reference images, is visible to anyone. The private owner workspace is separate and contains its own browser-local references. Do not export private canon or personal reference material into this public Council copy unless it is intended for public release.

## Continuity rules

- Reuse the existing concept before adding another card for the same character, scene, or place.
- Preserve approved face, hair, scale, set layout, prop placement, and story position across a sequence.
- Keep experiments and unpinned details tentative.
- Log drift and unresolved conflicts for review.
- Store decisions once and link back to them; avoid duplicate prompt concepts.

## Workspace behavior

The app stores edits in the current browser. Changes become shared only after the exported `workspace.json` is committed. Image comparisons are embedded in browser-local data and may make JSON exports large.
