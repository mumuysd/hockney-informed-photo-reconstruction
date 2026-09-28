# Living-Identity Grammar v0.4

## Inheritance and scope

This relation grammar inherits all eight rules in `01-core-grammar.md`. Its human-portrait decisions are supported by H02, H08, H09, H13, H15, H17, and H19. Nonhuman living subjects and expansive-environment use are user-authorized extensions, not new corpus findings. A reconstruction must first read the actual living subject, pose/action, viewpoint, and support relations; it must not import a pose, anatomy, species cue, or object from the corpus.

Use `source_relation: living_identity` with exactly one implementation:

```yaml
relation_implementation:
  - single_living_subject
  - grouped_living_subjects
  - viewing_or_action_encounter
  - nonhuman_living_subject
  - living_subject_in_expansive_scene
```

Historical v0.3 mappings are preserved only in old records: `single_sitter`, `paired_relationship`, `viewing_encounter`, and `portrait_in_expansive_scene`.

For application to a new source, inherit the three-part preservation core from `00-intent-contract.md`. `identity_core` and `gesture_pose` are separate locks: a recognizable face cannot compensate for a lost body relation, and a preserved pose cannot compensate for lost identity. `scene_idea` carries the evidence-backed interpersonal or person-environment emotional relation. Space, proportion, composition, color, and local form may be rewritten around these locks.

## PG-01 — Classify the portrait subject unit before distributing emphasis

```yaml
branch_decision: "Choose single sitter, paired relationship, or reflected/viewing-apparatus encounter as the subject unit."
dimensions: [ATTENTION, SUBJECT]
evidence: "H08/H09/H17 single sitter; H02/H13/H19 paired relationship; H15 reflected head plus sink/mirror divider."
selection: "Use the unit supported by scale, placement, gaze, posture contrast, value/color contrast, and viewing apparatus."
limit: "Do not make the face the complete subject when pose, pairing, or viewpoint is structurally inseparable from identity."
```

### Implementations

- **Single sitter:** couple the face with the strongest pose or framing relation. H08 uses face plus raised-arm silhouette; H09 uses frontal face inside a scarf/backdrop frame; H17 uses face plus leaning action and brush hand.
- **Paired portrait:** treat the relationship as one subject. Compare contained/expansive, upright/leaning, closed/open hands, dark/pale bodies, and shared seating rather than rendering two unrelated individuals.
- **Viewing encounter:** allow apparatus and viewpoint to share subject status. H15 binds enlarged reflected eyes, divider, basin, and fixtures into one encounter.

## PG-02 — Preserve identity through a distributed anchor set

```yaml
branch_decision: "Select a small set of identity anchors across face, head, silhouette, gesture, contact, clothing division, and support."
dimensions: [ATTENTION, GESTURE, DETAIL_HIERARCHY, EDGE]
evidence: "All seven portraits concentrate facial information, but H08/H17 require action silhouette, H02/H13/H19 require posture and contact, and H15 requires viewpoint/apparatus."
selection: "Keep only anchors needed to distinguish this sitter or pair; assign the firmest edges and highest information to those anchors."
limit: "Identity is not equivalent to complete facial rendering, and non-source clothing or accessories cannot be added as identity shorthand."
```

Possible anchors include eye/glasses geometry, head angle, hair mass, mouth/nose relation, shoulder direction, arm silhouette, hand closure or action, leg/foot placement, chair contact, or one source-present clothing division. The set must remain sparse enough for surrounding incompletion to stay visible.

## PG-03 — Select one evidence-backed gesture mode

```yaml
branch_decision: "Choose strong action silhouette, paired relational gesture, low frontal gesture, or viewpoint/head action."
dimensions: [GESTURE, ATTENTION, SUBJECT, SHAPE]
evidence: "H08/H17 strong action; H02/H13/H19 paired relation; H09 low frontal; H15 viewpoint/head action."
selection: "Read head, torso, arms/hands, legs/feet, weight/contact, and interfigure relation separately, then weight only what is actually visible."
limit: "Do not invent missing hands, feet, body action, or interpersonal narrative."
```

- **Strong action silhouette:** the gesture changes the outer mass or creates a second attention anchor.
- **Paired relational gesture:** posture and contact contrast differentiate two sitters inside the same stage.
- **Low frontal gesture:** gaze and facial line dominate; unresolved arms or hands remain low information.
- **Viewpoint/head action:** head position and viewing apparatus replace a full-body gesture record.

## PG-04 — Convert anatomy into a small relational shape system

```yaml
branch_decision: "Construct the figure from nested, interlocking, paired, or stacked body/support masses before anatomical description."
dimensions: [SHAPE, SUBJECT, SPACE]
evidence: "H08 interlocking diagonal figure; H09 nested bilateral frame; H15 stacked head/apparatus zones; H17 head within arm arch; H02/H13/H19 paired contrasting body blocks."
selection: "Retain silhouette, weight direction, interfigure gap, and support contact in three to five dominant shapes."
limit: "Do not trace every anatomical contour or simplify the sitter into a generic oval-and-torso icon."
```

Small shapes such as hands, glasses, shoes, jewelry, chair joints, fixtures, or tools may punctuate the system only when they carry identity, weight, relation, or viewpoint.

## PG-05 — Concentrate detail locally and asymmetrically

```yaml
branch_decision: "Choose identity, paired identity/support, or identity-plus-action/viewpoint as the portrait density pattern."
dimensions: [DETAIL_HIERARCHY, EDGE, DELETION]
evidence: "H09 confines high information almost entirely to the face; H08 adds the arm junction; H15 and H17 add apparatus or action; H02/H13/H19 distribute precision across two faces, hands, feet, and supports."
selection: "State high-, medium-, and low-information regions; allow different sitters or different body zones to receive unequal resolution."
limit: "Do not fully render a photographic face against a merely stylized background, and do not distribute equal facial, garment, furniture, and room detail."
```

Lost or open garment boundaries are permitted when identity and posture remain intact. H09 and H13 show that pale body regions can dissolve while facial or relational anchors stay specific.

## PG-06 — Choose between a shallow shared stage and a compressed encounter

```yaml
branch_decision: "Use a shallow shared stage for seated/full-figure relations or a compressed encounter for close viewpoint/apparatus relations."
dimensions: [SPACE, SHAPE, EDGE]
evidence: "H02/H08/H09/H13/H19 shallow stages; H15/H17 compressed encounters."
selection: "Preserve the minimum floor, wall, chair, divider, overlap, or scale cues required to orient the body and subject relation."
limit: "Do not develop an unnecessary descriptive room and do not apply generic perspective distortion."
```

Four-sheet joins visible in H02, H13, and H19 belong to physical support evidence, not to mandatory portrait composition. They remain absent unless the intended support genuinely uses assembled sheets.

## PG-07 — Retain support objects only when they prove posture or viewpoint

```yaml
branch_decision: "Reduce chairs, floor bands, counters, basins, dividers, and tools to the parts that establish weight, contact, action, scale, or viewing position."
dimensions: [SUBJECT, SPACE, MARK, DELETION]
evidence: "Chair mechanics locate H02/H08/H13/H19; brush and table boundary support H17; sink/divider/fixtures construct H15; H09 needs little developed support."
selection: "For each support, name its retained function and omit unrelated inventory."
limit: "Do not copy a chair, sink, brush, or room arrangement from another work; do not delete the contact point that makes the pose believable."
```

## PG-08 — Separate portrait color, edge, and mark jobs

```yaml
branch_decision: "Choose a portrait color mode, then assign distinct edge and mark jobs to identity, body mass, support, and ground."
dimensions: [COLOR, EDGE, MARK]
evidence: "H02/H09/H13/H19 muted differentiation; H08/H17 stronger figure-ground zoning; H15 near-monochrome. Fine identity lines coexist with broad body/ground fields and selected support geometry."
selection: "Use color to separate sitters or body/ground zones; use firm edges at chosen identity/contact nodes; use broader or open treatment elsewhere."
limit: "Do not default to bright color, universal dark outline, or one wash/hatch vocabulary. Source-color change remains unknown."
```

This limit describes the corpus evidence boundary: brightness is not a universal finding from the seven works. The user-authorized `structural_luminosity` default in `00-intent-contract.md` and `render-profiles.md` governs runtime output while still requiring regional chroma hierarchy rather than uniform brightness.

## Portrait coverage ledger

| Work | Subject mode | Gesture mode | Spatial mode | Density mode |
|---|---|---|---|---|
| H02 | paired relationship | paired relational | shallow shared stage | paired identity/support |
| H08 | single sitter plus pose | strong action silhouette | shallow shared stage | identity plus gesture anchor |
| H09 | frontal single sitter | low frontal | shallow field/stage | extreme local identity |
| H13 | paired relationship | paired relational | shallow shared stage | asymmetric paired identity/support |
| H15 | viewing encounter | viewpoint/head action | compressed encounter | identity plus apparatus |
| H17 | single sitter plus action | strong action silhouette | compressed encounter | identity plus action |
| H19 | paired relationship | paired relational | shallow shared stage | paired identity plus clothing/support |

All seven figure works are represented. Landscape direction is never used as gesture evidence in this branch.

## User-authorized application extension — `living_subject_in_expansive_scene`

This implementation handles a small but indispensable living subject inside a large environment. It is authorized by the user's application intent and source-photo validation, not promoted as new corpus evidence. It remains inside `living_identity`.

```yaml
source_relation: living_identity
relation_implementation: living_subject_in_expansive_scene
selection_cues:
  - "the living subject remains individually recognizable"
  - "head, body, gait, posture, or species-specific action relation cannot be removed"
  - "removing the living subject fundamentally changes scene_idea"
  - "the large environment supplies scale, exposure, movement, isolation, or destination"
place_boundary: "Use place_space instead when the living subject is replaceable scale evidence and no identity or specific pose must survive."
gesture_boundary: "Environment direction remains SPACE, SHAPE, EDGE, or MARK; it never becomes GESTURE."
```

### Carrier budget

Use three to five dominant carriers total:

1. head, face, ears, cap, hair, muzzle, or another small identity shape;
2. torso, body, wing, forelimb, or arm action mass;
3. leg, paw, foot, tail, contact, or movement direction;
4. a path, railing, furniture, or comparable figure-environment link;
5. one environmental combination field.

The first three may merge into two carriers when the figure is simple. The environment may occupy one or two carriers only. If a route or support already occupies one carrier, all remaining buildings, terrain, vegetation, and atmosphere must merge into one combination field.

### Environmental compression

- Retain exactly two or three functional anchor groups across the setting.
- An anchor group primarily preserves mass, contour, placement, direction, or value. It may include one or two representative place-identity cues when the grouped place would otherwise become generic, but the cue cannot repeat as a window, roof, facade, fixture, foliage, or object inventory.
- Repeated windows, roof tiles, facade units, rail subdivisions, leaves, grass, signs, street furniture, and separate buildings must be merged, omitted, left open, or represented only as one field.
- The environment uses at most one subordinate mark family. At thumbnail size the carrier fields and grouped place identity must read before individual anchor cues; representative cues may not become the first read.
- The living subject must remain a readable identity-and-gesture unit rather than a generic place scale cue.

This extension does not authorize environment invention, profile averaging, or a descriptive background. Its success depends on the living-subject/environment relation, not on recognizing every location object.

## User-authorized application extension — `nonhuman_living_subject`

Use this implementation only when an animal or other living subject remains individually recognizable and its species-specific silhouette, head/body relation, markings, posture, gait, contact, or interaction is indispensable.

- Build identity from a sparse distributed set such as head profile, ear/eye/muzzle geometry, body proportion, tail or wing direction, limb contact, distinctive marking division, and one support relation.
- Preserve action logic without converting it into human anatomy or expression.
- Keep fur, feathers, scales, whiskers, spots, and background inventory merged or localized; they cannot become uniform texture.
- Use one primary contour/identity mark family only at defining head, contact, or action junctions; exclude it from broad body and setting fields.
- This extension remains behaviorally unvalidated until A01 passes without importing new rules.
