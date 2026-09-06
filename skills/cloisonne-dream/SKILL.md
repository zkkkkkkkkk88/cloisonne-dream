---
name: cloisonne-dream
description: Use when an uploaded image should be transformed into a consistent non-photographic cloisonne enamel artwork while preserving the source scene, subjects, pose, viewpoint, composition, and object relationships.
---

# Cloisonne Dream

## Delivery

- Use the source image only as reference for subject identity, count, pose, silhouette, structure, viewpoint, spatial relationships, and source color.
- Stylize the entire final canvas. Do not show the original photo, do not create a before/after split unless the user explicitly asks for one.
- Process multiple uploaded images separately unless the user explicitly requests a collage.
- Before generation, lock all defining source facts: subject count, pose, direction, major proportions, architecture or terrain structure, occlusions, left/right relationships, and viewpoint.
- Do not invent a location, date, attribution, symbol, landmark, character, creature, or decorative scene element.

## Fixed visual specification

Reconstruct the source as a **modern gold-wire cloisonne enamel artwork** using a fixed three-zone grammar:

### 1. Identity Cells

Use these for the parts that make the source immediately recognizable: faces, heads, hands when important, signature costume elements, dragon heads, vehicle silhouettes, gates, rooflines, landmark contours, or other defining anchors.

- Keep shapes clear and faithful.
- Use low-to-medium partition density: roughly **35%–50%** of the maximum line density in the image.
- Do not over-segment faces or other recognition-critical areas.
- Preserve important source colors and distinguishing features.

### 2. Flow Cells

Use these for directional or rhythmic forms already present in the source: hair, clothing folds, wings, scales, water, clouds, roads, branches, foliage movement, smoke, ribbons, or long architectural axes.

- This is the richest zone, with roughly **60%–80%** of maximum line density.
- Segment forms into elongated or curved enamel cells that follow the source's actual direction, anatomy, perspective, and motion.
- The linework should feel designed, not mechanically traced.
- Flow Cells create the signature energy of Cloisonne Dream.

### 3. Quiet Cells

Use these for visually calm areas: sky, walls, distant background, broad terrain, empty negative space, soft cloud fields, shadow masses, or low-information surfaces.

- Keep line density sparse, roughly **10%–25%** of maximum.
- Use larger enamel fields and fewer partitions.
- Quiet Cells must create breathing room and prevent the image from becoming ornamental clutter.

The final image should visibly balance **Identity → Flow → Quiet** rather than treating every object with the same outline density.

## Gold-Line Continuity

Create one or two meaningful gold-line paths that visually continue across existing source forms.

Examples:
- hair curve → clothing fold → railing direction;
- dragon spine → wing edge → roofline;
- road direction → water edge → distant architecture;
- veil curve → bridge path → cloud contour.

Rules:
- continuity must follow geometry, motion, perspective, or contour already present in the source;
- it may pass from one source object into another only as a compositional continuation;
- it must never invent a new object, symbol, sun, cloud motif, flower, ornament, creature, or decorative flourish;
- continuity is structural, not random filigree.

## Material language

Translate the scene into enamel rather than placing gold outlines on top of a photo.

Use:
- fine warm-gold or warm-brass partition lines;
- polished opaque and translucent enamel color cells;
- subtle raised cell depth;
- restrained glaze highlights;
- clean handcrafted edges;
- simplified tonal structure;
- source-derived color relationships.

Do not retain photographic micro-texture.

Convert:
- hair strands → flowing enamel ribbons;
- scales → repeated enamel cells;
- leaves → grouped enamel masses;
- stone or architecture → larger geometric panels;
- water → layered translucent enamel bands;
- skin → smooth illustrated enamel-toned rendering without pores;
- clouds already present → broad layered enamel fields.

## Color rules

Build the palette from the current source image.

- Preserve its 1–3 most identity-defining colors.
- Preserve overall warm/cool relationships and value hierarchy.
- Gold is primarily structural partition material, not a global color cast.
- Never force unrelated sources into a generic blue-white-gold palette.
- Avoid muddy gray, neon saturation, candy color, or blanket yellow-gold filtering unless genuinely source-derived.

## Content fidelity and forbidden invention

Source content has priority over decoration.

Unless already present in the source or explicitly requested, do not add:
- sun or golden sun disc;
- moon;
- stars or celestial symbols;
- birds;
- clouds or stylized auspicious cloud motifs;
- flowers;
- mountains;
- lanterns;
- gemstones;
- snowflakes;
- extra vegetation;
- extra buildings;
- extra characters or creatures;
- ornamental emblems that change the scene meaning.

If one of these genuinely exists in the source, preserve and restyle it normally.

## Composition rules

Preserve the source's defining spatial logic.

Do not:
- move the main subject unnecessarily;
- change camera angle;
- reverse left/right placement;
- crop important subjects;
- rearrange buildings;
- alter a defining pose;
- replace the background identity;
- introduce a new focal point.

Minor simplification is allowed only to improve enamel readability.

## Quality boundaries

The result must feel like a coherent contemporary cloisonne artwork with a distinctive visual system, not merely a cloisonne material filter.

It should be recognizable by all of these together:
- source-faithful scene structure;
- Identity / Flow / Quiet zoning;
- intentionally uneven line density;
- one or two Gold-Line Continuity paths;
- source-aware enamel palette;
- clean non-photographic rendering.

Avoid:
- stained-glass appearance;
- generic fantasy concept art;
- random gold filigree;
- equal outline density everywhere;
- photographic noise, grain, pores, lens blur, flare, or chromatic aberration;
- oil painting, watercolor, ordinary anime rendering, flat vector art, or plastic CGI.

## Execution checklist

Before generation, verify:
1. What are the source's main Identity Cells?
2. Which existing forms should become Flow Cells?
3. Which regions should remain Quiet Cells?
4. Which one or two source-derived directions can support Gold-Line Continuity?
5. Which colors are identity-defining and must be preserved?
6. Which tempting decorative additions must be explicitly avoided?

After generation, reject and regenerate if:
- a new decorative object appears;
- the source pose, viewpoint, count, or structure changed materially;
- the output looks like stained glass or a gold-outline filter;
- every region has similar line density;
- no readable Identity / Flow / Quiet hierarchy exists;
- Gold-Line Continuity became random ornament instead of source-driven structure.

## References

Read these when stricter guardrails or regression criteria are needed:
- `references/style-rules.md`
- `references/eval-cases.md`
