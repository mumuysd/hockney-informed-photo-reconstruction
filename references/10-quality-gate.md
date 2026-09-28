# Direct Reconstruction Quality Gate v0.8

## Purpose

Inspect the actual raster, not only the prompt. Decisions are non-compensating: lost recognition, lost/invented living gesture, lost scene idea, wrong relation/profile, blocked fidelity lock, unchanged camera organization, descriptive completeness, failed non-drawing, absent structural luminosity, unranked or leaked marks, generic watercolor, absent regional materiality, profile mixing, poster/print drift, or user rejection cannot be offset by polish.

Do not calculate an aggregate score.

Application revision `expressive-watercolor-v1` adds the local-rhythm checks below inside the existing gate interface. Record the application revision and runtime hashes with new results; do not reclassify historical candidates under changed rules. User preference, visual gate results, and overall generalization validation remain separate facts.

## Required inputs

- original source plus metadata/EXIF-aware displayed orientation;
- accepted source reading v0.6;
- accepted interpretation v0.7 and render recipe v0.4;
- compiled prompt v0.8;
- actual generated raster;
- generation record and any user direction decision.

## Decision states and delivery

- `pass`: all applicable hard gates are clear and direction is accepted or not yet rejected for ordinary use;
- `revise`: direction and all central cores pass; exactly one localized defect is repairable without changing thesis or carriers;
- `fail`: one or more central gates fail, several regions fail, or repair requires upstream recipe change;
- `blocked`: source, displayed orientation, explicit locks, required inputs, or user decision prevents honest execution.

Contract clarification `acceptance-contract-v1` separates what can be delivered from what has passed. Keep the existing decision states and visual thresholds. User preference, quality decision, and permission for another generation are separate: praise changes only the preference evidence. Missing inspection evidence cannot become `pass` or an assumed single-defect `revise`.

| Observed state | Delivery and next action |
|---|---|
| All applicable gates clear; no user rejection | Return the image. Ordinary use does not require a new approval question merely to label a fully inspected candidate `pass`; formal calibration still follows its acceptance requirements. |
| Actual raster has failed gates; user accepts or has not yet responded | Show or retain the candidate, briefly naming the visible limitations. Keep `fail` when its criteria apply. “Accepted direction” is not “all requirements passed.” Multiple failures end this cycle; do not discard an accepted candidate, repeatedly regenerate, or revise merely to reduce marks. |
| Direction accepted; exactly one eligible localized defect; all other required evidence clear | Apply the existing single targeted revision protocol, then compare both candidates. Acceptance by itself is insufficient for eligibility. |
| User rejects the candidate or corrects which image was accepted | Attach feedback to the correct candidate. Keep the rejected candidate as evidence, identify its visible problem, and return upstream; do not present it as an accepted final or begin another generation cycle from that feedback alone. |
| Source/locks/inspection evidence unresolved | Name the missing input or conflicting requirement. Use `blocked` where required evidence is missing; do not fabricate a pass, a raster inspection, or repair eligibility. Request only information needed for the next action. |

Use ordinary visual language in the brief delivery note, not internal gate IDs. For example, an accepted portrait with unresolved background repetition can be acknowledged as “保留这张，人物神态方向已认可；背景重复细节仍未达到这次的简化要求。” Do not append an unsolicited technical report or ask again whether the user likes an already accepted image. If the user explicitly requests further work, reevaluate the applicable upstream or revision path; this table is not a blanket stop on authorized work.

For new reviews, cite the visible region and unmet requirement in the existing evidence fields. Record later user feedback or a correction as a subsequent event linked to the candidate; preserve the original generation and inspection records. Never retroactively turn a historical failure into a pass using this clarification.

### Evidence calibration without changing thresholds

| Check | Evidence to inspect | Insufficient evidence or failure |
|---|---|---|
| Useful local richness | Declared focal group has unequal pressure, direction and spacing that preserve expression, depth or contact; surrounding suppressed regions remain distinct | Mark count alone proves neither success nor failure. Repeated inventory across suppressed regions fails; deleting the expression or contact also fails. |
| Quiet watercolor region | The declared region reads as a continuous wash at whole-frame scale, with only marks permitted by its existing ceiling | Blur, a blank decorative margin, or primary/secondary marks entering the quiet region fails. Continuous does not mean bare paper; the ban on global grain and uniform treatment remains. |
| Structural reconstruction | At least two declared, mutually supporting changes are visible at thumbnail scale while required relations and contact survive | A recipe's count or an arbitrary displacement is insufficient. A changed road that breaks credible building contact cannot earn a pass merely because it is different. |
| Material and ranked marks | Inspect the actual broad transparent field and the declared local pigment/brush events, then check mark jobs and exclusions | “Looks like watercolor” or prompt compliance alone is insufficient; missing regional differentiation still fails under Gates 6–7. |

These are application-level reading aids for the existing gates, not new art-research claims. Do not use an attractive or user-preferred result to offset another failed gate.

## Gate 0 — Input integrity

Verify source path/hash, actual visual inspection, raw pixel matrix, EXIF orientation, displayed orientation, source role, Imagegen input inclusion, prompt/recipe hashes, output path/hash/dimensions, and lineage.

A rotated JPEG must record both raw matrix and displayed orientation. Treating a portrait-displayed source as landscape is an input-integrity failure unless the user explicitly requests the change.

## Gate 1 — User direction

```yaml
user_direction:
  status: [accepted, accepted_partial, pending, rejected]
  accepted_elements: []
  rejected_elements: []
```

Partial acceptance locks only named elements. It does not make a failed candidate revisable when failures span multiple carriers or regions.

## Gate 2 — Relation and three-part core

```yaml
relation_and_core:
  expected_relation:
  observed_relation:
  relation_status: [clear, absent]
  identity_core: [clear, weakened, lost]
  gesture_pose: [clear, weakened, lost, not_applicable]
  scene_idea: [clear, weakened, lost]
  invented_core_cue: [true, false]
```

Any lost/absent or invented central cue fails. `gesture_pose` is required only for `living_identity`; place/object direction cannot be counted as bodily gesture.

Simplification also fails when it deletes the middle layer needed to read those cores. Check the whole before counting omitted details: a grouped place must still read as that place relation, an object must retain necessary joins or use, and a living subject must retain plausible source-supported head, torso, limb, contact, and weight structure. Strange or unsupported anatomy is a hard failure, not an expressive exception.

## Gate 3 — Exact fidelity locks

```yaml
fidelity_lock_check:
  requested: []
  visibly_preserved: []
  drifted_or_unverifiable: []
  status: [not_requested, clear, partial, failed, should_have_blocked]
```

Do not claim exact product geometry, logo, text, count, architectural module, or color when actual inspection cannot verify it. If an accepted lock was incompatible with reconstruction or Imagegen reliability, mark `should_have_blocked` and fail.

## Gate 4 — Thesis, reconstruction, and hierarchy

At thumbnail scale verify:

- one governing relation controls first read;
- exactly three to five dominant carriers replace inventory;
- at least two declared manifestations visibly replace camera organization;
- high, medium, and quiet information regions differ;
- active quiet ground remains part of the subject relation rather than a decorative margin;
- non-drawing inventory is merged, omitted, open, or mass-only—not merely soft or blurred.
- broad watercolor fields and spatial/color relations still govern the whole-frame read; localized drawing has not become a global line skeleton;
- the retained focal group still carries expression, depth, or contact rather than becoming a sterile icon after deletion.

Any absent central check fails. A localized partial permits revision only when every other hard gate passes.

## Gate 5 — Structural luminosity

```yaml
luminous_color_check:
  expected_luminous_carrier:
  observed_luminous_carrier:
  expected_dark_anchor:
  observed_dark_anchor:
  chroma_hierarchy:
    high: []
    medium: []
    restrained: []
  observed_value_contrast:
  observed_chromatic_contrast:
  photographic_or_margin_light_detected: [true, false]
  equal_saturation_or_mud_detected: [true, false]
  status: [clear, partial, absent]
```

Light must remain relational through transparent color or adjacent planes. Global brightening, equal saturation, gray mud, photographic shadows, white-margin glow, or paper texture as light fails.

## Gate 6 — Ranked mark architecture

```yaml
ranked_mark_check:
  expected_families:
    - priority:
      geometry:
      region:
      excluded_regions: []
      job:
  observed_families: []
  primary_family_visibly_distinct: [true, false]
  excluded_region_leakage: []
  uniform_surface_or_outline_detected: [true, false]
  status: [clear, partial, absent]
```

Pass only when two or three geometrically distinguishable families perform unequal jobs. The primary family must be visibly independent at full view and absent from excluded/quiet regions. Broad unmarked fields do not count as a family. One outline, hatch, wash, grain, or soft texture everywhere fails.

For the localized-expression application, compare the actual raster with each declared retained group and suppressed zone. Check pressure variation, interruption, directional relation, and any compact purposeful echo. Fail equal-weight mechanical repetition or repeated motifs continuing through a suppressed zone. Do not fail useful abundance merely because it contains several marks. Conversely, fail an over-pruned focal group that loses source-supported expression, depth, spatial cadence, or contact. Record the visible evidence in `observed_families` and the resulting status in `ranked_mark_check`; do not infer success from the prompt.

An explicitly assigned subordinate sparse family may enter a quiet region only when its ceiling is `one_sparse_family` and the region is not excluded for that family. No discrete marks enter a `no_marks` region. This exception never admits primary or secondary marks.

## Gate 7 — Watercolor materiality

```yaml
watercolor_material_check:
  expected_mode:
  broad_field_evidence: []
  precision_recognition_or_anchor_evidence: []
  opaque_or_smooth_digital_fill_detected: [true, false]
  global_grain_or_repeated_treatment_detected: [true, false]
  status: [clear, partial, absent]
```

Pass only when a broad field shows transparent wash/stain behavior and a precision/recognition/contact/anchor region shows pointed-brush pressure change, compact wet deposition, selective overlap, dry interruption, pooling, or another declared event. Simulated paper grain, generalized blooms, or smooth digital fill alone do not count.

Local line expressiveness must arise from those regional watercolor applications. Dry-only drawing, a universal black outline with colored infill, or line dominance across broad fields fails even when the local marks are attractive. A quiet continuous wash remains valid and is not required to become bare paper.

## Gate 8 — Relation-specific checks

### `living_identity`

- identity is sparse and distributed rather than fully modeled;
- source-supported action/contact survives before anatomy or surface texture;
- nonhuman subjects retain species-specific silhouette/action without humanization;
- primary identity/action marks remain localized and independent from setting marks.
- indispensable visible expression survives through head direction and role-appropriate eye, mouth, hair, or silhouette relationships without a numerical feature ceiling; tiny or unresolved faces receive no invented detail;
- retained facial cues share the watercolor language of the work, without independently polished portrait modeling or humanized animal expression.

For `living_subject_in_expansive_scene` additionally require:

```yaml
expansive_environment_check:
  environment_carrier_count:
  anchor_group_count:
  representative_cues_per_group: []
  fields_read_before_anchors: [clear, partial, absent]
  subject_environment_link: [clear, partial, absent]
  inventory_takeover_absent: [true, false]
  environment_primary_line_absent: [true, false]
```

Pass only with one or two environmental carriers, two or three functional anchor groups, fields-and-grouped-place-before-exemplar thumbnail order, a clear link, no repeated setting inventory beyond the explicitly budgeted exemplars, and no primary identity-line geometry in the environment.

### `place_space`

- gesture is N/A;
- route/opening/enclosure/room/threshold/built mass/event/active surface remains one relation;
- source-supported recession or spatial family is coherent;
- repeated architectural/interior modules are merged unless locked;
- no real-estate rendering, architectural visualization, or technical-drawing fallback.

### `object_event`

- gesture is N/A;
- minimum silhouette/proportion/opening/joint/count/arrangement/contact/direction/function survives;
- three to five carriers replace parts, labels, ingredients, modules, or event units;
- exact locks pass or generation should have blocked;
- no product-ad gloss, catalog staging, technical illustration, exhaustive part rendering, or object-by-object still-life fallback.

## Gate 9 — Anti-identity, anti-filter, and anti-poster

Ask:

1. If watercolor and paper texture disappeared, would structure, space, hierarchy, and deletion still differ materially from a photographic repaint?
2. If global grain disappeared, would regional wash, pigment, pressure, dry interruption, pooling, or exposed ground still show watercolor materiality?
3. If typography, blank margins, collage, print defects, and token accent disappeared, would the intended identity remain?
4. If photographic shadows and paper glow disappeared, would color planes still produce luminous carrier, dark anchor, and both contrasts?
5. If semantic labels disappeared, would the chosen living/place/object-event relation still be visible through geometry and attention?

All answers must be yes. Also fail invented subjects, source-absent motifs, reference residue, profile mixing, fixed 3:5 or whitespace defaults, text, logos not present/locked, scan/halftone/xerox effects, decorative border, global paper grain, and uniform brush treatment.

## Targeted revision protocol

```yaml
revision:
  target:
  diagnosis:
  repair:
  lock: []
  do_not_change: []
  upstream_return: [07, 08, 09, none]
  attempt_number: 1
```

Revise only one localized problem. Preserve passing relation, core, locks, thesis, carriers, manifestations, hierarchy, non-drawing, color, and mark jobs. If failure spans carriers, inventory, mark hierarchy, material system, or user direction, return upstream. Never make a second automatic revision.

Do not revise merely to lower the number of lines, facial features, or useful local marks. Use `LOCK / REPAIR / DO NOT CHANGE` to protect retained rhythmic groups, expression, spatial depth, contact, broad watercolor fields, quiet regions, and previously passing gates while repairing the one observed defect.

After the revision, inspect both rasters at whole-frame and detail scale and rerun every applicable gate. Reject a revision that introduces a new hard-gate failure or loses passing expression, depth, rhythm, or watercolor dominance. Among eligible candidates prefer the one that repairs the targeted defect without those losses; if there is no demonstrated improvement, retain the initial candidate. Preserve its actual failure decision and limitations if it still fails; never label it a pass because the revision is worse. Neither candidate is deliverable as a pass when required evidence cannot be inspected.

## Output schema

```yaml
quality_gate:
  gate_version: "0.8"
  source_id:
  candidate_id:
  source_relation:
  relation_implementation:
  profile_id:
  review_level: [normal_use, calibration, holdout, formal_validation]
  input_integrity:
  user_direction:
  relation_and_core:
  fidelity_lock_check:
  thesis_and_hierarchy:
  non_drawing_check:
  luminous_color_check:
  ranked_mark_check:
  watercolor_material_check:
  relation_specific_check:
  anti_identity_checks: []
  anti_filter_test:
  anti_poster_test:
  decision: [pass, revise, fail, blocked]
  primary_failure:
  revision:
  unresolved_evidence: []
```
