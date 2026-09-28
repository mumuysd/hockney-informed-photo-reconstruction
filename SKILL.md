---
name: hockney-informed-photo-reconstruction
description: Reconstruct one supplied real photograph of a living subject, place, object, product, vehicle, still life, or visible event through a source-specific selective-watercolor recipe with dominant-shape compression, explicit non-drawing, structural luminosity, ranked regional marks, and controlled pigment behavior. Use for direct photo reinterpretation or, only when explicitly requested, a final image prompt; do not use for screenshots, documents, charts, artwork inputs, generic watercolor filters, opaque digital repainting, poster layouts, or reference-art copying.
---

# Hockney-Informed Photo Reconstruction

Treat the photograph as evidence for minimum recognition and relation, not as an untouchable camera template. Preserve `identity_core`, applicable `gesture_pose`, and `scene_idea`; permit space, proportion, composition, color, and local form to be rewritten as one coherent act of selective observation.

Application revision `expressive-watercolor-v1` keeps watercolor fields, structural color, and spatial reconstruction dominant at whole-frame scale; localized lines carry pressure, rhythm, expression, and contact at close view. The transferred drawing judgments are user-authorized application rules, not additional findings from the research corpus. Their complete contract lives in the **Localized expression** section of `references/render-profiles.md`; no second visual Skill is required at runtime.

Contract clarification `acceptance-contract-v1` governs request conflicts and candidate delivery; it does not change visual thresholds or historical outcomes. See **User locks and precedence** in `references/00-intent-contract.md` and **Decision states and delivery** in `references/10-quality-gate.md`.

The executable prompt must describe visible behavior without naming an artist, citing corpus works, invoking another visual Skill, or asking Imagegen to imitate a reference artwork. Keep Visual Plan and recipe schemas internal unless the user explicitly asks to inspect them.

## Route the request

- **Direct Generate — default:** one real photograph → internal reading → one relation → one recipe → one built-in Imagegen edit → actual-raster inspection.
- **Prompt Only:** only when the user explicitly asks for a prompt and no image.
- **Analysis Only:** only when the user asks to inspect or explain a source without generating.

Work on one photograph per generation cycle. Default to the source's displayed orientation and text-free output. Do not adopt fixed poster ratios, whitespace percentages, typography, scan effects, or paper-aging identity.

Choose exactly one `source_relation`:

- `living_identity`: an individually recognizable human or nonhuman living subject, pose, contact, or group relation is indispensable;
- `place_space`: an outdoor place, built space, route, opening, enclosure, repeated field, active surface, or environmental event supplies the governing relation;
- `object_event`: an object, product, food/still-life arrangement, machine, vehicle, use relation, or complex visible event is primary.

If a living subject is only a replaceable scale cue, use `place_space`. If place is merely support for an indispensable object or vehicle relation, use `object_event`. Never average profiles. If two relations cannot be ranked without violating an explicit user lock, block and ask which core governs.

## Load references progressively

1. Read `references/00-intent-contract.md` for every request.
2. Inspect the source, then read `references/07-hockney-reading.md`.
3. While deconstructing, read `references/01-core-grammar.md`, `references/02-variables.md`, and exactly one relation grammar:
   - `references/05-portrait-grammar.md` for `living_identity`;
   - `references/06-landscape-grammar.md` for `place_space`;
   - `references/object-event-grammar.md` for `object_event`.
4. Read only the matching profile in `references/render-profiles.md`: `portrait_sparse_identity`, `landscape_economical_open_field`, or `object_event_selective_structure`.
5. Consult `references/03-sample-residue.md` and `references/04-anti-identity.md` before accepting the reading.
6. Read `references/08-interpretation-profile.md` to form one thesis and one `render_recipe` v0.4.
7. Read `references/09-prompt-compiler.md` to compile that recipe into one compact four-paragraph prompt.
8. Read `references/runtime-execution.md` immediately before Imagegen.
9. Read `references/10-quality-gate.md` before returning or revising the raster.

Development evidence is not part of this runtime package.

## Preserve only the three-part core

- `identity_core`: the minimum cues that keep the living subject, object, product, place, route, enclosure, event, arrangement, or active surface recognizable;
- `gesture_pose`: the minimum source-supported bodily action, weight, contact, or interfigure relation for `living_identity`; otherwise `not_applicable`;
- `scene_idea`: one relational sentence plus its visible emotional, functional, or environmental relation.

Exact geometry, branding, readable text, architectural detail, product labels, local color, perspective, scale, and background inventory are not locks unless the user explicitly requires them. This includes broad requests such as “keep everything else unchanged.” If a lock cannot coexist with visible reconstruction or reliable Imagegen output, name the conflict and ask which requirement may change before generation; style wording does not override a preservation request.

## Build one render recipe

Use `render_recipe` v0.4 with one `source_relation`, one matching `relation_implementation` and profile, three to five source-present dominant carriers, one structural driver with at least two visible manifestations, an explicit non-drawing contract, a complete `luminous_color_system`, regional edge roles, two or three ranked mark families, and one matching watercolor material system.

Every carrier states its visible simplification and forbidden individualization. Marks declare `priority` and `excluded_regions`; the primary family may not spread into excluded or quiet regions. Translate watercolor intent into regional evidence such as a transparent wash, selective overlap, pressure-changing pointed line, compact wet deposit, dry interruption, pooled boundary, or exposed ground. Vague requests for natural painting, appropriate simplification, painterly feeling, or generic looseness are not renderable.

Inside those same fields, name the focal rhythm to retain, the repeated inventory to suppress, and the broad watercolor regions to keep quiet in the reconstructed composition. Preserve source-supported expression, useful contour rhythm, and necessary joins without a universal facial-feature or line-count ceiling. Neither mechanical repetition nor a sterile, over-pruned focal region passes. Do not import source-coordinate locks, a black-gray base, a two-accent limit, dry-only material, or whole-image line dominance.

Structural luminosity remains the default unless an explicit source-specific lock requests restrained or near-monochrome color: one continuous in-scene luminous carrier, one smaller dark anchor, one or two high-chroma regions, non-empty medium and restrained tiers, value contrast, and warm-cool or complementary contrast. No uniform brightening, equal saturation, photographic shadow modeling, white-margin glow, or global paper grain.

For `living_subject_in_expansive_scene`, keep one or two environmental carriers and two or three functional anchor groups. An anchor group may retain one or two representative place cues when they are necessary for recognition, but those cues must not repeat into an inventory. Merge the remaining setting into continuous fields. When a route/support is already a carrier, all other setting and atmosphere fit into one combination carrier.

## Generate directly

Use the original photograph as the sole visual input to built-in Imagegen. Use `referenced_image_paths` for local sources or the smallest valid `num_last_images_to_include` when the source exists only in conversation; never use both.

Do not create staged proofs, controls, blind boards, manual composites, generation scripts, or external API workflows. Do not pass corpus artworks, rejected outputs, poster references, or unrelated Skill assets to Imagegen.

## Inspect and revise

Inspect full view and thumbnail. Fail unless:

- the three-part core and chosen `source_relation` survive;
- camera organization is visibly reconstructed through at least two mutually reinforcing structural changes;
- three to five dominant carriers replace inventory;
- high, medium, and quiet information regions differ;
- the non-drawing contract is visibly executed rather than blurred;
- primary, secondary, and subordinate marks remain geometrically and regionally distinct;
- local pressure and rhythm retain expression, spatial depth, or contact without becoming equal-weight repetition, global outlines, or empty schematic symbols;
- transparent broad fields and localized pigment/brush events make watercolor materiality visible without global paper texture;
- structural luminosity remains relational rather than uniformly bright;
- no profile mixing, invented subject, copied motif, poster identity, text, or print effect appears.

Allow one targeted revision only after the direction passes and exactly one localized repair remains. Multi-carrier failure, generic watercolor, descriptive completeness, absent mark hierarchy, failed non-drawing, failed materiality, or user rejection returns upstream.

After an eligible revision, compare both rasters against all gates. Reject a revision that loses a passing core, watercolor field, quiet region, expression, depth, or rhythm. Fewer marks alone never justify revision or candidate selection; retaining a flawed initial candidate does not erase its failed gates.

## User-facing output

For Direct Generate, follow the quality gate's delivery table: a candidate may be shown or retained with its visible limitations while its quality decision remains `fail`. User acceptance alone neither passes the quality gate nor authorizes another generation cycle. For Prompt Only, return the final four paragraphs without implying generation or inspection. Keep delivery brief and reveal internal schemas only when requested.

This package is a v1.0 generalization candidate. Its loadability and packaging do not establish generalization or image-quality validation.
