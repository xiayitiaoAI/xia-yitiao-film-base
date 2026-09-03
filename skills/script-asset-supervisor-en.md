---
name: script-asset-supervisor-en
description: Turn a film or short-drama script into a consistent, trackable image-asset library. Always list and confirm the assets before generating them.
---

# Script Asset Supervisor

Convert a complete script into a practical visual asset library for AI film and short-drama production.

## Required Workflow

Follow this order:

**Read the script -> understand continuity -> extract assets -> merge duplicates -> define state variations -> output an Asset Bible -> wait for user confirmation -> create master references -> wait for confirmation -> generate approved variations.**

The goal is not to create as many images as possible. Use the smallest stable set of character, location, prop, and special-state assets that can cover the production.

## Non-negotiable Rules

1. Do not generate images before fully reading the script.
2. Do not generate images before the user explicitly confirms the Asset Bible.
3. A change in shot size, camera angle, facial expression, or ordinary movement does not automatically require a new asset.
4. Create a state variation only for a sustained or visually important change.
5. Every state variation of a character must inherit the same Character Master.
6. Every state variation of a location must inherit the same Environment Master and preserve its spatial structure.
7. Every state variation of a prop must inherit the same Prop Master.
8. Never redesign an approved asset without permission.
9. Mark contradictions, missing information, and unclear visual decisions as `[NEEDS CONFIRMATION]` instead of deciding silently.
10. Update the Asset Bible whenever an asset is created or changed.
11. Do not create storyboards, shot lists, or final movie shots during the asset phase unless the user asks for them.
12. Inspect the available image-generation tools and local project files before generating. Prefer tools that can pass reference images and preserve identity.

## Asset Bible

For every asset, record:

- Asset ID and name
- Type: character, location, prop, special asset, or state variation
- Script scenes or paragraphs where it appears
- Visual description and continuity anchors
- Required angles, poses, expressions, damage, or clothing states
- Related assets
- Reference-image path after generation
- Status: proposed, confirmed, master, variation, or needs confirmation

## Character Continuity

Track identity, age, body type, hair, face, clothing, accessories, and distinctive marks. If a character is injured, wet, dirty, missing clothing, holding an object, or otherwise visibly changed for later scenes, create a separate state reference.

## Location Continuity

Track layout, entrances, windows, furniture, lighting direction, time of day, weather, color palette, and recurring background objects. Different lighting states may be variations, but the underlying space must remain recognizable.

## Prop Continuity

Track shape, material, color, size, markings, damage, and who is holding or using the prop. Create variations for meaningful changes such as broken, opened, stained, or partially consumed props.

## Generation Phase

After confirmation, generate the approved assets one by one or in a controlled batch. Keep character identity, clothing, hairstyle, age, location structure, lighting logic, and prop appearance consistent. Label every output with its Asset ID and name.

When the user provides a script, start with the Asset Bible only. Stop and wait for confirmation before generating images.
