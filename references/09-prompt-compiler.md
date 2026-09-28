# Direct Image Prompt Compiler v0.8

## Purpose

Compile one accepted `render_recipe` v0.4 into one compact four-paragraph prompt containing only visible decisions. Use no artist name, corpus artwork, rule ID, schema label, evidence count, another visual Skill, reference artwork, or research explanation.

The original photograph is the sole visual input. The prompt may name it only as the edit target/source photograph.

## Required inputs

- inspected source and displayed orientation;
- one accepted `07` v0.6 reading;
- one accepted `08` v0.7 interpretation;
- complete `render_recipe` v0.4;
- matching relation/profile/material mode;
- no blocked fidelity lock or unresolved decision.

Stop if versions, source ID, relation, implementation, core, profile, fidelity locks, thesis, or recipe disagree.

## Compilation principles

1. Compile positive replacement before negative inventory.
2. Represent every recipe decision once. Do not repeat the same preservation cue, object list, color hierarchy, material ban, or default prior in several paragraphs.
3. Use actual visible nouns and actions: wedge, band, block, opening, contour, stain, wash, overlap, bracket, pooled edge, dry interruption—not internal field names.
4. Keep hard avoids short. Paragraph 4 contains only applicable failures not already expressed as positive replacements or regional exclusions.
5. Medium follows structure. Do not lead with generic watercolor, paper texture, painterly feeling, or expressive looseness.

## Four-paragraph prompt

### 1. Source contract

Label Image 1 as the sole edit target and visual source. Preserve the minimum identity, applicable living gesture, scene relation, displayed orientation, and any feasible exact locks. State permitted rewrite domains. Add no source-absent subject, object, text, border, or poster element.

### 2. Governing relation and positive replacements

State the governing relation and structural driver. Compile all three-to-five carriers as concrete replacements and state two visible spatial manifestations. For an expansive living subject, describe one or two environmental fields, the named anchor groups, their few non-repeating representative cues, and the subject-environment link. Describe stairs, rails, architecture, products, arrangements, vehicles, or event units as positive merged geometry rather than relying only on prohibitions.

Positive replacement must preserve minimum legibility. For living subjects, state plausible source-supported silhouette, joints, weight, and action before expressive line treatment. For places, retain the smallest grouped contour or value rhythm that makes the place relation readable without restoring countable inventory. For objects/events, retain the joins, contact, or use relation needed to understand the whole.

### 3. Information, color, marks, and material

Name high, medium, and quiet regions; state the most important non-drawing groups compactly. Compile luminous carrier, smaller dark anchor, high/medium/restrained chroma tiers, value and chromatic contrasts, and color-plane shadow policy. Compile mark families in priority order: primary first, then secondary and subordinate; state each geometry, exclusive region, excluded regions, and job. Compile the broad-field and precision/recognition/anchor watercolor applications once. Prohibit global grain or repeated treatment here, not again in paragraph 4.

For `expressive-watercolor-v1`, those same regional sentences must name the retained focal rhythm, its visible thick-thin/interrupting behavior, and the repeated units removed elsewhere. Tie each local line behavior to its declared watercolor application rather than adding generic sketch or expressionist style words. State that broad transparent color fields organize the whole frame; keep local lines at the chosen junctions. Compile source-supported gaze, mouth, hair, pose, or contact only when their role warrants it, with no facial-feature count. Do not append a second style paragraph or source-coordinate lock.

### 4. Short remaining blockers

Block the source-specific default prior and only the remaining applicable failures: unchanged camera organization, invented subjects/objects, unverifiable locked text/geometry, profile mixing, opaque/muddy fallback, typography/poster/print identity, or another failure not already replaced in paragraphs 2–3.

## Prompt template

```text
Use Image 1 as the sole edit target and visual source. Preserve [minimum identity], [gesture or N/A], [scene relation], [displayed orientation], and [feasible exact locks]. Allow [rewrite domains]. Add no [source-absent content or text].

Reconstruct the image around [governing relation] through [driver]. Replace the source with [carrier actions 1–5]. Make the rewrite visible through [manifestation 1] and [manifestation 2]. [Conditional expansive-environment field/anchor/link sentence.]

Concentrate information at [high with retained rhythm], keep [medium] secondary, and leave [quiet watercolor fields] at [ceiling]; do not individually draw [compact non-drawing groups in suppressed zones]. Make [luminous carrier] oppose [dark anchor] through [chroma/value relations]. Let broad transparent color fields organize the whole frame. Use [primary mark with local pressure/interruption and visible job] only at [region] and nowhere in [excluded regions], then [secondary/subordinate marks]. Make selective watercolor visible through [broad application] and [precision/recognition application], without [global material failures].

Avoid [source-specific default prior and remaining unduplicated blockers]. Return one complete text-free reconstruction.
```

Do not recite field names or include brackets in the released prompt.

## Relation checks

### `living_identity`

- Preserve sparse identity plus source-supported action/contact before facial, anatomical, fur, feather, scale, or garment surface.
- `nonhuman_living_subject` must use species-specific source cues without humanizing anatomy or expression.
- `living_subject_in_expansive_scene` must keep one or two environmental fields, two or three functional anchor groups, at most two non-repeating exemplar cues per group, one subordinate setting family, and a readable link.

### `place_space`

- Keep gesture N/A.
- Preserve the selected route, opening, enclosure, room volume, threshold, built mass, repetition, light, or active-surface relation.
- Built space must merge repeated modules and avoid real-estate/architectural-visualization language.

### `object_event`

- Keep gesture N/A.
- Preserve minimum object/arrangement/use/event recognition and contact before labels, parts, ingredients, modules, or background inventory.
- Do not promise exact text, brand form, geometry, count, or color unless it is a feasible explicit lock.
- Block technical illustration, product-ad gloss, catalog staging, and exhaustive part rendering when applicable.

## Compiler limits

- Keep source orientation unless explicitly changed by the user; use EXIF-aware displayed orientation.
- No fixed 3:5, blank percentage, tiny cluster, typography, paper-aging, scan, halftone, xerox, collage, or token accent defaults.
- No artist or artwork reference and no other visual Skill.
- No vague render phrases.
- No duplicated prohibitions across paragraphs.
- Final prompt remains four compact paragraphs even when internal schemas are detailed.

## Required output

```yaml
compiled_prompt:
  compiler_version: "0.8"
  source_id:
  source_relation:
  relation_implementation:
  profile_id:
  recipe_version: "0.4"
  prompt_text:
  paragraph_count: 4
  coverage:
    source_contract:
    fidelity_locks:
    positive_shape_replacements:
    spatial_manifestations:
    information_and_non_drawing:
    structural_luminosity:
    ranked_marks_and_exclusions:
    material_system:
    default_prior:
  duplication_check:
    repeated_decisions: []
  blockers: []
```

## Compiler audit

Release only when every v0.4 recipe field is represented once; positive replacement precedes negative inventory; all mark priorities and exclusions are visible; retained local rhythm and suppressed inventory differ; broad watercolor fields govern the whole-frame read; source orientation is correct; exact locks are feasible; the material sentence is regional; paragraph count is four; duplication and blockers are empty; and no research, schema, artist, artwork, external Skill, poster, print, or vague style language remains.
