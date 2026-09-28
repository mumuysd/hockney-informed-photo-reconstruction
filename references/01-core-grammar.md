# Core Grammar v0.2

## Status and evidence boundary

This file promotes recurring decisions from the corrected 20-work, ten-dimension corpus into formal Core Grammar. Promotion here means stable recurrence inside the supplied corpus; it does not yet claim uniqueness against ordinary watercolor or prove how a photograph was transformed.

When this corpus grammar is applied to a new photograph, `00-intent-contract.md` supplies the user-authored preservation and transformation boundary. The three-part preservation core is not corpus evidence and must not be presented as such. Core Grammar may reorganize the five permitted rewrite domains, but it may not silently weaken `identity_core`, applicable `gesture_pose`, `scene_idea`, or an explicit user lock. Exact photographic framing, perspective, placement, proportion, and local color are not preservation defaults.

The source project retains the underlying research analyses. They are omitted from this self-contained runtime package.

`core-grammar-v0.1.md` and rejected generation operators are excluded from positive evidence. Portraits are H02, H08, H09, H13, H15, H17, H19; landscapes are H01, H03–H07, H10–H12, H14, H16, H18, H20.

## Promotion rule

A rule belongs here when it recurs in both portrait and landscape works, describes a decision rather than an object, survives materially different implementations, and can be applied without copying a reference motif. Branch-only decisions belong in `05-portrait-grammar.md` or `06-landscape-grammar.md`.

## CG-01 — Construct the subject as a visual relation

```yaml
rule: CG-01
decision: Name the relation that makes the subject dominant before naming or rendering its component objects.
dimensions: [ATTENTION, SUBJECT]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "single sitter as face/pose/viewpoint; paired sitters as posture and value contrast; reflected head plus viewing apparatus"
landscape_evidence: "route-and-anchor; opening/enclosure; repeated field; boundary obstruction; isolated activity; light event; active surface"
implementation_types: [single-figure relation, paired relation, route-and-anchor, framed opening, repeated surface, obstruction, isolated cluster, light event, kinetic surface]
counterexamples_or_limits: "No single focal-object formula is universal; H14 is dominated by a tiny isolated cluster and H20 by a broad surface field."
application_boundary: "Describe the subject unit visible in the source; do not import a reference object or infer artist intention."
```

## CG-02 — Allocate information unevenly

```yaml
rule: CG-02
decision: Divide the image into high-, medium-, and low-information regions and state why each density level is needed.
dimensions: [ATTENTION, DETAIL_HIERARCHY, DELETION]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "faces, hands, pose junctions, shoes, chair mechanics, or viewing apparatus concentrate information while walls and broad garments remain quiet"
landscape_evidence: "density may concentrate at a route boundary, enclosing hedge, near verge, repeated field, tiny activity cluster, light event, or active water surface"
implementation_types: [identity, paired-support, action-viewpoint, route-boundary, framed-opening, repetition-distance, near-layer, isolated-cluster, event-centered, surface-field]
counterexamples_or_limits: "Detail does not always peak at the named focal object: H14 uses extreme isolation and H20 gives the active surface the highest density."
application_boundary: "Do not equate low information with blur, empty decoration, or damage to source-defining structure."
```

## CG-03 — Establish a dominant shape relationship before local description

```yaml
rule: CG-03
decision: Reduce the scene to three to five dominant shapes and name how those shapes relate before adding local description.
dimensions: [SUBJECT, SHAPE, SPACE]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "nested or interlocking body masses, paired body contrast, and stacked mirror/apparatus zones"
landscape_evidence: "route-and-anchor, framed opening, repeated units, stacked zones, interlocking enclosure, centered event, and active field contained by stable bands"
implementation_types: [nested, paired, interlocking, stacked, framed, repeated, route-and-anchor, active-field-contained-by-bands]
counterexamples_or_limits: "Large-shape simplification without a relationship type is too vague to guide reconstruction."
application_boundary: "Preserve the source's semantic roles and any user-locked compositional function, but allow composition, proportion, and geometry to be reconstructed under 00; do not copy the exact geometry of a reference work."
```

## CG-04 — Assign different boundary roles

```yaml
rule: CG-04
decision: Assign firm, broken, soft, lost/open, atmospheric, internal-construction, and explicit-mark edges according to visual function.
dimensions: [ATTENTION, EDGE, SPACE]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "identity, gesture junctions, support geometry, and one structural divider receive different edge classes from garments and room fields"
landscape_evidence: "routes, hedges, cliffs, islands, light boundaries, atmosphere, and kinetic surface marks receive distinct boundary treatment"
implementation_types: [identity-support selective, asymmetric lost pale edge, structural divider, route-versus-atmosphere, frame-versus-opening, distance-gradient, extreme economy, plane-light, stable-silhouette-around-active-field]
counterexamples_or_limits: "The selected firm edge is not fixed: it may be a face, chair joint, road, hedge, cliff, divider, reflection, or water ring."
application_boundary: "Do not apply one contour strength globally or soften every secondary region indiscriminately."
```

## CG-05 — Give mark families distinct visible jobs

```yaml
rule: CG-05
decision: Use visibly different mark geometries and densities for identity, mass, support, direction, repetition, atmosphere, or surface activity.
dimensions: [DETAIL_HIERARCHY, MARK, SHAPE]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "fine identity lines, broader body fields, chair or fixture structure, clothing direction, and floor orientation remain distinguishable"
landscape_evidence: "route fields, foliage strokes, field repetition, cliff striation, radial light, and kinetic water marks divide labor"
implementation_types: [identity-line-plus-field, sparse-route-anchor, framing-vegetation, repeated-volume-surface, isolated-cluster, directional-geology-light, radial-event, kinetic-surface]
counterexamples_or_limits: "No single universal brush vocabulary or exact tool attribution is supported by the reproductions."
application_boundary: "Specify visible geometry and job before medium or tool; avoid a uniform hatch, dot, wash, or texture overlay."
```

## CG-06 — Preserve active low-information regions

```yaml
rule: CG-06
decision: Leave selected regions broad, incomplete, open, or absent while preserving the structural function that keeps the scene legible.
dimensions: [DETAIL_HIERARCHY, EDGE, DELETION]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "quiet walls, broad garments, incomplete chairs, open room fields, or omitted body regions expose identity, posture, and viewpoint"
landscape_evidence: "quiet roads, openings, water, sky, distant planes, or open paper expose routes, enclosures, events, and dense fields"
implementation_types: [reduced-room, reduced-route-distance, reduced-opening, reduced-atmosphere, extreme-open-ground, reduced-topography, reduced-anatomy-around-active-surface]
counterexamples_or_limits: "The corpus shows finished-image absence only; it does not reveal what existed in reality or what was deliberately deleted from a source photograph."
application_boundary: "Name the retained function of every low-information region; do not erase identity, route continuity, layer order, or scale evidence."
```

## CG-07 — Organize color as an internal role system

```yaml
rule: CG-07
decision: Assign hue, value, saturation, and accent relationships to separate bodies, planes, routes, enclosures, events, and active surfaces.
dimensions: [ATTENTION, SHAPE, COLOR]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "muted body differentiation, strong figure-ground zoning, localized scarf or brace accents, and near-monochrome line/value organization"
landscape_evidence: "restrained land palettes, warm-cool layer zoning, localized color clusters, muted enclosures, saturated light events, and blue-dominant active surfaces"
implementation_types: [muted-value-differentiation, figure-ground-zoning, near-monochrome, restrained-land, warm-cool-layers, localized-cluster, muted-enclosure, saturated-event, active-surface]
counterexamples_or_limits: "High saturation is not universal; H15 is near-monochrome while H11 is a high-saturation extreme. Reproduction color is uncalibrated."
application_boundary: "The rule concerns relationships inside the finished image. Source-color fidelity is unknown without paired evidence."
```

## CG-08 — Select a coherent spatial system instead of applying one flattening rule

```yaml
rule: CG-08
decision: Identify the spatial cues carrying the subject and organize the image around one coherent system or an explicitly controlled hybrid.
dimensions: [SUBJECT, SPACE, SHAPE]
supporting_works: [H01, H02, H03, H04, H05, H06, H07, H08, H09, H10, H11, H12, H13, H14, H15, H16, H17, H18, H19, H20]
portrait_evidence: "shallow shared stages, minimally developed frontal fields, and compressed encounter or mirror viewpoints"
landscape_evidence: "route recession, obstruction depth, repetition recession, sparse stacked layers, interlocking enclosure, frontal light event, and layered depth with an active flat surface"
implementation_types: [shallow-stage, compressed-encounter, route-recession, obstruction-depth, repetition-recession, sparse-layers, interlocking-enclosure, frontal-event, layered-plus-flat-active-surface]
counterexamples_or_limits: "The corpus rejects a universal amount or kind of spatial compression; H05/H16 retain strong recession while H11 is frontal and H20 combines depth with surface flatness."
application_boundary: "Do not claim that the space was changed from a photograph without a source pair; do not flatten merely to signal style."
```

## Core exclusions

The following are deliberately not Core Grammar: figure gesture, roads, hay bales, sheet seams, radial suns, fjords, water rings, a bright palette, a fixed flattening amount, or any particular pose, chair, garment, plant, building, and color. Their reusable functions appear in branch rules or variables; their exact appearances remain residue.
