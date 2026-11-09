# Statistics of archetype library SPLASH-adl2_template

## Compilation

| Metric | Count |
| --- | --- |
| Valid archetypes | 40 |
| Specialised archetypes | 21 |
| Client archetypes | 12 |
| Supplier archetypes | 16 |
| Total archetypes | 40 |

## Terminology bindings

| Terminology | Archetypes |
| --- | --- |
| openehr | 2 |

## Reference model org.openehr:healthcare

### Archetype metrics

| Metric | Total | Minimum | Maximum | Average |
| --- | --- | --- | --- | --- |
| Archetypable nodes | 327 | 1 | 36 | 8 |
| Data value nodes | 173 | 1 | 43 | 4 |
| Id-codes (semantic) | 265 | 1 | 35 | 6 |
| Ac-codes (value-sets) | 29 | 1 | 6 | 0 |
| At-codes (coded values) | 99 | 2 | 21 | 2 |
| Id-code bindings | 0 | 0 | 0 | 0 |
| Ac-code bindings | 0 | 0 | 0 | 0 |
| At-code bindings | 10 | 1 | 1 | 1 |
| Total nodes | 589 | 1 | 105 | 14 |

### RM classes: LOCATABLE

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| ACTION | 1 | yes | description (1), ism_transition (1), protocol (1) |
| ADDRESS | 5 | yes | details (1), name (1) |
| ADMIN_ENTRY | 8 | yes | data (2), other_participations (4) |
| CLUSTER | 42 | yes | items (19) |
| COMPOSITION | 5 | yes | category (1), content (1), context (2) |
| CONTACT | 2 |  | addresses (2) |
| ELEMENT | 198 |  | name (1), value (132) |
| EVALUATION | 24 | yes | data (5), protocol (2) |
| EXTRACT | 2 | yes | chapters (1) |
| EXTRACT_CHAPTER | 3 |  | items (3) |
| GENERIC_CONTENT_ITEM | 8 |  | author (1), creation_time (1), item (8), item_status (1), item_type (1), item_type_version (1), version_set_id (1) |
| ITEM_LIST | 4 |  | items (4) |
| ITEM_SINGLE | 1 |  | item (1) |
| ITEM_TREE | 27 |  | items (27) |
| ORGANISATION | 4 | yes | identities (1) |
| PARTY_IDENTITY | 7 | yes | details (3), name (1) |
| PARTY_RELATIONSHIP | 1 |  | details (1) |
| PERSON | 11 | yes | contacts (1), details (1), identities (3), relationships (2) |
| SECTION | 3 | yes | items (1) |

### RM classes: DATA_VALUE

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| DV_BOOLEAN | 2 |  |  |
| DV_CODED_TEXT | 59 |  | defining_code (59) |
| DV_COUNT | 1 |  | magnitude (1) |
| DV_DATE | 9 |  | value (1) |
| DV_DATE_TIME | 10 |  | value (3) |
| DV_DURATION | 6 |  | value (1) |
| DV_IDENTIFIER | 5 |  |  |
| DV_INTERVAL<DV_DATE> | 1 |  |  |
| DV_QUANTITY | 1 |  |  |
| DV_TEXT | 76 |  | value (2) |
| DV_URI | 3 |  |  |

### RM classes: Primitive

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| Integer | 1 |  |  |
| String | 7 |  |  |

### RM classes: Any

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| CODE_PHRASE | 59 |  |  |
| EVENT_CONTEXT | 1 |  | other_context (1) |
| ISM_TRANSITION | 12 |  | careflow_step (12), current_state (12) |
| PARTICIPATION | 9 |  | function (5), performer (1) |

