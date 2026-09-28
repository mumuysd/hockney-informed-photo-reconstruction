# Object and Event Grammar v0.1

## Scope and evidence boundary

Use this relation grammar when a nonliving object, product, food/still-life arrangement, machine, vehicle, use relation, or complex visible event is the indispensable subject. It inherits `00-intent-contract.md` and the cross-category decisions in `01-core-grammar.md`.

This is a user-authorized application extension, not a new finding from the twenty-work portrait/landscape corpus. Transfer only the abstract Core Grammar: relational subject selection, unequal information, dominant shapes, regional edges and marks, active quiet ground, role-based color, and coherent space. Do not cite object-specific behavior as artist evidence.

## Implementations

Choose exactly one:

```yaml
relation_implementation:
  - single_object
  - arranged_objects
  - object_in_use_or_vehicle
  - complex_event
```

- `single_object`: one object's silhouette, defining proportion, opening, joint, or functional relation carries recognition.
- `arranged_objects`: count, overlap, spacing, scale contrast, or contact makes the arrangement one subject.
- `object_in_use_or_vehicle`: object geometry and visible use/direction/contact are inseparable; the setting remains support.
- `complex_event`: several units form one visible event through direction, repetition, collision, exchange, queue, work, or another source-supported relation.

Route to `place_space` instead when architecture, route, enclosure, or environment remains the subject after the object is removed. Route to `living_identity` when a recognizable living subject and bodily action must survive. Never average profiles.

## OG-01 — Preserve recognition as a relational cue set

Declare only the minimum silhouette, proportion, joint, opening, count, arrangement, contact, direction, material break, or functional cue needed for recognition. A product label, logo, readable text, exact dimension, exact color, repeated feature, or engineering geometry is not a default invariant.

When the user explicitly locks exact geometry, branding, or readable text, record it under `user_locks`. Block before generation if the requested reconstruction would make that lock unreliable; do not claim that Imagegen can reproduce exact text or product geometry without inspection.

## OG-02 — Build three to five dominant carriers

Compress the object or event into three to five source-present carriers. A carrier may be a body mass, opening, handle/joint, container/content relation, grouped food mass, wheel/body relation, contact surface, movement corridor, or one merged event field.

Every carrier must state its visible simplification and forbidden individualization. Do not preserve complete buttons, labels, seams, spokes, windows, ingredients, packaging copy, machine parts, table inventory, or crowd units merely because they are visible.

## OG-03 — Keep function without technical illustration

Retain only contacts and geometry that explain how the subject stands, opens, carries, contains, rolls, pours, cuts, supports, moves, or interacts. Function is a visible relation, not permission for exploded views, diagram labels, exhaustive part rendering, or invented mechanisms.

## OG-04 — Treat arrangements and events as one subject

For multiple units, preserve the relation before individual objects: overlap, gap, rhythm, directional sequence, central exchange, repeated scale, or one interruption. Merge incidental units. If object count is explicitly locked, the count becomes a hard gate; otherwise preserve the arrangement logic rather than every unit.

## OG-05 — Allocate information by recognition and contact

Put high information only at one or two defining recognition/contact regions, medium information at supporting joints or arrangement boundaries, and keep broad body, ground, table, road, wall, or atmosphere fields quiet. Exact packaging copy, decorative texture, minor ingredients, machine fasteners, background shelves, street furniture, and repeated bystanders normally belong to non-drawing.

## OG-06 — Rank contour, structure, and material marks

Use two or three mark families with unequal priority:

- primary marks preserve the defining silhouette, opening, contact, or direction;
- secondary marks establish support, joint, arrangement, or event flow;
- subordinate marks provide one localized material or scale cue.

Every family declares `excluded_regions`. Do not use a universal outline around every object, ingredient, wheel, building, or person. A primary contour may remain incomplete when the adjacent color field already carries recognition.

## OG-07 — Use structural luminosity, not product gloss

Select one continuous in-scene luminous carrier and one smaller dark anchor. Keep one or two regions at highest chroma, with medium and restrained tiers elsewhere. Use color planes and transparent washes; do not substitute studio reflections, photographic cast shadows, uniform saturation, glossy advertising polish, white margins, or paper glow.

## OG-08 — Use selective contour-and-wash materiality

The matching material mode is `selective_contour_and_wash_object`:

- one broad object, table, road, wall, or atmosphere field uses a clean transparent wash or stain;
- one recognition/contact region uses a pointed line, compact wet deposit, dry interruption, selective overlap, or pooled boundary;
- quiet regions remain free of generalized blooms and global grain;
- material evidence cannot add undeclared seams, labels, ingredients, machine parts, or event units.

## Acceptance gate

Accept only when one implementation governs; the three-part core is complete with `gesture_pose: not_applicable`; three to five carriers replace inventory; exact locks are explicit and feasible; high/medium/quiet regions differ; non-drawing names source-present inventory; mark priorities and exclusions are complete; structural luminosity is relational; the material system covers a broad field and recognition/contact region; and no profile mixing, advertising identity, technical-diagram drift, or unverifiable fidelity claim remains.
