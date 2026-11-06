# Statistics of archetype library SPLASH-ADLref

## Compilation

| Metric | Count |
| --- | --- |
| Valid archetypes | 168 |
| Specialised archetypes | 75 |
| Client archetypes | 26 |
| Supplier archetypes | 106 |
| Total archetypes | 235 |

## Terminology bindings

| Terminology | Archetypes |
| --- | --- |
| AIR93 | 1 |
| AIR93(1.0.0) | 1 |
| LNC205 | 3 |
| LOINC | 1 |
| SNOMED-CT | 4 |
| loinc | 2 |
| openehr | 25 |
| snomedct | 2 |

## Reference model org.openehr:healthcare

### Archetype metrics

| Metric | Total | Minimum | Maximum | Average |
| --- | --- | --- | --- | --- |
| Archetypable nodes | 727 | 1 | 28 | 5 |
| Data value nodes | 449 | 1 | 62 | 3 |
| Id-codes (semantic) | 651 | 1 | 48 | 5 |
| Ac-codes (value-sets) | 88 | 1 | 6 | 0 |
| At-codes (coded values) | 429 | 1 | 44 | 3 |
| Id-code bindings | 7 | 1 | 1 | 1 |
| Ac-code bindings | 6 | 1 | 1 | 1 |
| At-code bindings | 99 | 1 | 1 | 1 |
| Total nodes | 1564 | 1 | 162 | 12 |

### RM classes: LOCATABLE

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| ACTION | 3 | yes | description (2), ism_transition (3), other_participations (1), protocol (2) |
| ACTIVITY | 2 |  | description (2) |
| ADDRESS | 10 |  | details (2), name (1) |
| ADMIN_ENTRY | 1 | yes | data (1) |
| CLUSTER | 98 | yes | items (50), name (3) |
| COMPOSITION | 2 | yes | category (1), content (2), context (1) |
| CONTACT | 7 |  | addresses (5) |
| ELEMENT | 316 |  | name (2), value (285) |
| ENTRY | 1 |  |  |
| EVALUATION | 23 | yes | data (13), protocol (2) |
| EVENT | 34 |  | data (22), state (8) |
| EVENT<ITEM_LIST> | 1 |  | data (1) |
| HISTORY | 39 |  | events (36) |
| HISTORY<ITEM_LIST> | 1 |  | events (1) |
| INSTRUCTION | 5 | yes | activities (2) |
| INTERVAL_EVENT | 2 |  | data (2), math_function (2), state (2) |
| ITEM | 3 |  | name (2) |
| ITEM_LIST | 23 |  | items (9) |
| ITEM_TREE | 84 |  | items (72), name (1) |
| OBSERVATION | 77 | yes | data (35), protocol (16) |
| ORGANISATION | 1 | yes | identities (1) |
| PARTY_IDENTITY | 4 |  | details (1), name (2) |
| PARTY_RELATIONSHIP | 1 |  | details (1) |
| PERSON | 3 | yes | contacts (3), details (1), identities (2), name (2) |
| POINT_EVENT | 18 |  | data (18), offset (12), state (1) |
| ROLE | 1 | yes | details (1), identities (1), relationships (1) |
| SECTION | 10 | yes | items (8) |

### RM classes: DATA_VALUE

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| DV_BOOLEAN | 10 |  | value (6) |
| DV_CODED_TEXT | 212 |  | defining_code (152) |
| DV_COUNT | 6 |  | magnitude (5) |
| DV_DATE | 3 |  | value (2) |
| DV_DATE_TIME | 13 |  | value (2) |
| DV_DURATION | 12 |  | value (12) |
| DV_EHR_URI | 3 |  |  |
| DV_ENCAPSULATED | 1 |  |  |
| DV_IDENTIFIER | 3 |  |  |
| DV_INTERVAL | 1 |  |  |
| DV_INTERVAL<DV_DATE_TIME> | 1 |  | lower (1), upper (1) |
| DV_INTERVAL<DV_QUANTITY> | 1 |  |  |
| DV_MULTIMEDIA | 9 |  |  |
| DV_ORDINAL | 15 |  | symbol (15), value (15) |
| DV_PROPORTION | 6 |  | is_integral (6), numerator (6), type (6) |
| DV_QUANTITY | 38 |  | magnitude (16), normal_range (2), other_reference_ranges (1), precision (7), property (25), units (28) |
| DV_TEXT | 120 |  | value (2) |
| DV_URI | 1 |  |  |

### RM classes: Primitive

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| Boolean | 13 |  |  |
| Integer | 72 |  |  |
| Real | 30 |  |  |
| String | 55 |  |  |

### RM classes: Any

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| CODE_PHRASE | 178 |  |  |
| EVENT_CONTEXT | 1 |  | other_context (1) |
| ISM_TRANSITION | 36 |  | careflow_step (36), current_state (36) |
| PARTICIPATION | 2 |  | function (2) |
| REFERENCE_RANGE<DV_QUANTITY> | 1 |  |  |

## Reference model org.openehr:test

### Archetype metrics

| Metric | Total | Minimum | Maximum | Average |
| --- | --- | --- | --- | --- |
| Archetypable nodes | 75 | 1 | 15 | 1 |
| Data value nodes | 56 | 1 | 10 | 1 |
| Id-codes (semantic) | 98 | 1 | 14 | 2 |
| Ac-codes (value-sets) | 6 | 1 | 1 | 0 |
| At-codes (coded values) | 32 | 1 | 5 | 0 |
| Id-code bindings | 0 | 0 | 0 | 0 |
| Ac-code bindings | 0 | 0 | 0 | 0 |
| At-code bindings | 10 | 1 | 1 | 1 |
| Total nodes | 457 | 1 | 104 | 11 |

### RM classes: LOCATABLE

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| BOOK | 2 | yes | author (2), chapters (2), title (2) |
| CAR | 4 | yes | body (3), engine_parts (3) |
| CAR_BODY | 4 |  | description (3), model (4) |
| CHAPTER | 6 |  | title (6) |
| ENGINE_PART | 6 |  | items (6) |
| ENGINE_PART_ITEM | 18 |  | model (6), type (6) |
| SOME_TYPE | 14 | yes | clinical_coded_text_attr_1 (2), clinical_ordinal_attr_1 (3), clinical_quantity_attr_1 (6), clinical_quantity_attr_2 (3), clinical_quantity_attr_4 (2), clinical_quantity_attr_5 (2), clinical_quantity_attr_6 (2), qty_interval_attr_1 (2), qty_interval_attr_2 (1), standard_coded_text_attr (2), standard_coded_text_attr_2 (2), standard_ordinal_attr (3), standard_quantity_attr (3) |
| TEST_ELEMENT | 1 |  |  |
| TEST_ENTRY | 7 | yes | element_attr_2 (1), ordinal_attr_1 (1), value (1) |
| WHOLE | 13 | yes | any_attr_1 (1), any_attr_2 (1), any_attr_3 (1), any_attr_4 (1), any_attr_5 (1), boolean_attr1 (2), boolean_attr2 (2), boolean_attr3 (2), date_attr1 (2), date_attr10 (1), date_attr11 (1), date_attr2 (2), date_attr3 (2), date_attr4 (2), date_attr5 (2), date_attr6 (2), date_attr7 (1), date_attr8 (1), date_attr9 (1), date_time_attr1 (2), date_time_attr10 (1), date_time_attr11 (1), date_time_attr12 (1), date_time_attr13 (1), date_time_attr2 (2), date_time_attr3 (2), date_time_attr4 (2), date_time_attr5 (2), date_time_attr6 (2), date_time_attr7 (2), date_time_attr8 (2), date_time_attr9 (1), duration_attr1 (3), duration_attr10 (1), duration_attr11 (1), duration_attr12 (1), duration_attr13 (1), duration_attr14 (1), duration_attr15 (1), duration_attr16 (1), duration_attr17 (1), duration_attr18 (1), duration_attr19 (1), duration_attr2 (3), duration_attr20 (1), duration_attr21 (1), duration_attr22 (1), duration_attr23 (1), duration_attr24 (1), duration_attr25 (1), duration_attr26 (1), duration_attr27 (1), duration_attr28 (1), duration_attr29 (1), duration_attr3 (2), duration_attr30 (1), duration_attr31 (1), duration_attr32 (1), duration_attr33 (1), duration_attr34 (1), duration_attr35 (1), duration_attr36 (1), duration_attr4 (2), duration_attr5 (2), duration_attr6 (2), duration_attr7 (1), duration_attr8 (1), duration_attr9 (1), integer_attr1 (2), integer_attr10 (1), integer_attr11 (1), integer_attr12 (1), integer_attr2 (2), integer_attr3 (2), integer_attr4 (2), integer_attr5 (2), integer_attr6 (2), integer_attr7 (2), integer_attr8 (2), integer_attr9 (2), real_attr1 (2), real_attr10 (1), real_attr11 (1), real_attr12 (1), real_attr2 (2), real_attr3 (2), real_attr4 (2), real_attr5 (2), real_attr6 (2), real_attr7 (2), real_attr8 (2), real_attr9 (2), string_attr1 (4), string_attr2 (2), string_attr3 (2), string_attr5 (1), time_attr1 (2), time_attr10 (1), time_attr11 (1), time_attr12 (1), time_attr2 (2), time_attr3 (2), time_attr4 (2), time_attr5 (2), time_attr6 (2), time_attr7 (2), time_attr8 (1), time_attr9 (1) |

### RM classes: DATA_VALUE

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| DV_CODED_TEXT | 20 |  | defining_code (11) |
| DV_COUNT | 4 |  | magnitude (4) |
| DV_INTERVAL<DV_QUANTITY> | 3 |  | lower (1), lower_included (1), upper (1), upper_included (1) |
| DV_ORDINAL | 9 |  | symbol (9), value (9) |
| DV_QUANTITY | 20 |  | magnitude (14), precision (2), property (12), units (18) |

### RM classes: Primitive

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| Boolean | 8 |  |  |
| Integer | 44 |  |  |
| Real | 40 |  |  |
| String | 87 |  |  |

### RM classes: Any

| Class | Occurrences | Archetype root | Attributes |
| --- | --- | --- | --- |
| CODE_PHRASE | 32 |  | code_string (12), terminology_id (12) |
| Iso8601_date | 17 |  |  |
| Iso8601_date_time | 22 |  |  |
| Iso8601_duration | 45 |  |  |
| Iso8601_time | 19 |  |  |
| TERMINOLOGY_ID | 12 |  | value (12) |

