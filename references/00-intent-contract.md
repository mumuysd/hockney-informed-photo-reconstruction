# User Intent and Direct-Reconstruction Contract v0.6

## Purpose and authority

This file defines the user's creative objective for applying the research system to one source photograph. It is an application contract, not a claim derived from the twenty-work corpus. It governs `07-hockney-reading.md` through `10-quality-gate.md` and has priority over default photographic fidelity, medium conventions, and surface polish.

The objective is:

> Treat one real photograph as evidence for core recognition and visible relation, not as an untouchable visual template. Preserve only the minimum identity, applicable living-subject gesture/pose, and scene-idea information needed for continuity. From DECONSTRUCT onward, permit space, proportion, composition, color, and local form to be rewritten as one coherent act of selective observation.

The intended result must remain recognizably connected to the source while visibly replacing camera organization with a constructed pictorial relation. It must also retain visible watercolor materiality, brush articulation, and structural luminosity through higher-chroma color planes and stronger role-based contrast. A faithful repaint, ordinary watercolor filter, opaque digital-paint simplification, uniformly saturated recoloring, decorative poster treatment, or technically compliant image rejected by the user does not satisfy this contract.

The user-authorized `expressive-watercolor-v1` application adds localized drawing judgment: broad watercolor fields and spatial/color relations govern the whole frame, while pressure-varied local marks preserve expression, tension, depth, and contact. The operative details are in `render-profiles.md` under **Localized expression**. This is a transfer of application methods, not corpus evidence or a second rendering mode. It does not restrict the existing rewrite permissions, palette, or watercolor materiality.

## Default runtime outcome

The normal user path is direct and image-first:

```text
one real source photograph
→ internal observation and deconstruction
→ one reconstruction thesis
→ one source relation, matching target profile, and source-specific render recipe
→ one direct built-in Imagegen call
→ inspection of the actual raster
→ at most one targeted revision
```

Do not expose a structure proof, finish stage, control image, blind board, generation script, or technical report unless the user explicitly requests development evidence. Internal grammar reasoning must not become visible prompt jargon.

## Three-part preservation core

Every source receives exactly three top-level preservation categories:

```yaml
preservation_core:
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
    emotional_relation:
    minimum_cues: []
    failure_condition:
```

### `identity_core`

The smallest cue set that keeps the person, pair, subject, place, route, enclosure, event, or active surface recognizable. It is not a complete object inventory and does not require complete facial rendering, exact local color, photographic texture, exact geometry, or original camera placement by default.

### `gesture_pose`

For `living_identity`, preserve the minimum head/body/limb, weight, contact, gait, posture, or inter-subject cues that keep the depicted action or bodily relation distinctive. Human anatomy is not required for a nonhuman subject; protect the source-supported action logic and species-specific silhouette rather than inventing human gesture.

For `place_space` and `object_event`:

```yaml
gesture_pose:
  applicability: not_applicable
  statement: "N/A — bodily gesture does not govern this source relation"
  minimum_cues: []
```

Place, vehicle, machine, object-use, and event direction belongs to ATTENTION, SPACE, SHAPE, EDGE, MARK, or `scene_idea` and must never be relabeled as bodily gesture.

### `scene_idea`

One relational sentence describing what the image remains fundamentally about after incidental detail is removed. `emotional_relation` or functional/environmental relation stays inside this category and must be supported by pose, spacing, contact, use, direction, light, enclosure, exposure, or environmental evidence rather than invented psychology or function.

## Five rewrite domains

Unless a source-specific user lock says otherwise, rewriting may begin during DECONSTRUCT:

```yaml
rewrite_permission:
  space: allowed
  proportion: allowed
  composition: allowed
  color: allowed
  local_form: allowed
```

- **space:** compress, unfold, stack, overlap, lift, open, enclose, or coordinate multiple observed cues;
- **proportion:** alter relative scale among major units while required identity, pose, contact, route, or scene relations survive;
- **composition:** crop, shift, redistribute, enlarge, reduce, interrupt, or rebalance major units;
- **color:** replace dependence on photographic local color and realistic shadow with internal role relationships;
- **local_form:** merge, simplify, enlarge, break, reconnect, or leave incomplete bodies, objects, and environmental units while protecting required cues.

Permission is not a command to maximize distortion. Every rewrite follows:

```text
visible source evidence
→ preservation-core function
→ supported grammar or variable
→ matching target render profile
→ one coherent reconstruction thesis
→ mandatory source-specific render recipe
→ actual-image verification
```

## Four reconstruction languages

These are user-authored application goals. `01–06` decide their source-responsive implementation.

### A — Observed space

Replace automatic camera perspective with deliberately reorganized spatial relations. A tabletop may lift, ground may unfold, background planes may compress, a road may guide more strongly, or mild directional systems may coexist. Do not flatten every source or invent a viewpoint unsupported by the governing subject relation.

### B — Subjective structural color

Use color to separate and connect bodies, planes, routes, enclosures, events, and quiet fields. Hue may depart from literal source values when the internal structure requires it.

The global runtime default is `structural_luminosity` unless an explicit source-specific user lock requests a restrained or near-monochrome result. Every reconstruction must use one continuous in-scene luminous color carrier, one smaller dark anchor, one or two high-chroma regions, at least one value contrast, and at least one warm-cool or complementary contrast. All remaining regions stay medium or restrained in chroma so luminosity is relational rather than a global saturation filter.

Light must be carried by color planes, transparent high-chroma washes, adjacent warm/cool regions, and selectively visible luminous undertone. Do not substitute continuous photographic illumination, realistic cast-shadow modeling, uniform brightening, pastel harmony, a fixed palette, blank paper margins, or equal saturation everywhere.

### C — Functional watercolor edge, mark, and pigment

Allow broken contours, loose boundaries, visible water movement, repeated short marks, construction lines, local unpainted ground, transparent wash overlap, pigment pooling, dry interruption, and pointed-brush pressure change only when each has a regional job. Watercolor materiality is required, but it cannot substitute for composition, space, proportion, shape, information hierarchy, or deletion. Conversely, structural reconstruction cannot pass when it is rendered as opaque digital paint with no visible wash or brush behavior.

### D — Reconstructed viewing

Treat the result as selective looking rather than pixel-by-pixel transcription. Gesture/pose outranks facial microtexture; spatial and large-shape relations outrank incidental objects; local exaggeration is allowed where it clarifies attention, contact, route, opening, scale, or scene relation.

## Active quiet field

Every reconstruction must identify at least one continuous low-information region whose role is structural, spatial, emotional, or scalar.

```yaml
active_quiet_field:
  source_region:
  created_by: [retain_broad, merge, omit, open_edge, unpainted_ground]
  retained_function:
  protected_core: []
  failure_condition:
```

It may be sky, wall, floor, road, water, clothing, distance, or exposed paper within the scene. It must emerge from source-responsive reduction and remain connected to the composition. It must not become a decorative poster margin, a fixed blank percentage, a reason to shrink the subject, or an excuse to erase the preservation core.

## Unified reconstruction minimum

A candidate needs one `reconstruction_thesis`, not two unrelated transformation commands. The thesis must make a single visual relation legible and may coordinate composition, space, proportion, dominant/local form, information allocation, active omission, color, edge, and mark together.

Structural change must be visible beyond surface styling. At thumbnail scale, the result must differ from a camera-preserving repaint through at least two mutually reinforcing aspects among composition, space, proportion, dominant/local form, and information/omission. These aspects are evidence that one thesis was executed; they are not separate prompt priorities.

The following fail:

- preservation survives but photographic organization remains substantially unchanged;
- reconstruction is radical but any required preservation category is lost;
- color, paper, wash, outline, or texture supplies the only difference;
- structure changes but watercolor transparency, pigment behavior, and articulated brush evidence are absent;
- deletion becomes blur, fake border, or empty decoration;
- the scene survives only as an object inventory while its relational or emotional meaning disappears;
- the image drifts into minimal-zine/poster identity through typography, tiny subject scale, fixed paper margins, or reproduction effects.

## User locks and precedence

Exact product geometry, readable text, logo/brand form, object count, architectural module, vehicle part, and local color are transformable by default. They become hard preservation requirements only when the user explicitly locks them. Before accepting such a lock, test whether visible structural reconstruction and Imagegen reliability can coexist with it. If not, block before generation and name the conflict; do not silently reduce the lock, freeze the whole photograph, or report approximate text/geometry as exact.

Under contract clarification `acceptance-contract-v1`, broad wording such as “everything else must stay as photographed” is also an explicit preservation request. If it rules out the required structural reconstruction, ask whether the user permits that reconstruction or wants the unchanged arrangement. Do not compile or call Imagegen while this conflict is unresolved, and do not silently substitute a faithful watercolor filter. A compatible limited lock, such as preserving a pose while allowing space and background changes, proceeds normally; a lock alone is not a reason to block. Apply the same conflict handling in Prompt Only before releasing an executable prompt.

```yaml
user_locks:
  required: []
  forbidden_changes: []
  optional_preferences: []
global_render_preferences:
  color_light_default: structural_luminosity
  override_only_when_explicit: true
```

Resolve conflicts in this order:

```text
explicit source-specific user locks
→ three-part preservation core
→ source-relation boundary
→ visible source evidence
→ validated Core and matching relation grammar
→ matching user-selected target profile
→ global structural-luminosity preference
→ source-selected categorical evidence
→ reconstruction thesis and mandatory render recipe
→ medium and surface preference
```

No lower-priority instruction may silently weaken a higher-priority core. If a meaningful reconstruction cannot preserve the required core, return upstream or report the conflict rather than freezing the photograph or presenting an unrecognizable result.
