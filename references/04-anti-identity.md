# Anti-Identity v0.8

## Status

Anti-Identity defines detectable failures that contradict the recurring decision system or the user-authored application contract. `corpus-derived` means the failure is the inverse of stable reference evidence. `pilot-confirmed` and `ablation-confirmed` mean the failure also appeared in rejected generation work. `intent-contract-derived` means the failure violates `00-intent-contract.md` and is not presented as corpus evidence. These failures are diagnostic knowledge only; rejected positive operators remain ineligible for later Skill compilation.

## AI-01 — Generic watercolor filter

```yaml
failure_signature: "An unchanged photographic organization covered with washes, paper texture, looseness, or bright color."
violated_grammar: [CG-01, CG-03, CG-05, CG-08]
visible_symptoms: "Source hierarchy, spatial organization, and texture distribution remain photographic; only surface finish changes."
detection_question: "If the watercolor texture were removed, would any visual decision still be materially reconstructed?"
correction_direction: "Return to the branch render profile and rebuild the shape map, spatial manifestations, non-drawing contract, and region-specific mark jobs before any surface wording."
evidence_status: [corpus-derived, pilot-confirmed]
```

## AI-02 — Photographic composition left intact

```yaml
failure_signature: "The result repaints all source objects in the same framing, depth, scale, and informational order."
violated_grammar: [CG-01, CG-02, CG-03, CG-06, CG-08]
visible_symptoms: "No selective subject unit, no shape reorganization, no active omission, and no source-responsive spatial choice."
detection_question: "Does one coherent visual relation visibly reorganize at least two mutually reinforcing aspects of composition, space, proportion, dominant form, or information/omission without relying on texture or saturation?"
correction_direction: "Re-read the source, select the governing subject relation and recipe, then rewrite one reconstruction thesis instead of adding unrelated effects."
evidence_status: [corpus-derived, pilot-confirmed]
```

## AI-03 — Uniform information density

```yaml
failure_signature: "Every region is equally resolved, or detail is automatically concentrated only on the conventional focal object."
violated_grammar: [CG-02, CG-06]
visible_symptoms: "Background clutter survives, quiet fields disappear, or H14/H20-type density structures become impossible."
detection_question: "Are high-, medium-, and low-information regions visibly different, and is each density justified by function?"
correction_direction: "Choose an evidence-backed density pattern and restore low-information regions while retaining structural anchors."
evidence_status: [corpus-derived, pilot-confirmed]
```

## AI-04 — Uniform outline or texture vocabulary

```yaml
failure_signature: "The same contour, hatch, dot, wash, or paper effect covers face, clothing, road, vegetation, sky, architecture, and water."
violated_grammar: [CG-04, CG-05]
visible_symptoms: "Materials and visual jobs collapse into one decorative treatment; distant and quiet areas become overfilled."
detection_question: "Can each major mark family be named by a distinct geometry, location, and job?"
correction_direction: "Reduce the render recipe to two or three mark families, assign one geometry/region/job to each, and restore the categorical ceiling in quiet regions."
evidence_status: [corpus-derived, ablation-confirmed]
```

## AI-05 — One flattening rule for every source

```yaml
failure_signature: "Global compression, distortion, or plane quantization is applied regardless of the source's spatial cues."
violated_grammar: [CG-03, CG-08]
visible_symptoms: "Route recession, obstruction, repetition, enclosure, frontal alignment, and active surface are treated as interchangeable."
detection_question: "Which visible source cues selected this spatial system, and which cues must remain legible?"
correction_direction: "Choose one of the documented spatial systems from source evidence; use a hybrid only when both systems are visibly present."
evidence_status: [corpus-derived, ablation-confirmed]
```

## AI-06 — Uniform bright or pastel palette without hierarchy

```yaml
failure_signature: "Brightness, pastel harmony, or high saturation is distributed uniformly or through a fixed palette instead of a luminous carrier, smaller dark anchor, and three-level chroma hierarchy."
violated_grammar: [CG-07, intent_contract, luminous_color_system]
visible_symptoms: "All shapes become equally vivid or high-key; color no longer establishes attention, depth, figure-ground separation, route, enclosure, or scale."
detection_question: "Can one continuous luminous carrier, one smaller dark anchor, one or two high-chroma regions, and distinct medium/restrained regions each be identified by structural job?"
correction_direction: "Keep the user-authorized structural-luminosity default but redistribute chroma and value by named regional roles; remove equal saturation, fixed palettes, and global brightening."
evidence_status: [corpus-derived, intent-contract-derived]
```

## AI-07 — Landscape gesture fiction

```yaml
failure_signature: "Road, grass, cliff, ray, or water direction is counted as figure gesture."
violated_grammar: [portrait_branch_boundary, landscape_branch_boundary]
visible_symptoms: "Figure-pose rules are justified with non-figure marks or invented human action."
detection_question: "Is there a depicted figure with readable head, torso, limbs, contact, or interfigure evidence?"
correction_direction: "Record landscape direction under ATTENTION, SPACE, SHAPE, or MARK; keep GESTURE as N/A."
evidence_status: [corpus-derived]
```

## AI-08 — Sample-object leakage

```yaml
failure_signature: "Reference motifs such as braces, chairs, hay bales, roads, radial suns, water rings, sinks, fjords, flowers, or sheet seams appear without source need."
violated_grammar: [CG-01, CG-03, sample_residue_boundary]
visible_symptoms: "The output resembles a collage of remembered reference objects rather than a reading of the new source."
detection_question: "Does the source contain an equivalent object and structural function, or was the feature imported as a style signal?"
correction_direction: "Remove the motif and transfer only its abstract function when the source supports that function."
evidence_status: [corpus-derived]
```

## AI-09 — Portrait and landscape implementations averaged together

```yaml
failure_signature: "Face/gesture, route, enclosure, repetition, light event, and kinetic surface instructions are combined into one universal treatment."
violated_grammar: [CG-01, CG-08, branch_selection]
visible_symptoms: "The result has many stylistic signals but no coherent subject, spatial, density, or mark system."
detection_question: "Was exactly one applicable branch and one subject implementation selected before local treatment?"
correction_direction: "Select exactly one source_relation, relation_implementation, and matching profile; do not average living, place, and object/event profiles."
evidence_status: [corpus-derived, pilot-confirmed]
```

## AI-10 — Research dump used as an image instruction

```yaml
failure_signature: "Ten-dimension terminology, rule IDs, and long analytical prose are passed directly as a generation prompt."
violated_grammar: [selection_before_rendering]
visible_symptoms: "Instructions conflict, generic rendering priors dominate, and no visible thesis or ordered transformation is selected."
detection_question: "Can the intended result be summarized as one subject relation, one spatial system, one density pattern, and a few visible actions?"
correction_direction: "Keep these files as research references; compile source-specific actions only in the later reading/profile/compiler stages."
evidence_status: [pilot-confirmed]
```

## AI-11 — Source-relative claims without paired evidence

```yaml
failure_signature: "The analysis claims that real color was changed, camera perspective was transformed, or objects were deleted when only the finished artwork is known."
violated_grammar: [evidence_boundary]
visible_symptoms: "Interpretation is presented as observed fact and unsupported transformation rules enter the system."
detection_question: "Is there a verified source photograph or other paired evidence for this claim?"
correction_direction: "Restrict COLOR to finished-image relationships, DELETION to visible low-information or absence, and SPACE to visible organization."
evidence_status: [corpus-methodology]
```

## AI-12 — Identity core lost under reconstruction

```yaml
failure_signature: "Space, proportion, composition, color, or local form is changed so aggressively that the person, pair, subject, place, or governing landscape relation is no longer recognizable through the declared minimum cues."
violated_grammar: [intent_contract, preservation_core]
visible_symptoms: "The output is visually transformed but cannot be connected to the source without explanation, or recognition depends only on a generic object category."
detection_question: "Are the declared identity-core cues still visibly present without requiring photographic surface similarity?"
correction_direction: "Return to 07 when the core was misidentified, or revise the responsible domain role and visible carrier in 08 while preserving the successful parts of the thesis."
evidence_status: [intent-contract-derived]
```

## AI-13 — Gesture or pose lost, weakened, or invented

```yaml
failure_signature: "A portrait loses the source-defining head, body, contact, weight, or interfigure relation, or replaces it with a more dramatic invented pose."
violated_grammar: [intent_contract, portrait_branch_boundary]
visible_symptoms: "The sitter remains superficially recognizable but the action logic, balance, contact, or relationship that made the source distinctive disappears."
detection_question: "Do the minimum gesture/pose cues survive, and are all visible actions supported by the source?"
correction_direction: "Restore the declared gesture/pose core; revise the proportion or local-form carrier without reverting to full photographic anatomy. Landscapes remain N/A."
evidence_status: [intent-contract-derived]
```

## AI-14 — Scene idea or emotional relation replaced by effects

```yaml
failure_signature: "Objects remain recognizable, but the source's governing situation, distance, tension, intimacy, isolation, enclosure, calm, or activity is replaced by decorative color, distortion, or generic mood."
violated_grammar: [intent_contract, CG-01, CG-02, CG-03]
visible_symptoms: "The result can be described only as an inventory or style effect; the relational sentence defined in scene_idea no longer fits."
detection_question: "Can the same scene-idea sentence and evidence-backed emotional relation describe the source and candidate?"
correction_direction: "Return to the subject relation and redistribute composition, space, proportion, information, and color around the declared scene idea."
evidence_status: [intent-contract-derived]
```

## AI-15 — Minimal-zine or poster identity leakage

```yaml
failure_signature: "The reconstructed photograph becomes a sparse editorial poster through a tiny isolated subject, fixed blank margins, typography, collage fragments, halftone/xerox effects, or one token accent color."
violated_grammar: [intent_contract, CG-01, CG-03, CG-06, CG-07]
visible_symptoms: "The source scene is reduced to a poster event; active quiet ground becomes decorative paper area; visual identity comes from layout or reproduction effects rather than observed space, shape, color, edge, mark, and deletion."
detection_question: "Would the image still belong to this reconstruction system if all typography, paper-aging, collage, and print effects were removed?"
correction_direction: "Restore the source-responsive scene relation and use low-information areas inside the reconstructed scene; remove poster layout, text, tiny-subject scaling, and reproduction-effect identity."
evidence_status: [implementation-boundary-derived]
```

## AI-16 — Descriptive completeness disguised as simplification

```yaml
failure_signature: "The result removes a little texture or background clutter but still individually describes nearly every leaf, grass blade, rock, wave, facial plane, hair strand, garment fold, fixture, or room object."
violated_grammar: [CG-02, CG-03, CG-05, CG-06, render_profile, render_recipe]
visible_symptoms: "The image can still be inventoried like the photograph; large shapes are subdivided into many local forms; the declared quiet field is continuously modeled; simplification exists only as softer finish."
detection_question: "Did three to five dominant carriers actually replace source inventory, and is every item in the non-drawing contract visibly merged, omitted, left open, or represented only as a mass?"
correction_direction: "Return upstream and rebuild the shape map and non-drawing contract. Name the forbidden individualization for every carrier and lower the quiet-region mark ceiling; do not repair this by adding another style adjective."
evidence_status: [corpus-derived, user-confirmed-generation-failure]
```

## AI-17 — Structural simplification rendered as materially generic digital paint

```yaml
failure_signature: "Space, shape, hierarchy, or deletion improves, but the result is rendered with opaque digital oil/gouache strokes, smooth fills, or materially neutral surfaces that contain no regional watercolor behavior."
violated_grammar: [CG-04, CG-05, intent_contract, render_profile, material_system]
visible_symptoms: "Transparent underlayers are absent; brush pressure, wash overlap, pigment pooling, dry interruption, and exposed or thinly washed ground cannot be located; or fake paper grain is the only watercolor cue."
detection_question: "After ignoring any uniform paper texture, can at least one broad field and one precision/anchor region be identified by different, declared watercolor applications and visible pigment evidence?"
correction_direction: "Return to the render profile and add a branch-matching material system. Assign transparent wash behavior to a broad field and a pointed, wet, dry, pooled, or concentrated pigment behavior to a precision/anchor region without changing the accepted structural thesis or adding global texture."
evidence_status: [intent-contract-derived, user-confirmed-generation-failure]
```

## AI-18 — Environmental inventory takeover

```yaml
failure_signature: "A small but indispensable portrait figure is surrounded by an environment that expands into more than two carriers or a repeated inventory of buildings, windows, roofs, rail subdivisions, vegetation, signs, or street furniture beyond the budgeted representative cues."
violated_grammar: [intent_contract, living_identity, living_subject_in_expansive_scene, render_recipe]
visible_symptoms: "The setting can be counted object by object at thumbnail size; repeated setting marks dominate; the person becomes a generic scale dot; or environment detail is clearer than the figure gesture and figure-environment link."
detection_question: "Does the setting read first as one or two continuous fields and grouped place identity, with only two or three functional anchor groups and non-repeating exemplar cues, while the figure remains identifiable and gesturally specific?"
correction_direction: "Return to the portrait render handoff. Keep one or two environment carriers, two or three anchor groups, at most one or two recognition-critical exemplars inside a group, one subordinate setting mark family, and merge the remaining inventory explicitly."
evidence_status: [intent-contract-derived, user-confirmed-generation-failure]
```

## AI-19 — Structural luminosity collapse

```yaml
failure_signature: "The result is chromatically timid and muddy, uniformly saturated, lit by continuous photographic shadows, or made to glow through white margins or paper texture rather than color-plane relations."
violated_grammar: [intent_contract, luminous_color_system, material_system]
visible_symptoms: "No clear luminous carrier or smaller dark anchor exists; high/medium/restrained chroma tiers collapse; value and chromatic contrasts lack structural jobs; washes are gray from repeated mixing; or a white vignette supplies the only apparent light."
detection_question: "After ignoring paper texture and margins, do clean transparent color planes still produce one luminous field, one smaller deep-color anchor, and both value and warm-cool/complementary contrast?"
correction_direction: "Rebuild the luminous-color system and its regional material applications. Use one clean high-chroma transparent field, one transparent deep-color anchor, controlled supporting chroma, and color-plane shadows without changing the accepted structural thesis."
evidence_status: [intent-contract-derived, user-confirmed-generation-failure]
```

## AI-20 — Destructive over-simplification

```yaml
failure_signature: "Deletion removes the middle layer needed to recognize the subject or relation, leaving generic blobs, isolated symbols, or an empty category cue."
violated_grammar: [intent_contract, preservation_core, shape_map, non_drawing_contract]
visible_symptoms: "A village becomes unrelated hills and tokens; a person becomes a dark cutout; an object loses the few joins that explain how it is built or used; the result needs the source caption to be understood."
detection_question: "After removing repeated inventory, do the declared identity, action, place, or use-relation cues still form a readable whole at thumbnail and full view?"
correction_direction: "Keep the carrier count and non-drawing contract, but restore a minimum legibility layer: grouped contour rhythm, necessary joins, plausible silhouette, and the relation-specific cues declared in the source contract. Do not restore repeated inventory."
evidence_status: [intent-contract-derived, user-confirmed-generation-failure]
```

## AI-21 — Living-subject morphology drift

```yaml
failure_signature: "A living subject remains categorically present but acquires implausible or source-unsupported anatomy, proportions, face direction, limb length, contact, or weight."
violated_grammar: [identity_core, gesture_pose, living_identity, local_form]
visible_symptoms: "The figure looks strange, mannequin-like, elongated, fused, dislocated, or generically substituted even though clothing colors or pose labels survive."
detection_question: "Are head, torso, limb joins, weight-bearing support, and source-defining silhouette plausible and consistent with the source before expressive line or color is considered?"
correction_direction: "Return upstream. Preserve plausible source-supported morphology as a hard carrier constraint; let wash edges simplify surface detail and reserve fine lines for emphasis rather than using sparse lines to rescue broken anatomy."
evidence_status: [intent-contract-derived, user-confirmed-generation-failure]
```

## AI-22 — Source-relation or profile mixing

```yaml
failure_signature: "A recipe selects more than one source_relation or combines living, place, and object/event profiles to cover ambiguity."
violated_grammar: [source_relation, relation_implementation, render_profile]
visible_symptoms: "Conflicting shape, gesture, fidelity, density, or material rules appear; no single governing relation controls the image."
detection_question: "Can exactly one source_relation and one matching profile explain what must survive and what may be rewritten?"
correction_direction: "Route by the indispensable relation. If two relations are equally indispensable and no governing relation can be chosen from the source and user locks, block and ask before compilation."
evidence_status: [implementation-contract-derived]
```

## AI-23 — Unranked or cross-region mark reuse

```yaml
failure_signature: "Primary identity contours, secondary structural lines, and tertiary material marks are treated as equal or reused across excluded regions."
violated_grammar: [mark_map, information_budget, material_system]
visible_symptoms: "Environment marks compete with a face or object join; the same fine contour enters sky, vegetation, figure, and architecture; quiet regions gain decorative activity."
detection_question: "Does every mark family have a unique priority, named region, visible job, and excluded_regions list, and does the output obey those boundaries?"
correction_direction: "Rank mark families before material compilation; reserve priority 1 for the governing relation, subordinate priority 2, constrain priority 3 to local material evidence, and remove cross-region reuse."
evidence_status: [implementation-contract-derived, user-confirmed-generation-failure]
```

## AI-24 — Implicit exact-fidelity promise

```yaml
failure_signature: "The system silently treats product geometry, readable text, logo, count, or precise building detail as exact, or proceeds after an explicit exact lock conflicts with reconstructive rendering reliability."
violated_grammar: [fidelity_locks, preflight, source_evidence_boundary]
visible_symptoms: "Approximate text is presented as exact; a brand mark is invented; technical geometry drifts despite a promised lock; or reconstruction becomes a disguised product or architectural reproduction task."
detection_question: "Did the user explicitly request the exact lock, and was feasibility confirmed before generation?"
correction_direction: "Default exact fidelity to unlocked. When explicitly requested, run preflight and block before generation if the lock cannot be met reliably alongside the reconstruction contract."
evidence_status: [implementation-contract-derived]
```

## Hard gate

Any output that reads primarily as generic watercolor or minimal-zine/poster design, preserves photographic organization without coherent reconstruction, retains descriptive completeness or destroys minimum legibility despite a simplification claim, distorts living morphology, mixes source relations or profiles, permits environmental inventory takeover, flattens mark priorities, lacks structural luminosity or regional watercolor materiality, imports reference motifs, loses any applicable part of the three-part preservation core, makes an unsupported exact-fidelity promise, or violates the source-evidence boundary fails regardless of technical polish or numeric score.
