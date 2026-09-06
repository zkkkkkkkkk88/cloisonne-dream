# Cloisonne Dream

A reusable image-restyling skill that converts a source image into a **modern luminous gold-wire cloisonne enamel illustration** while keeping the original scene, subjects, composition, and spatial relationships faithful.

> **Core principle: preserve the scene, redesign the surface, decorate with intent.**

## What makes v0.4 distinctive

Version 0.4 keeps the source-faithful structure of v0.3, but restores a controlled ornamental layer so the result can feel richer, more complete, and more recognizably cloisonne.

- **Identity Cells** — recognition-critical areas such as faces, landmark silhouettes, dragon heads, or signature objects. These stay readable and controlled.
- **Flow Cells** — directional forms such as hair, clothing folds, wings, scales, roads, water, branches, or cloud motion. These carry the richest enamel segmentation.
- **Quiet Cells** — sky, walls, distant background, shadow masses, and other calm surfaces. These stay broader and less dense, while also providing the preferred space for restrained ornament.
- **Gold-Line Continuity** — one or two source-derived gold-line paths visually connect existing forms across the composition.
- **Surface Creativity** — existing dresses, scales, wings, ice, water, architecture, foliage, and other surfaces may be made much more ornate and jewel-like.
- **Luminous Enamel Uplift** — source colors remain recognizable, but the result may become brighter, clearer, and more radiant.
- **Decorative Enamel Motif Layer** — a limited sun/moon disc, stars, cloud bands, snow-crystal motifs, floral emblems, geometric accents, or tiny non-narrative bird silhouettes may be added when they improve the composition.

The repeatable visual system is now:

**Scene Fidelity → Identity / Flow / Quiet → Gold-Line Continuity → Bold Surface Redesign → Controlled Motif Layer → Luminous Enamel Finish**

## Decorative motif rule

Decorative motifs are allowed, but they are not allowed to behave like new narrative subjects.

Good:
- one elegant sun disc in genuine open sky;
- a few crystalline stars in an ice-themed scene;
- a restrained cloud band in unused negative space;
- a small floral or geometric enamel emblem supporting composition.

Bad:
- the same top-left sun in every image;
- several large celestial symbols competing with the subject;
- motifs covering a face, dragon head, prop, or landmark;
- inventing a second dragon, new building, new person, or other major scene object.

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

## Version

Current draft: **0.4.0**

Version 0.4 reintroduces selected decorative cloisonne motifs under explicit control, while retaining the brighter luminous finish, bold surface redesign, and strict protection of the source's main scene structure.
