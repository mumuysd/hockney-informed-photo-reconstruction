# Source Reading and Deconstruction v0.6

## Purpose

Perform OBSERVE and DECONSTRUCT for one visible real photograph. Output one evidence-bounded source contract and one render handoff. Do not name an artist, choose surface style first, or expose the internal Visual Plan unless requested.

Read `00-intent-contract.md`, `01-core-grammar.md`, and `02-variables.md`. After routing, read exactly one matching grammar: `05-portrait-grammar.md`, `06-landscape-grammar.md`, or `object-event-grammar.md`.

## Stage 1 — Observe

Record only visible source evidence:

| Dimension | Record | Do not infer |
|---|---|---|
| ATTENTION | what wins and through which cues | conventional subject importance |
| SUBJECT | smallest governing living/place/object/event relation | object inventory |
| GESTURE | living subjects only: head/body/limb, weight, contact, gait, group relation | invented anatomy or nonliving gesture |
| SPACE | convergence, overlap, stacking, enclosure, repetition, threshold, circulation, containment | automatic flattening |
| DETAIL HIERARCHY | current density peaks and quiet fields | every detail must survive |
| SHAPE | three to five candidate carriers and their relation | contour tracing |
| COLOR | role-bearing value, warm/cool, chroma, light, material breaks | how far color changed from reality |
| EDGE | firm, broken/open, soft/lost source opportunities | uniform outline |
| MARK | visible directional/material geometries | generic brush feeling |
| DELETION | inventory that can merge, omit, open, or become mass-only | blur as deletion |

Inspect metadata and EXIF orientation when available. Record `displayed_orientation` separately from raw pixel-matrix dimensions. The runtime defaults to the displayed orientation.

## Stage 2 — Choose one source relation

Use visible indispensability, not semantic labels:

- `living_identity`: removing or genericizing the living subject, identity, pose/action, contact, or group relation changes the image's core;
- `place_space`: route, enclosure, opening, room volume, built mass, repetition, event field, or active surface remains primary after incidental subjects/objects are removed;
- `object_event`: a nonliving object, product, arrangement, vehicle, use relation, or complex event remains primary and place is support.

Choose one implementation:

```yaml
living_identity: [single_living_subject, grouped_living_subjects, viewing_or_action_encounter, nonhuman_living_subject, living_subject_in_expansive_scene]
place_space: [outdoor_place, built_space, active_place_or_surface]
object_event: [single_object, arranged_objects, object_in_use_or_vehicle, complex_event]
```

Tiny or replaceable living subjects do not activate `living_identity`. Environment direction is never bodily gesture. If two relations remain equally indispensable and no source-supported thesis can rank them, block rather than profile-average.

## Build the source contract

Extract exactly three preservation categories:

```yaml
source_contract:
  identity_core:
    statement:
    minimum_cues: []
    failure_condition:
  gesture_pose:
    applicability: [required, not_applicable]
    statement:
    minimum_cues: []
    failure_condition:
  scene_idea:
    statement:
    emotional_or_functional_relation:
    minimum_cues: []
    failure_condition:
```

`gesture_pose` is required only for `living_identity`. Keep every cue set minimal. Exact geometry, text, logo, object count, local color, camera position, proportion, and inventory remain transformable unless explicitly locked.

## Evaluate exact fidelity locks

```yaml
fidelity_locks:
  exact_requirements: []
  source_support: [not_requested, visible, unsupported]
  reconstruction_compatibility: [not_requested, compatible, blocked]
  conflict:
```

Products, buildings, vehicles, object counts, logos, and readable text do not receive automatic high preservation. If an explicit lock is unsupported by the source or cannot coexist with visible reconstruction/Imagegen reliability, stop and report the conflict.

## Name one governing relation

Choose one subject unit and attention system supported by at least two visible cues. Write one plain-language relation, not a list or style phrase. Examples of form only:

- `turning body linked to distant place through one descending wedge`;
- `room volume opened by one light threshold`;
- `single vessel and poured stream held by one contact relation`;
- `vehicle direction opposed by a compressed environment field`.

Do not reuse the examples unless the source contains the relation.

## Build deletion and rewrite opportunities

Before material language, name:

- three to five source-present candidate carriers;
- high, medium, and quiet information regions;
- source-present inventory to merge, omit, leave open, or represent only as mass;
- at least two mutually reinforcing rewrite opportunities among composition, space, proportion, dominant/local form, and information/omission;
- one active quiet field with a retained function;
- one likely source-specific default fallback to block.

For `living_subject_in_expansive_scene`, nominate one or two environmental carriers, exactly two or three functional anchor groups, at most one or two non-repeating place-identity exemplars per group, merged setting inventory, a subject-environment link, and a thumbnail read in which fields and grouped place identity precede exemplars.

## Prepare the render handoff

Before choosing local marks, identify source-supported expression/action/contact cues and any contour rhythm needed for depth or place identity. Distinguish useful rhythmic groups from repeated inventory; record them in the existing core, candidate information budget, candidate marks, and non-drawing fields. Do not impose a feature-count ceiling or invent a face when the source does not resolve one. These are observation inputs, not locks on the source's coordinates: final mark and quiet regions belong to the reconstructed composition.

Select exactly one profile and material mode:

```yaml
living_identity:
  profile_id: portrait_sparse_identity
  material_mode: transparent_line_and_wash_portrait
place_space:
  profile_id: landscape_economical_open_field
  material_mode: open_wash_and_directional_brush_landscape
object_event:
  profile_id: object_event_selective_structure
  material_mode: selective_contour_and_wash_object
```

Candidate mark families must already differ by geometry, region, priority, excluded regions, and visible job. At least one primary family is required; quiet regions cannot receive it.

## Required output

```yaml
source_reading:
  reading_version: "0.6"
  source_id:
  source_integrity:
    actual_source_inspected: true
    raw_pixel_matrix:
    exif_orientation:
    displayed_orientation: [portrait, landscape, square]
  source_relation: [living_identity, place_space, object_event]
  relation_implementation:
  observed:
    ATTENTION:
    SUBJECT:
    GESTURE:
    SPACE:
    DETAIL_HIERARCHY:
    SHAPE:
    COLOR:
    EDGE:
    MARK:
    DELETION:
  source_contract:
  fidelity_locks:
  governing_relation:
  active_quiet_field:
  user_locks:
  candidate_shape_carriers: []
  candidate_information_budget:
    high_regions: []
    medium_regions: []
    quiet_regions: []
    quiet_region_mark_ceiling:
  candidate_non_drawing: []
  rewrite_opportunities: []
  candidate_marks:
    - priority:
      geometry:
      region:
      excluded_regions: []
      job:
  render_handoff:
    target_profile_id:
    material_mode:
    expansive_environment: [object, not_applicable]
    likely_default_prior:
  unresolved_decisions: []
```

## Acceptance gate

Accept only when the actual source and displayed orientation were inspected; one relation and implementation are unambiguous; the three-part core is minimal and source-supported; gesture applicability is correct; exact locks are feasible; one governing relation is visible; three to five candidate carriers and an explicit deletion plan exist; two structural rewrite opportunities reinforce one thesis; active quiet ground remains functional; mark priorities and exclusions are complete; profile and material mode match; expansive-environment fields are complete only when applicable; and no artist name, profile averaging, vague style language, unsupported fidelity claim, poster default, or unresolved decision remains.
