# Evaluation Cases

Use these cases as visual regression checks after any skill change.

## Global v0.2 pass criteria

Every output must satisfy all of the following:

- source subject count, pose, viewpoint, major silhouette, object placement, and scene identity remain traceable;
- no unrelated decorative object is invented;
- the image is visibly non-photographic and reads as cloisonne enamel rather than stained glass or a gold-outline filter;
- the composition contains all three structural zones when the source permits them: **Identity Cells**, **Flow Cells**, and **Quiet Cells**;
- line density is intentionally uneven: identity regions are readable, flow regions are richest, quiet regions are sparse;
- at least one meaningful **Gold-Line Continuity** path links existing source forms without inventing a new object;
- source-derived colors remain recognizable;
- micro-detail is compressed into enamel structure rather than reproduced as noise.

## Known baseline failures

These failures motivated v0.2 and must not return:

- adding a decorative sun or golden disc where the source had none;
- treating every object with the same dense gold outline;
- making the result look like generic stained glass;
- applying a generic blue-white-gold palette to unrelated sources;
- changing only the material while leaving no distinctive Cloisonne Dream composition or line rhythm;
- using random filigree instead of lines that follow source geometry and motion.

## Case 1: Anime character in a garden

Source characteristics:
- single seated character;
- parasol;
- dense green garden;
- wooden railing;
- white/lavender clothing.

Pass criteria:
- face and parasol are **Identity Cells** with restrained line density;
- hair and clothing folds become **Flow Cells** with directional segmentation;
- distant foliage and empty background become **Quiet Cells**;
- one or two gold-line paths may continue from hair/clothing into existing railing or foliage contours;
- no invented sun, moon, birds, stars, lanterns, or cloud motifs.

## Case 2: White dragon over fantasy architecture

Source characteristics:
- one large white dragon;
- pale castle/city below;
- blue daytime sky;
- pink-tinted wing membranes.

Pass criteria:
- dragon head, wing silhouette, and city mass remain immediately traceable;
- dragon scales and wing membranes form high-density **Flow Cells**;
- sky remains a low-density **Quiet Cell** field;
- gold continuity follows existing spine, wing, or architectural directions rather than decorative curls;
- no new celestial symbol or decorative sun disc.

## Case 3: Ice queen with dragon

Source characteristics:
- standing woman in icy dress;
- staff;
- large dark icy dragon behind her;
- dark blue environment.

Pass criteria:
- face, staff head, and dragon head remain **Identity Cells**;
- dress, hair, dragon scales, and icy structures carry the richest **Flow Cell** segmentation;
- dark background remains sparse and calm;
- palette stays predominantly cool and dark;
- no forced bright-gold background, moon, stars, snowflake symbols, or birds unless present in source.

## Case 4: Woman on cloud bridge toward bright castle

Source characteristics:
- woman seen in profile/back-three-quarter view;
- long pale dress and veil;
- winding elevated bridge;
- pale castle in distance;
- clouds dominate environment;
- bright sunlight already exists in source.

Pass criteria:
- bridge path, woman placement, castle, clouds, and existing bright light remain recognizable;
- dress/veil and bridge path become directional **Flow Cells**;
- distant cloud fields remain comparatively quiet;
- existing sunlight may be restyled because it is actually present;
- no second sun, moon, birds, emblems, or decorative cloud motifs.

## Failure trigger

If the output passes the material test but fails the structural grammar test, it is not a Cloisonne Dream v0.2 result. Regenerate with stronger Identity / Flow / Quiet zoning and Gold-Line Continuity.