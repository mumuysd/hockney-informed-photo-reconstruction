# Place-Space Grammar v0.4

## Inheritance and scope

This relation grammar inherits all eight rules in `01-core-grammar.md`. Its outdoor landscape implementations are supported by H01, H03, H04, H05, H06, H07, H10, H11, H12, H14, H16, H18, and H20. Built spaces are a user-authorized application extension, not new corpus evidence. For every `place_space` source, `GESTURE` is `N/A`; visible direction belongs to ATTENTION, SPACE, SHAPE, EDGE, MARK, or `scene_idea`.

Use `source_relation: place_space` with exactly one implementation:

```yaml
relation_implementation:
  - outdoor_place
  - built_space
  - active_place_or_surface
```

For application to a new source, inherit `identity_core` and `scene_idea` from `00-intent-contract.md`; set `gesture_pose.applicability` to `not_applicable`. Place identity is normally a route, opening, enclosure, repetition, layer, event, active-surface, room-volume, threshold, or architectural-mass relation rather than an inventory of exact objects or modules. Space, proportion, composition, color, and local form may be rewritten while the declared place relation remains legible.

## LG-01 — Classify the landscape subject system

```yaml
branch_decision: "Choose route-and-anchor, framed opening/enclosure, patterned field, boundary obstruction, isolated activity cluster, frontal light event, or kinetic surface-place as the subject system."
dimensions: [ATTENTION, SUBJECT]
evidence: "H01/H04/H05/H16 route; H03/H06/H18 opening or enclosure; H07/H12 patterned field; H10 obstruction; H14 activity cluster; H11 light event; H20 kinetic surface."
selection: "Choose the relation supported by convergence, enclosure, repetition, isolation, density, value, scale, or alignment."
limit: "Do not reduce the scene to the largest tree, building, sun, island, or other named object."
```

The subject system determines later spatial, density, shape, and mark choices. It must be selected before describing vegetation, architecture, weather, or surface texture.

## LG-02 — Select the spatial family from visible source cues

```yaml
branch_decision: "Choose route recession, obstruction depth, repetition recession, sparse stacked layers, interlocking enclosure, frontal stacked event, or layered depth plus flat active surface."
dimensions: [SPACE, SUBJECT, SHAPE]
evidence: "H01/H04/H05/H16 route; H03/H10 obstruction; H07/H12 repetition; H14 sparse layers; H06/H18 enclosure; H11 frontal event; H20 layered plus flat surface."
selection: "Use convergence for routes, overlap for obstruction/enclosure, diminishing units for repetition, stacking for sparse layers/events, and stable containing bands for an active surface."
limit: "No universal flattening amount is supported. Preserve strong recession where it carries the subject, especially H05/H16-type sources."
```

Controlled hybrids are allowed only when both components are visible, as in H20 where geographic layers coexist with a flattened patterned water field.

## LG-03 — Build landscape structure from relational shapes

```yaml
branch_decision: "Reduce land, route, vegetation, water, sky, and event into a small shape relation matched to the subject system."
dimensions: [SHAPE, SUBJECT, SPACE]
evidence: "route-and-anchor H01/H04/H05/H16; framed/interlocking opening H03/H06/H18; repeated units H07/H12; stacked zones H10/H14; centered event H11; active field H20."
selection: "Preserve route continuity, enclosure gap, repeated-scale rhythm, layer order, event alignment, or surface containment before local marks."
limit: "Do not copy exact road curves, cliff silhouettes, bale placement, sun geometry, or water rings from the corpus."
```

Roads may become wedges or ribbons, trees and islands may become anchor masses, hedges and cliffs may become brackets or wedges, fields may become planes, and water may become a contained active field—but only when those roles exist in the source.

## LG-04 — Match information density to the landscape system

```yaml
branch_decision: "Choose route-boundary, framed-opening, repetition-distance, extreme-near-layer, isolated-cluster, event-centered, or active-surface density."
dimensions: [DETAIL_HIERARCHY, ATTENTION, DELETION]
evidence: "H01/H04/H05/H16 route boundary; H03/H06 framed opening; H07/H12 repetition-distance; H10 near layer; H14 isolated cluster; H11/H18 event; H20 active surface."
selection: "Concentrate information where it proves direction, enclosure, scale, layer order, light, or surface activity; keep complementary regions quiet."
limit: "Do not assume foreground-to-background detail decline is universal: H14 isolates a tiny middle cluster and H20 concentrates detail across water."
```

## LG-05 — Encode direction without calling it gesture

```yaml
branch_decision: "Assign landscape movement to spatial convergence, shape direction, boundary rhythm, or mark geometry."
dimensions: [ATTENTION, SPACE, SHAPE, EDGE, MARK]
evidence: "roads H01/H04/H05/H16; framing stems H03/H10/H14; rows and repeated units H07/H12; cliff striation H06/H18; radial light H11; concentric water marks H20."
selection: "Name the carrier and its job: entry into depth, enclosure, mass orientation, repetition, radiance, or kinetic surface."
limit: "GESTURE remains N/A unless a depicted figure is large enough for a separate figure analysis; H20's tiny figures do not change the landscape classification."
```

## LG-06 — Coordinate landscape edges and mark families by region

```yaml
branch_decision: "Use firm boundaries for selected routes, frames, masses, lights, or containing silhouettes; use distinct mark families for material and direction; keep atmosphere softer or open."
dimensions: [EDGE, MARK]
evidence: "route/anchor H01/H04/H05/H16; vegetation frame H03/H10; distance-gradient repetition H07/H12; extreme edge economy H14; plane/light boundaries H06/H11/H18; stable containment around kinetic field H20."
selection: "For every region, specify boundary class, mark geometry, density, and visible job before naming a medium."
limit: "Do not cover distant hills, sky, water, road, and vegetation with one hatch or watercolor texture vocabulary."
```

Typical divisions of labor include quiet route field versus hedge dots, long stem lines versus open sky, curved repeated units versus broad field plane, cliff striation versus quiet water, radial light versus horizontal atmosphere, and kinetic surface rings versus stable land silhouettes.

## LG-07 — Keep open ground structurally active

```yaml
branch_decision: "Preserve low-information road, opening, water, sky, distance, land, or paper where it exposes the selected subject relation."
dimensions: [DETAIL_HIERARCHY, EDGE, DELETION]
evidence: "quiet routes H01/H04/H05/H16; openings H03/H06; atmosphere around repetition H07/H12; open far field H10; extreme blankness H14; reduced topography H11/H18; quiet anchors around active surface H20."
selection: "Name the retained function: direction, passage, enclosure, scale, layer contrast, event clarity, or surface containment."
limit: "Open ground is not decorative blank paper, and finished-image absence does not prove what the artist removed from reality."
```

## LG-08 — Use landscape color to separate roles, not to enforce brightness

```yaml
branch_decision: "Choose restrained land, warm-cool layer zoning, localized accent, muted enclosure, saturated event, or active-surface containment."
dimensions: [COLOR, SHAPE, ATTENTION]
evidence: "H01/H04/H05/H07/H12 restrained land; H03/H10/H16 warm-cool layers; H14 localized cluster; H06/H18 muted enclosure; H11 saturated event; H20 blue-dominant active surface."
selection: "Assign color according to route, plane, enclosure, scale cue, light event, or surface role, using the minimum intensity that keeps those relations legible."
limit: "Do not mandate bright/pastel color and do not claim departure from local color without a source pair; reproductions are uncalibrated."
```

This limit describes the corpus evidence boundary: brightness is not a universal finding from the thirteen works. The user-authorized `structural_luminosity` default in `00-intent-contract.md` and `render-profiles.md` governs runtime output while still requiring regional chroma hierarchy rather than uniform brightness.

## Landscape coverage ledger

| Work | Subject system | Spatial family | Density pattern | Direction carrier |
|---|---|---|---|---|
| H01 | route and anchors | route recession | sparse route/boundary | road taper and grass lines |
| H03 | framed opening | obstruction depth | dense frame/quiet passage | hedge brackets and stem arcs |
| H04 | route and tree anchor | route recession | anchor/boundary | road convergence and canopy marks |
| H05 | bending route and scale cue | route recession | boundary plus distance | road/hedge curve and field stripes |
| H06 | enclosed water opening | interlocking enclosure | dense side masses/quiet opening | cliff striation and inward silhouettes |
| H07 | repeated field use | repetition recession | repetition-distance | diminishing bales and stubble |
| H10 | dense near obstruction | obstruction depth | extreme near layer | projecting stems and band stacking |
| H11 | frontal light event | frontal stacked event | event-centered | radial sun, horizontal cloud, vertical reflection |
| H12 | patterned cultivated field | repetition recession | surface plus distance | converging rows and repeated units |
| H14 | isolated activity cluster | sparse stacked layers | tiny cluster/extreme open ground | stalk lattice and thin layer bands |
| H16 | route through segmented land | route recession | boundary plus land surface | road taper and crop directions |
| H18 | enclosed light path | interlocking enclosure | light/mass/near texture | reflection axis and cliff striation |
| H20 | kinetic surface and place | layered plus flat active surface | surface-field dominant | concentric rings within stable bands |

All thirteen landscape works are represented and all retain `GESTURE: N/A` for landscape analysis.

## User-authorized application extension — `built_space`

Use this implementation when room volume, corridor, threshold, facade mass, interior enclosure, light opening, or circulation relation remains primary after incidental furniture, fixtures, signage, and people are removed.

- Reduce the built place to three to five carriers such as floor/wall wedge, ceiling or sky field, opening, dominant mass, circulation path, or one anchor block.
- Preserve only the perspective, overlap, threshold, repeated bay, or scale cues required for the governing relation. Do not trace every wall edge or window module.
- Merge furniture, fixtures, facade units, tiles, signs, cables, vents, lamps, parked objects, and repeated doors/windows unless one is a declared functional anchor.
- Exact architectural modules, dimensions, text, logos, and product geometry are not locks unless the user explicitly requires them; block if such a lock cannot coexist with reconstruction.
- Keep one primary spatial boundary family, one secondary anchor/contact family, and at most one subordinate material family. Each declares excluded regions.
- Use broad transparent planes for volume and localized pigment events at one opening, threshold, divider, or scale anchor. Reject clean architectural visualization, real-estate rendering, technical drawing, and uniform wall/paper texture.
- This extension remains behaviorally unvalidated; do not infer a quality pass from these rules alone.
