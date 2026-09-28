# Direct Runtime Execution Contract v0.7

## Purpose

Execute one accepted v1.0 recipe through built-in Imagegen, inspect the actual raster, and permit at most one evidence-backed targeted revision.

```text
original real photograph
→ accepted source reading v0.6
→ accepted interpretation v0.7 / render_recipe v0.4
→ accepted compiler output v0.8
→ one direct Imagegen edit
→ full-view and thumbnail inspection
→ optional single targeted revision
```

## Modes

- `direct_candidate`: default for a supplied photograph and transformation request.
- `targeted_revision`: only after direction acceptance, complete preservation, overall recipe presence, and exactly one localized repairable failure.
- `prompt_only`: no Imagegen call and no generation claim.
- `analysis_only`: no Imagegen call.

## Tool and input policy

1. Use built-in Imagegen only.
2. For a readable local source, use `referenced_image_paths`; for a conversation-only source, use the smallest valid `num_last_images_to_include`; never both.
3. The original photograph is the sole visual input for a direct candidate.
4. Inspect metadata/EXIF and use the displayed orientation unless explicitly overridden.
5. Do not pass corpus art, artist portraits, style references, rejected candidates, poster references, or other Skill assets.
6. Do not invoke or dynamically merge another visual-generation Skill at runtime. The localized-expression methods already integrated in `render-profiles.md` are part of this package, not a dependency on the donor Skill or its assets.
7. Send the accepted four-paragraph prompt without artist names, schema terms, style references, fixed poster defaults, or wrapper instructions that alter it.

## Preflight

```yaml
runtime_preflight:
  runtime_version: "0.7"
  source_available:
  source_inspected:
  displayed_orientation_verified:
  source_relation:
  relation_implementation:
  profile_match:
  source_contract_complete:
  fidelity_locks_feasible:
  recipe_version: "0.4"
  recipe_complete:
  positive_replacements_complete:
  spatial_manifestations_complete:
  non_drawing_complete:
  expansive_environment_gate: [passed, not_applicable]
  structural_luminosity_complete:
  ranked_marks_complete:
  mark_exclusions_complete:
  material_mode_match:
  prompt_four_paragraphs:
  prompt_duplication_empty:
  prompt_blockers_empty:
```

Block execution when any required field fails; when exact geometry/text/brand/count locks are incompatible; when relation/profile/material mode mismatch; when there are fewer than three or more than five carriers; when marks lack unequal priority or excluded regions; when expansive-environment fields are incomplete; or when the prompt contains vague, artist, artwork, external-Skill, poster, print, or duplicated instructions.

## Direct candidate

Send the exact accepted prompt. The wrapper may state only that Image 1 is the sole edit target and visual source if that role is not already present.

When saving project-bound artifacts, choose an output directory for the current task and keep the generated raster, prompt, and record together. No bundled validation directory is required.

The record contains source hash, displayed orientation, recipe and prompt hashes, generated identifier, project output hash/dimensions, relation/profile/material versions, quality decision, and user-direction status. Prompt hashes use prompt text with trailing CR/LF removed. A new direct candidate from the original has no parent output and `revision_attempt: 0` even when its display ID follows an earlier failed version.

For the integrated application also record `application_revision: expressive-watercolor-v1` and hashes of the runtime instructions used. Existing wire versions are unchanged; the application revision identifies the new behavioral rules. Historical generation records are never rewritten.

For runs using this clarification, also record `contract_revision: acceptance-contract-v1`. It identifies conflict/delivery handling only; visual gate thresholds and the existing wire versions are unchanged.

## Inspect actual output

Read `10-quality-gate.md`. Inspect full view for identity/recognition, exact locks, line/mark hierarchy, pigment evidence, and forbidden inventory. Inspect thumbnail for governing relation, carrier count, field-before-anchor order, information hierarchy, active quiet ground, and structural luminosity.

Do not declare a candidate passed from prompt compliance alone.

For this application, explicitly inspect both mechanical repetition and destructive over-pruning, compare retained rhythm with suppressed zones, and confirm that local line expression remains subordinate to broad watercolor fields. Record unknown evidence as unresolved rather than manufacturing a pass.

## Single targeted revision

Revision is allowed only when:

- the user explicitly accepts the direction;
- relation, three-part core, feasible locks, thesis, and overall recipe survive;
- exactly one localized failure can be repaired without changing carriers, structural driver, information hierarchy, or profile identity.

Repeat every locked invariant and state one change. Use candidate as edit target and original as preservation reference only when supported. If failure spans several carriers, inventory, marks, materiality, or user direction, return upstream instead of revising. Never make a second revision automatically.

Use the `LOCK / REPAIR / DO NOT CHANGE` structure and the candidate comparison in `10-quality-gate.md`. Protect useful expression, spatial cadence, contact, and quiet watercolor fields alongside other passing properties. Fewer marks alone are not a repair. If the revision loses those properties, retain the initial candidate with its actual limitations; do not upgrade a failed candidate to a pass.

## Output

Follow **Decision states and delivery** in `10-quality-gate.md`: showing or retaining a failed candidate does not upgrade its quality decision, and acceptance alone does not start a new generation cycle. Keep internal prompts, records, rule IDs, and technical scores hidden unless requested. Prompt-only output contains the four paragraphs and does not imply generation or inspection; unresolved preservation/reconstruction conflicts must be resolved first under `00-intent-contract.md`.
