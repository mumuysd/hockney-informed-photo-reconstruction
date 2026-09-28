# Variables v0.4

## Status

Variables describe stable alternatives observed inside the corpus. They are categorical decisions selected from source structure and branch grammar, not random sliders and not a single style-strength control. Evidence concerns finished artworks; source-relative transformation remains unproven.

For runtime application, `00-intent-contract.md` defines what must survive and which domains may be rewritten. These variables classify source-supported alternatives after the three-part core has been extracted in `07`; they are analytical inputs, not the executable recipe. `render-profiles.md` narrows them through one relation target, and `08-interpretation-profile.md` converts the result into the mandatory pixel-facing `render_recipe`. Variable names and option lists never reach Imagegen.

The portrait/landscape values below remain corpus-grounded. `object_event` may reuse only the abstract decision axes—attention, relation, shape, space, density, color role, edge role, mark density, and open ground—and must name its source-specific choice in plain language. Object-specific alternatives are user-authorized application behavior, not corpus findings.

## V-01 — `attention_system`

```yaml
values: [face_identity, paired_alternation, living_action, route_plus_anchor, framed_opening, repeated_surface_or_path, obstruction_or_isolated_cluster, frontal_light_event, object_identity, arranged_relation, object_use_or_complex_event]
source_selection_cues: "Choose the unit that wins through at least two visible cues among contrast, scale, isolation, convergence, repetition, edge specificity, and placement."
compatible_grammar: [CG-01, CG-02, living_identity, place_space, object_event]
incompatible_uses: "Do not default to the largest named object or add a second attention system unsupported by the source."
evidence_examples: "H08/H09/H15/H17 face; H02/H13/H19 pair; H01/H04/H05/H16 route; H03/H06/H18 opening; H07/H12/H20 repeated surface; H10/H14 obstruction or cluster; H11 light event."
```

## V-02 — `subject_unit`

```yaml
values: [single_living_relation, grouped_living_relation, route_place_system, enclosure, patterned_field, boundary_obstruction, activity_cluster, atmospheric_event, kinetic_surface_place, single_object_relation, arranged_objects_relation, object_use_or_vehicle_relation, complex_visible_event]
source_selection_cues: "Name the smallest relation that still explains the scene's dominance and supporting structure."
compatible_grammar: [CG-01, CG-03, living_identity, place_space, object_event]
incompatible_uses: "Do not reduce a pair to one sitter, a route scene to a tree, or an active surface to a conventional focal object."
evidence_examples: "H08/H09/H15/H17; H02/H13/H19; H01/H04/H05/H16; H03/H06/H18; H07/H12; H10; H14; H11; H20."
```

## V-03 — `gesture_weight`

```yaml
values: [high_action_silhouette, high_paired_relation, low_frontal, viewpoint_or_head_only, not_applicable]
source_selection_cues: "Use only depicted figure evidence from head, torso, arms/hands, legs/feet, weight/contact, and interfigure relation."
compatible_grammar: [living_identity]
incompatible_uses: "Never invent a pose; place_space and object_event are N/A and their direction belongs to ATTENTION, SPACE, SHAPE, MARK, or scene_idea."
evidence_examples: "H08/H17 action; H02/H13/H19 paired relation; H09 low frontal; H15 viewpoint/head only; H01/H03-H07/H10-H12/H14/H16/H18/H20 N/A."
```

## V-04 — `spatial_system`

```yaml
values: [shallow_shared_stage, compressed_encounter, route_recession, obstruction_depth, repetition_recession, sparse_stacked_layers, interlocking_enclosure, frontal_stacked_event, layered_depth_plus_flat_active_surface]
source_selection_cues: "Classify the cues already carrying space: convergence, overlap, repeated scale, obstruction, band stacking, enclosure, frontal alignment, or surface pattern."
compatible_grammar: [CG-03, CG-08, living_identity, place_space, object_event]
incompatible_uses: "Do not choose a generic high-flattening setting or combine unrelated systems without a visible source reason."
evidence_examples: "H02/H08/H09/H13/H19 stage; H15/H17 encounter; H01/H04/H05/H16 route; H03/H10 obstruction; H07/H12 repetition; H14 sparse layers; H06/H18 enclosure; H11 frontal event; H20 layered plus flat surface."
```

## V-05 — `density_pattern`

```yaml
values: [identity, paired_identity_support, action_viewpoint, route_boundary, framed_opening, repetition_distance, extreme_near_layer, isolated_cluster, event_centered, active_surface_field]
source_selection_cues: "Locate where information is needed to preserve identity, direction, layer order, scale, or event."
compatible_grammar: [CG-02, CG-06, living_identity, place_space, object_event]
incompatible_uses: "Do not distribute detail uniformly or assume the named focal object must receive the most marks."
evidence_examples: "H08/H09; H02/H13/H19; H15/H17; H01/H04/H05/H16; H03/H06; H07/H12; H10; H14; H11/H18; H20."
```

## V-06 — `shape_relation`

```yaml
values: [nested, paired, interlocking, stacked, framed, repeated, route_and_anchor, active_field_contained_by_bands]
source_selection_cues: "Reduce the source to three to five dominant shapes, then choose the relation that preserves the subject unit."
compatible_grammar: [CG-01, CG-03]
incompatible_uses: "Do not select shapes by visual similarity to one reference or stop at the instruction 'use large simple shapes.'"
evidence_examples: "H08/H09/H15/H17 nested or stacked; H02/H13/H19 paired; H01/H04/H05/H16 route; H03/H06/H18 framed/interlocking; H07/H12 repeated; H10/H14 stacked; H11 centered stack; H20 active field."
```

## V-07 — `color_intensity`

```yaml
values: [near_monochrome, restrained, moderate_zoning, localized_high_accent, high_saturation_event]
source_selection_cues: "Choose the minimum intensity needed to separate subject roles, planes, or an actual light/surface event."
compatible_grammar: [CG-07, living_identity, place_space, object_event]
incompatible_uses: "Do not use bright, pastel, or highly saturated color as a mandatory signature."
evidence_examples: "H15 near-monochrome; H01/H02/H04/H07/H09/H12/H13/H19 restrained; H03/H06/H08/H10/H16-H18 moderate; H05/H14 localized accent; H11 high-saturation event."
```

This variable records finished-corpus evidence only. It does not cancel the user-authorized `structural_luminosity` runtime default. The target profile may raise chromatic intensity through a luminous carrier, smaller dark anchor, and three-level hierarchy without turning high saturation into a corpus claim or a uniform style slider.

## V-08 — `color_role`

```yaml
values: [figure_ground_separation, sitter_differentiation, plane_zoning, route_or_scale_accent, enclosure_and_light, surface_containment]
source_selection_cues: "Identify which bodies, planes, routes, masses, or events require separation; assign color by that role."
compatible_grammar: [CG-07]
incompatible_uses: "Do not infer how far local color changed from reality and do not remap color without a compositional function."
evidence_examples: "H08/H17 figure-ground; H02/H13/H19 sitters; H03/H06/H10/H16/H18 planes; H04/H05/H14 route or scale; H11/H18 light; H20 surface containment."
```

## V-09 — `edge_target`

```yaml
values: [identity, gesture_or_support, route, framing_vegetation, distance_atmosphere, structural_divider, plane_or_light_boundary, kinetic_field_containment]
source_selection_cues: "Choose boundaries whose clarity preserves identity, contact, direction, enclosure, layer order, or event."
compatible_grammar: [CG-04, living_identity, place_space, object_event]
incompatible_uses: "Do not use one edge class across the image or automatically sharpen the conventional focal object."
evidence_examples: "H02/H08/H09/H13/H17/H19 identity/support; H15 divider; H01/H04/H05/H16 route; H03/H10 vegetation; H07/H12 distance; H06/H11/H18 plane/light; H20 kinetic containment."
```

## V-10 — `mark_density`

```yaml
values: [extremely_sparse, localized_clusters, region_differentiated, repetition_led, surface_dominant]
source_selection_cues: "Set density from the selected information pattern and the number of distinct visible jobs, not from a global looseness preference."
compatible_grammar: [CG-02, CG-05, CG-06]
incompatible_uses: "Do not cover every region with hatching, dots, wash texture, or paper effects."
evidence_examples: "H14/H15 extremely sparse; H09/H17 localized; H01-H06/H08/H10/H13/H16/H18/H19 region-differentiated; H07/H12 repetition-led; H20 surface-dominant."
```

## V-11 — `open_ground`

```yaml
values: [limited, moderate, extensive, extreme]
source_selection_cues: "Choose according to how much low-information area can remain while subject relation, layer order, and scale stay legible."
compatible_grammar: [CG-02, CG-06]
incompatible_uses: "Do not add blank paper as decoration or fill open ground merely to make the image look finished."
evidence_examples: "H20 limited around a dense surface; many route and figure works moderate; H01/H09/H15 extensive; H14 extreme."
```

## V-12 — `sheet_structure_visibility`

```yaml
values: [absent, present_subordinate, present_structural]
source_selection_cues: "Default to absent. Select a visible join only when the intended physical support or assembled composition actually uses multiple sheets."
compatible_grammar: [CG-03, CG-08]
incompatible_uses: "Never add seams as a decorative style token or copy the four-sheet grid into an unrelated image."
evidence_examples: "Visible joins occur in H02, H06, H11, H13, H18, H19, and H20; their structural prominence varies."
```

## Selection order

Select `subject_unit` and `attention_system` first; then `spatial_system` and `shape_relation`; then `density_pattern`, `edge_target`, `mark_density`, and `open_ground`; finally select color roles and any physically justified sheet structure. `gesture_weight` is inserted only for a depicted figure. The combination is one analytical selection serving one relation. Pass it to the matching target profile and `08`; do not pass variable names or option lists to the image model.
