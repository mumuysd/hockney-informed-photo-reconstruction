# Target Render Profiles v0.4

## Purpose and evidence boundary

Choose one profile after source reading and before interpretation. Profiles narrow visible decisions; they do not supply objects, palettes, layouts, or artist imitation.

- `portrait_sparse_identity` is grounded in the seven human figure works; nonhuman and expansive-environment behavior is user-authorized application scope.
- `landscape_economical_open_field` is grounded in the thirteen landscape works; built-space behavior is user-authorized application scope.
- `object_event_selective_structure` is a user-authorized application profile that transfers only cross-category Core Grammar and must not be described as a corpus finding.

All profiles use `structural_luminosity` unless an explicit source-specific lock requests restrained or near-monochrome color. Light comes from a continuous in-scene luminous carrier, a smaller dark anchor, one or two high-chroma regions, medium and restrained tiers, value contrast, and warm-cool or complementary contrast—not from uniform saturation, photographic shadows, white margins, or paper glow.

## `portrait_sparse_identity`

Use only with `source_relation: living_identity`.

### Fixed visible identity

- Preserve an individually recognizable living subject through sparse distributed anchors rather than complete surface modeling.
- Build pose/action/contact from body and support masses before anatomy, fur, feather, scale, or garment detail.
- Keep one or two high-information identity/action clusters inside broader unresolved fields.
- Use a primary pointed or contour mark family only at named identity/action junctions; exclude it from broad body and setting fields.
- Let transparent washes carry broad masses and concentrated pigment or pressure-changing lines carry selected identity/contact nodes.

### Implementations

```yaml
relation_implementation:
  - single_living_subject
  - grouped_living_subjects
  - viewing_or_action_encounter
  - nonhuman_living_subject
  - living_subject_in_expansive_scene
```

For `living_subject_in_expansive_scene`, use one or two environmental carriers and exactly two or three functional anchor groups. One anchor group may contain one or two non-repeating place-identity exemplars when pure mass/contour/value would make the place generic. When route/support occupies a carrier, all other setting and atmosphere merge into one combination field. The whole setting uses at most one subordinate sparse mark family; carrier fields and grouped place identity read before exemplar cues at thumbnail scale.

### Material mode

`transparent_line_and_wash_portrait`: transparent broad body/ground fields plus localized pointed-line, compact wet, overlap, pooling, or dry-interruption evidence at identity, action, contact, or support nodes.

## `landscape_economical_open_field`

Use only with `source_relation: place_space`.

### Fixed visible identity

- Construct the place as route, opening, enclosure, field, boundary, event, active surface, room volume, threshold, circulation path, or architectural mass relation rather than inventory.
- Preserve source-supported recession, stacking, overlap, enclosure, or active surface; do not apply universal flattening.
- Use three to five dominant planes or masses with functional active quiet ground.
- Concentrate marks only where they prove direction, enclosure, scale, layer order, opening, light, or material boundary.
- Keep `gesture_pose: not_applicable`; direction belongs to space, shape, edge, mark, or scene idea.

### Implementations

```yaml
relation_implementation:
  - outdoor_place
  - built_space
  - active_place_or_surface
```

Built spaces merge repeated windows, doors, bays, fixtures, furniture, tiles, lights, signs, cables, vents, and parked inventory unless one is a functional anchor. Reject architectural visualization, real-estate rendering, technical drawing, and module-by-module facades.

### Material mode

`open_wash_and_directional_brush_landscape`: transparent broad place fields plus localized wet, pointed, dry, pooled, repeated, or directional brush evidence at declared boundaries or anchors.

## `object_event_selective_structure`

Use only with `source_relation: object_event`.

### Fixed visible identity

- Preserve an object, product, arrangement, machine, vehicle, use relation, or complex visible event through minimum silhouette, proportion, opening, joint, count, contact, direction, or functional cues.
- Build three to five carriers before seams, labels, ingredients, parts, packaging, buttons, spokes, windows, or background units.
- Treat an arrangement or event as one relation through overlap, gap, rhythm, direction, exchange, contact, or one interruption.
- Keep one or two recognition/contact regions high information; quiet broad body, table, road, wall, or atmosphere fields remain unfilled by decorative marks.
- Exact geometry, branding, readable text, count, or local color is not preserved unless explicitly locked and feasible.

### Implementations

```yaml
relation_implementation:
  - single_object
  - arranged_objects
  - object_in_use_or_vehicle
  - complex_event
```

### Material mode

`selective_contour_and_wash_object`: one broad object/support/environment field uses a clean transparent wash or stain; one recognition/contact region uses a primary contour, pointed line, compact wet deposit, selective overlap, dry interruption, or pooled boundary. Reject advertising gloss, technical illustration, exhaustive part description, and global texture.

## Localized expression — application revision `expressive-watercolor-v1`

These user-authorized drawing judgments are adapted from the local `visual-essence-sketch-zine` package. They are not new corpus findings. The rules below are self-contained: do not load that Skill, its images, or its dry-medium rules during generation.

### Watercolor remains dominant

At whole-frame scale, broad transparent fields, structural luminosity, and reconstructed spatial relations organize the image. At close view, local pointed-brush pressure, compact wet deposits, selective overlap, or dry interruptions give chosen junctions force and character. A dry interruption is one watercolor event, not a command to turn the whole work into dry drawing. Do not add universal black outlines, a black-gray base, a source-derived two-color ceiling, or a line skeleton that dominates every field.

### Use the existing recipe fields

- `information_budget`: locate retained focal rhythm in high regions, supporting fragments in medium regions, and continuous quiet watercolor fields. Regions refer to the intended reconstructed composition, not an immutable grid over the photograph.
- `non_drawing_contract`: name the repeated units and zones to merge or omit, together with the structural rhythm that must survive. Do not erase a useful group merely because it contains several marks.
- `mark_map`: express thick-thin pressure, angular turns, interruption, and any compact purposeful echo within `geometry`; use `region`, `excluded_regions`, and `job` to confine it. Keep the existing two-or-three-family budget; echo marks belong to their parent family, not an extra all-over effect.
- `material_system.applications`: pair broad transparent wash evidence with the declared local line or pigment behavior. A quiet region may retain a continuous watercolor plane; it need not become bare paper.

When quiet regions allow `one_sparse_family`, only the explicitly assigned subordinate family may enter; primary and secondary families remain excluded. With `no_marks`, no discrete mark family enters. Region exclusions always take precedence.

### Retain rhythm, suppress inventory

Useful repetition is selective, directionally related, unequal in pressure or completion, and separated by quiet intervals. It must explain a source-supported relation: a face turn, limb contact, facade junction, wave layer, branch scaffold, or object hinge. Choose only functions actually present. Fail repeated windows, foliage, seams, hatching, or parallel redraws that have equal weight and continue through the suppressed zones. Also fail a focal region reduced to a generic icon or isolated contour after losing its expression, depth, or contact.

For dense places, a retained group may contain incomplete linked fragments at a chosen junction; it must not restore a countable facade or background inventory. Existing expansive-environment anchor and family budgets still apply. No numerical source-coordinate grid or new mark quota is introduced.

### Expression follows the subject's role

For an indispensable visible face, preserve source-supported head direction and the eye, mouth, hair, or silhouette relationships that carry expression. Glasses, nose punctuation, selective teeth, or hair strands may remain when useful; no universal feature-count ceiling applies. For a small or unresolved face, retain direction and silhouette without inventing features. A supporting body retains its action and contact before local character. Nonhuman subjects retain their own morphology and visible expression without humanization.

Resolve these cues through the same localized watercolor marks as the rest of the image. Fully polished facial modeling, cosmetic features, pores, strand-by-strand hair, mechanical anatomy tracing, and invented expressive gestures still fail.

## Mandatory `render_recipe` v0.4

Historical records remain unchanged. The existing v0.4 interface is retained; the application revision changes the decisions recorded inside it, not its wire shape. New generation records identify `application_revision: expressive-watercolor-v1` and the runtime file hashes. Every new v1.0 reading produces:

```yaml
render_recipe:
  recipe_version: "0.4"
  source_relation: [living_identity, place_space, object_event]
  relation_implementation: [single_living_subject, grouped_living_subjects, viewing_or_action_encounter, nonhuman_living_subject, living_subject_in_expansive_scene, outdoor_place, built_space, active_place_or_surface, single_object, arranged_objects, object_in_use_or_vehicle, complex_event]
  profile_id: [portrait_sparse_identity, landscape_economical_open_field, object_event_selective_structure]
  governing_relation:
  fidelity_locks:
    exact_requirements: []
    feasibility: [not_requested, compatible, blocked]
    conflict:
  shape_map:
    - source_region:
      visible_carrier:
      simplification_action:
      forbidden_individualization:
  spatial_rewrite:
    driver:
    visible_manifestations: []
  information_budget:
    high_regions: []
    medium_regions: []
    quiet_regions: []
    quiet_region_mark_ceiling: [no_marks, one_sparse_family]
  non_drawing_contract: []
  expansive_environment:
    environment_carriers: []
    anchor_groups:
      - source_region:
        retained_function:
        simplified_form:
        representative_cues: []
        repetition_block:
    merged_inventory: []
    environment_mark_ceiling: one_sparse_family
    subject_environment_link:
    thumbnail_read:
  color_mode:
  color_map:
    - source_region:
      structural_role:
      hue_value_relation:
  luminous_color_system:
    mode: structural_luminosity
    luminous_carrier:
      region:
      method: [clean_high_chroma_transparent_wash, luminous_undertone, adjacent_warm_cool_planes]
    dark_anchor:
      region:
      role:
    chroma_hierarchy:
      high: []
      medium: []
      restrained: []
    contrast_pairs:
      - regions: []
        axis: [value, warm_cool, complementary]
        visible_job:
    shadow_policy: color_planes_without_continuous_modeling
  edge_map:
    firm: []
    broken_or_open: []
    soft_or_lost: []
  mark_map:
    - priority: [primary, secondary, subordinate]
      geometry:
      region:
      excluded_regions: []
      job:
  material_system:
    mode: [transparent_line_and_wash_portrait, open_wash_and_directional_brush_landscape, selective_contour_and_wash_object]
    ground_role:
    applications:
      - region:
        application:
        visible_evidence:
    forbidden_global_behaviors: []
  default_prior_to_block:
```

Set `expansive_environment: not_applicable` unless the implementation is `living_subject_in_expansive_scene`.

## Renderability gate

Block compilation unless all conditions pass:

1. One source relation, one implementation, and one profile match exactly; no profile averaging occurs.
2. The three-part core is unchanged from source reading. `gesture_pose` is required only for `living_identity` and N/A otherwise.
3. `fidelity_locks.feasibility` is not `blocked`; every explicit exact requirement is visible, source-supported, and compatible with reconstruction.
4. `shape_map` contains three to five source-present carriers; every entry names a visible simplification and forbidden individualization.
   Carrier reduction must still preserve the minimum cues in `identity_core`, applicable `gesture_pose`, `scene_idea`, and feasible explicit locks. Grouped contour rhythm, necessary joins, plausible living-subject morphology, and relation-defining contact may remain when they are the minimum evidence for the whole; repeated inventory may not return.
5. One structural driver has at least two mutually reinforcing visible manifestations.
6. High, medium, and quiet regions differ; the quiet ceiling is categorical.
7. `non_drawing_contract` names source-present inventory to merge, omit, leave open, or represent only as mass.
8. `expansive_environment` is complete only for `living_subject_in_expansive_scene`: one or two environmental carriers, two or three functional anchor groups, at most two non-repeating representative cues per group, non-empty merged inventory, one sparse family, a link, and fields/grouped-place-before-exemplar thumbnail read.
9. Structural luminosity contains one continuous luminous carrier, one smaller dark anchor, one or two high-chroma regions, non-empty medium and restrained tiers, value contrast, chromatic contrast, and no photographic shadow policy.
10. `mark_map` contains two or three geometrically distinct families with at least one primary family. Priorities are unequal; every family names excluded regions. No family enters an excluded region; quiet regions admit only their explicitly assigned subordinate sparse family when the ceiling allows it.
    Local geometry names pressure, interruption, or selective echo and a source-supported job. Retained rhythmic groups and suppressed inventory zones are distinguished; neither equal-weight repetition nor loss of useful expression/depth/contact is acceptable. Watercolor fields retain whole-frame dominance.
11. Material mode matches the profile, covers a broad field and one recognition/precision/anchor region, and names visible pigment or brush evidence.
12. Forbidden global behavior blocks opaque all-over paint, muddy repeated mixing, uniform paper grain, one repeated treatment, white-margin glow, and profile-specific default fallback.
13. No artist name, another visual Skill, reference artwork, fixed poster ratio, typography, scan/print identity, vague render language, copied motif, or unresolved decision remains.

## Runtime boundary

Use only the original user photograph as visual input. Do not pass corpus works, style references, rejected outputs, or assets from other Skills to Imagegen. The profiles are internal text guidance and do not guarantee compliance; only actual-raster inspection can establish success.
