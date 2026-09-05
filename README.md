# Cloisonne Dream

A reusable image-restyling skill that converts a source image into a **modern gold-wire cloisonne enamel illustration** while keeping the original scene, subjects, composition, and spatial relationships faithful.

> **Core principle: change the medium, not the scene.**

## What it is

Cloisonne Dream is designed for image-to-image restyling where photographic or CGI micro-texture is undesirable. It replaces photo-like detail with clean enamel color fields, fine metallic partition lines, controlled glazed highlights, and handcrafted visual structure.

The style is intentionally strict: it should not invent suns, moons, clouds, birds, flowers, stars, buildings, ornaments, or other decorative scene elements unless they already exist in the source image or the user explicitly asks for them.

## Repository structure

```text
cloisonne-dream/
├── .codex-plugin/
│   └── plugin.json
├── skills/
│   └── cloisonne-dream/
│       ├── SKILL.md
│       └── references/
│           ├── style-rules.md
│           └── eval-cases.md
└── README.md
```

## Use in Codex

For local skill use, copy `skills/cloisonne-dream` into one of Codex's skill locations, for example:

```text
$HOME/.agents/skills/cloisonne-dream
```

Then invoke it explicitly with `$cloisonne-dream`, or choose it from `/skills`.

For distribution, this repository is also packaged as a skill-only plugin through `.codex-plugin/plugin.json`.

## Intended behavior

The skill should:

- preserve subject count, identity-defining features, pose, viewpoint, framing, and scene layout;
- preserve important source colors unless stylization requires small material adjustments;
- convert natural edges into elegant metallic partitions;
- convert photographic micro-detail into enamel cells and controlled linework;
- remove camera noise, grain, skin pores, and random photo texture;
- avoid unrelated decorative invention;
- remain clearly non-photographic and recognizably part of one consistent visual family.

## Golden rule for additions

**If an object or motif is absent from the source, do not add it merely because it looks appropriate for cloisonne, fantasy, Chinese decorative art, or enamel illustration.**

If the source really contains a sun, moon, bird, cloud, flower, snowflake, or similar element, preserve and restyle it normally.

## Version

Current draft: **0.1.0**

The first version is focused on style consistency and source fidelity. Future versions can add curated example assets and stronger evaluation coverage.