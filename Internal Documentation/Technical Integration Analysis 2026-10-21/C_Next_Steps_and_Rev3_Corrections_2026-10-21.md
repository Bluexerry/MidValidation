# ANFORA RURACTIVE integration next steps

Technical analysis dated 21 October 2026. Companion to the unchanged Rev3 package; this is not Rev4 and does not implement or approve a production integration.

## Agreed method and proposed allocation

Hybrid (AMT + API) was selected and accepted on 2 September according to the correspondence supplied by Evenor-Tech. The overall method need not be reopened. The per-code allocation and current technical contract still need agreement.

Recommend AMT initially for NBS4.20, NBS15.1, NBS24.18, RRTG.SC-01b, INNOV_002, INNOV_004, INNOV_005 and INNOV_006. Prepare INNOV_003 as the first conditional API candidate after measurement and integration gates pass. INNOV_004 is a possible later API extension only after valid paired scenarios exist. These are recommendations, not approved assignments.

No API result is currently ready for production submission. Manual entry is also conditional on receiving access, accepted value/status encoding and evidence decisions. A future API cannot create missing historical measurements.

## 1 Actions Evenor-Tech can take with available resources

1. Review the nine-row decision matrix and nominate an accountable owner for each source, approval and submission. Keep one observation register shared by AMT and API, with one owning route per indicator/scope/period/revision.
2. Retain or locate the original September thread in the company archive, including headers and attachments. Accessible Gmail searches did not return Lasith's messages; the agreement in this analysis relies on the supplied correspondence account. No later specification or AMT access instruction was located in the inspected files. Do not describe this as proof of non-delivery to another mailbox.
3. Preserve the three raw PostHog CSVs already held with Rev3. Retain saved insight settings showing the project, aggregation, dates, timezone and filters. All counted 31 August Pageviews were internally performed tests. Do not submit 1 identity / 4 sessions / 39 pageviews as external adoption or infer zero external visits during unproven coverage.
4. Approve a reproducible INNOV_003 metric specification: period-wide identity/session counting, consent/capture coverage, source and environment, identity merging, internal/QA/synthetic exclusions, unknown provenance, boundary-crossing sessions, and submitted versus successful events. Do not sum daily unique counts or equate browser IDs with people. The two anonymous MongoDB calculations retain independent unverified provenance.
5. Corroborate the declared training/citizen/job zeros with accountable period confirmations and source-owner reconciliation. These remain declarations until independently supported. Keep the job zero restricted to March-August; the official annual outcome is open. Keep the 48-person September/October statement outside this reporting period and do not certify a breakdown without attendance.
6. Record the 5 August activity as an external institutional presentation and coordination with Vera/BALAM and municipal representatives. It was not training or an open public citizen event. Current internal confirmation says the agreed municipal dissemination actions have not materialised. Do not negate other documented Evenor-Tech invitations, treat intentions as delivered outreach or count institutional representatives automatically as citizens.
7. For INNOV_004, document a future comparison protocol before automation: valid paired scenarios, common functional unit/servings, quantities, dated source/method snapshots, simulation label and aggregation. Do not use the fixed 2,500 L/serving profile benchmark, clamp increases away or label global-versus-Andalusian references as supermarket-versus-local origin. New simulations cannot certify a historical comparison.
8. Keep absent water-index, irrigation-energy, numerical survey and demographic observations explicitly unavailable. Prepare future collection separately. Do not infer survey/demographic alert FALSE, group share 0% or numeric impact 0 from missing inputs.
9. In a separately approved implementation phase, build a small isolated Node ESM extractor/validator and operator-triggered dry run using existing dependencies. Default to no network and no send. Use approved exports first; request authorised least-privilege read access separately if automatic extraction is needed. Do not import application startup modules, run seed scripts or call write-capable calculation endpoints to extract data.

## 2 Documentation and access Lasith should provide

- Current post-migration API documentation, version and contact; actual test/production HTTPS destinations, permitted operations and schemas. Do not guess endpoint URLs, payload field names or response formats.
- Project, location and indicator receiver identifiers and mapping to the nine official codes; units, precision, aggregation, observation-period boundaries and correction/version rules.
- Actual credential-to-token procedure described in the October meeting: authentication location and format, token expiry/refresh, permissions, revocation/rotation and error handling. Do not assume OAuth, JWT or Bearer placement. No ANFORA login token or PostHog capture key should be reused.
- AMT URL, account/access procedure, permissions, manual entry/import capability if any, accepted statuses and receipt/export mechanism. Availability was not verified in this analysis.
- Documented success/acknowledgement and read-back, synchronous versus asynchronous validation, limits/throttling, duplicate/idempotency/update semantics and handling of delivery uncertainty.
- Authorised sandbox and test identifiers, permitted fixture use and acceptance cases. No production test send should be used to discover the contract.
- Definitive interpretation of DMS in the workbook and its relationship to API and AMT. Confirm auto_accept for each agreed route, especially AMT/non-DMS rows and unset values. Do not treat DMS as a third independent delivery mode.
- Accepted representation for a missing observation, a confirmed internal declaration, partial coverage and a restricted-period result. Do not silently send status strings in numeric fields or zeros in place of missing measurements.

## 3 Decisions required jointly

| Decision | Proposed position | Confirmation needed |
|---|---|---|
| Overall method | Hybrid (AMT + API) already agreed | Preserve the September agreement; do not describe it as awaiting selection |
| Indicator allocation | Eight AMT initially; INNOV_003 first conditional API target | Approve named codes and ownership; no route is currently configured by this study |
| DMS and auto_accept | DMS is receiver/intake terminology; likely associated with the API branch | Confirm exact workbook semantics; retain blanks until then; no blanket TRUE or inferred FALSE |
| RRTG.SC-01b | Separate institutional coordination from open citizen participation | Decide whether the 5 August institutional presentation is eligible; resolve participant versus 100 registered users and repeated attendance |
| NBS15.1 / NBS24.18 | Preserve declared zeros and provenance | Accept declaration status; confirm training counting rule, annual jobs boundaries and # jobs/FTE interpretation |
| INNOV_003 | Count valid captured usage under approved definitions, excluding tests | Unique/active user and session definition, identity merging, partial coverage, internal/unknown records and session boundaries |
| NBS4.20 / INNOV_004 | Retain territorial index versus modelled footprint distinction | Ratio/target mapping; scenario functional unit, litres/% aggregation, simulated versus observed result and zero/negative-baseline handling |
| INNOV_005 / INNOV_006 | Missing datasets remain not assessable | Survey coding/denominator, group overlap/denominator, cohort windows, small-cohort disclosure and missing/alert representation |
| Revisions and duplicates | Shared observation ledger across manual and automatic paths | Receiver-supported idempotency, updates, read-back and correction procedure |

## 4 Corrections required in a later revision of Rev3

Rev3 is not edited now. Preserve its official definitions, units, targets, baselines and collection windows.

| Rev3 location | Required correction | What remains valid |
|---|---|---|
| Report sections 1 and 5, route discussion, changes note P02 | State that Hybrid was explicitly proposed and accepted in September | Per-code allocation and specifications remain pending; no working integration established |
| Report terminology and official workbook AMT + DMS context | Distinguish AMT manual entry, API automated delivery and DMS receiver terminology | Conditional DMS -> TRUE instruction; exact mapping needs Lasith; do not alter official labels without confirmation |
| All nine auto_accept cells; traceability mechanism column | Keep blank/unassigned until per-code mapping is confirmed; annotate overall Hybrid agreement separately | No blanket TRUE, no default FALSE, no current production configuration |
| Report sections 2.2 and 3.4; source interpretations E06/E22; official workbook Q11; Data Collection F7; traceability H8/I8/M8 | Replace the broad no-external-presentations wording with confirmed external institutional presentation/coordination. Note municipal dissemination remains unmaterialised | No automatic citizen count; declared RRTG.SC-01b zero remains qualified pending eligibility decision |
| Evidence register and changes note | Add the supplied September agreement and new institutional clarification with correct provenance; distinguish original messages from supplied account | E15 transcript remains verified; exact October meeting date unstated; no invented email headers or signed documents |
| INNOV_003 / INNOV_004 recommendations | Separate future API capability from actual result availability | Internal PostHog tests are not external adoption; MongoDB calculations remain unclassified; no verified historical pair/savings result |
| Training/jobs and remaining states | No invented numerical improvement from the integration design | Declared training zero, qualified citizen zero and partial-period job zero; six unavailable numeric results, annual job outcome open |

The meeting clarification resolves the factual characterisation of 5 August; it does not resolve RRTG.SC-01b eligibility. Do not retain the false implication that no presentation to external people occurred. Do not automatically remove the declared zero or validate it as measured attendance without Lasith's scope decision.

## 5 Implementation sequence and acceptance

### G1 Contract and indicator assignment

Owner: Lasith + Evenor-Tech.

Confirm AMT/API per code, DMS flag mapping, IDs, units, time boundaries, missing/status representation and acceptance of declarations.

Acceptance: No production send until the receiver contract and authority are explicit.

### G2 Source and measurement validity

Owner: Evenor-Tech.

Approve dataset/query versions, capture coverage, identity/session definition, exclusions, window and release status; preserve missing values.

Acceptance: INNOV_003 internal tests and unverified external totals remain held; INNOV_004 needs valid pairs.

### G3 Isolated implementation and dry run

Owner: Evenor-Tech.

Future separate Node ESM adapter using current dependencies; file-based prepared observations/delivery ledger, single worker, no public endpoint or app hot-path send. Default dry-run.

Acceptance: No credentials, code or services created in this study.

### G4 Sandbox contract and privacy tests

Owner: Evenor-Tech + Lasith.

Only authorised sandbox or local mock; test limits, errors, duplicate/manual/API collision, timeout uncertainty, token expiry, missing vs zero, internal exclusions and minimum aggregates.

Acceptance: No test data or synthetic records submitted as production observations.

### G5 Controlled release and reconciliation

Owner: Evenor-Tech + Lasith.

Approve per-code release; send small validated batch once, verify documented receiver acknowledgement/read-back, reconcile AMT entries and keep immutable receipt evidence.

Acceptance: No interpretation of HTTP success or auto_accept as formal indicator approval.

Keep the delivery ledger private and durable. For the initial low-volume single worker, atomic files and locking can avoid a new database or queue service. Record an observation revision/hash and documented receipt; an identical payload is not sent twice, including after manual AMT entry. A local hash is not a receiver idempotency guarantee. After ambiguous timeout, hold as unknown and reconcile before retrying a potentially non-idempotent request. Use receiver-supported idempotency/read-back when documented. See [HTTP retry semantics](https://www.rfc-editor.org/rfc/rfc9110.html#section-9.2.2).

Transmit minimum approved aggregates, not personal IDs or raw event/recipe/demographic records. Never expose tokens in browser builds, source control or logs. Confirm runtime support before choosing built-in HTTP; [Node documentation](https://nodejs.org/api/globals.html#fetch) describes the available native client. Access to [PostHog historical queries](https://posthog.com/docs/api) is distinct from capture configuration. These sources provide engineering guidance, not the RURACTIVE contract.

## Source verification and preservation

September email dates/content were supplied by Evenor-Tech; original messages and subsequent technical material were not found in the accessible mailbox/files. The original October transcript corroborates the prior two-route discussion, conditional flag rule and planned token access. The technical report and matrix identify all source locators and limits. No credentials, private API requests, database writes, application changes, DNS changes, deployments or Git updates were performed.

The six Rev3 byte hashes recorded for before/after preservation are:

| Rev3 file | SHA-256 |
|---|---|
| ANFORA_Data_Collection_Mid_Validation_Updated_2026-10-21_Rev3.xlsx | `4fe159910ec87fa1ea459dc9477a3cbe3ae7b2260810b9b3eb7f085b0b2ccd1f` |
| ANFORA_Indicator_Traceability_2026-10-21_Rev3.xlsx | `85d12f852c76097a8dd200f999dd839901408503ea2ec03ca694c5db2819bdfa` |
| ANFORA_Innovator_Indicators_Review_2026-10-21_Rev3.docx | `d3c7b5ef067243fedf405a3b2cd483e6ed71e1bda6374a3909f09a3b9351b2e3` |
| ANFORA_Innovator_Indicators_Review_2026-10-21_Rev3.pdf | `9634398d2f5ab36cf4715aa401956042345d04fb5b25f82b3704297780e1a2f2` |
| ANFORA_Innovator_Indicators_Updated_2026-10-21_Rev3.xlsx | `12626403c2f7bd8870ef9e447053ac11855dfe58c76115e4c2897eca29f6d305` |
| Changes_and_Pending_Information_2026-10-21_Rev3.md | `9e0b9b9b79e3e446e15ff5a63a39c8892a35ce076985e8c633bf88283dc879a3` |

Preservation check: all tracked source files, environment files, the six Rev3 files and Git HEAD/index/history hashes remain unchanged. A byte change was observed in the auxiliary frontend `.git/gk/config` file during the review; its origin was not established. This study did not write or restore it. The exception is recorded separately from code/history preservation.

Deliverables: A technical feasibility Word document, B decision matrix workbook and this C next-steps note. Only these three files are published in the technical-analysis folder. No Rev4 is created and no information is sent to Lasith or RURACTIVE.
