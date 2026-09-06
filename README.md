# Cloisonne Dream

A reusable image-restyling skill that converts a source image into a **modern gold-wire cloisonne enamel illustration** while keeping the original scene, subjects, composition, and spatial relationships faithful.

> **Core principle: change the medium, not the scene.**

## What makes v0.2 distinctive

Cloisonne Dream is not just a material filter. Version 0.2 introduces a fixed visual grammar inspired by strong image-transformation skills:

- **Identity Cells** — recognition-critical areas such as faces, landmark silhouettes, dragon heads, or signature objects. These use restrained line density.
- **Flow Cells** — directional forms such as hair, clothing folds, wings, scales, roads, water, branches, or cloud motion. These use the richest enamel segmentation.
- **Quiet Cells** — sky, walls, distant background, shadow masses, and other calm surfaces. These stay broad and sparse.
- **Gold-Line Continuity** — one or two source-derived gold-line paths visually connect existing forms across the composition without inventing new objects.

The goal is a repeatable visual system: **Identity → Flow → Quiet**, rather than applying the same gold outline everywhere.

## Showcase

<table>
  <tr>
    <td align="center" width="50%">
      <img src="assets/examples/example-01.png" alt="Cloisonne Dream example 01" width="100%"><br>
      <sub><b>Example 01</b> · Character / garden scene</sub>
    </td>
    <td align="center" width="50%">
      <img src="assets/examples/example-02.png" alt="Cloisonne Dream example 02" width="100%"><br>
      <sub><b>Example 02</b> · Dragon / castle scene</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="assets/examples/example-03.png" alt="Cloisonne Dream example 03" width="100%"><br>
      <sub><b>Example 03</b> · Character / dragon scene</sub>
    </td>
    <td align="center" width="50%">
      <img src="assets/examples/example-04.png" alt="Cloisonne Dream example 04" width="100%"><br>
      <sub><b>Example 04</b> · Fantasy architecture scene</sub>
    </td>
  </tr>
</table>

These examples show the material family. Future v0.2 examples should additionally demonstrate the Identity / Flow / Quiet hierarchy and Gold-Line Continuity more explicitly.

## What it is

Cloisonne Dream is designed for image-to-image restyling where photographic or CGI micro-texture is undesirable. It replaces photo-like detail with clean enamel color fields, fine metallic partition lines, controlled glazed highlights, and handcrafted visual structure.

The style is intentionally strict: it should not invent suns, moons, clouds, birds, flowers, stars, buildings, ornaments, or other decorative scene elements unless they already exist in the source image or the user explicitly asks for them.

## Repository structure

```text
cloisonne-dream/
├── .codex-plugin/
│   └── plugin.json
├── assets/
│   └── examples/
│       ├── example-01.png
│       ├── example-02.png
│       ├── example-03.png
│       └── example-04.png
├── skills/
│   └── cloisonne-dream/
│       ├── SKILL.md
│       ├── agents/
│       │   └── openai.yaml
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
- separate the scene into Identity, Flow, and Quiet zones;
- concentrate line richness in directional Flow Cells rather than outlining everything equally;
- create one or two meaningful Gold-Line Continuity paths from existing geometry;
- convert photographic micro-detail into enamel cells and controlled linework;
- remove camera noise, grain, skin pores, and random photo texture;
- avoid unrelated decorative invention;
- remain clearly non-photographic and recognizably part of one consistent visual family.

## Golden rule for additions

**If an object or motif is absent from the source, do not add it merely because it looks appropriate for cloisonne, fantasy, Chinese decorative art, or enamel illustration.**

If the source really contains a sun, moon, bird, cloud, flower, snowflake, or similar element, preserve and restyle it normally.

## Version

Current draft: **0.2.0**

Version 0.2 adds a distinctive structural grammar and regression criteria on top of the original source-fidelity and enamel-material rules.
