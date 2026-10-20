# ANFORA Innovator Indicators second critical review

Review date: 20 October 2026. Period: 1 March–31 August 2026. Status: INTERNAL DRAFT, not a completed validated submission.

## Material corrections from the first six files

- E15 now verifies the original transcript in full, 12:31:54–12:47:18. The exact meeting date is unstated and is not inferred from file metadata.
- Removed the unsupported assignment of all nine codes to DMS. The transcript confirms only DMS -> TRUE after route selection. No per-code DMS, API or AMT assignment is established. All nine auto_accept cells are blank, not FALSE. No production configuration was modified.
- Changed INNOV_003 from Partially verified to Not verified at official indicator level. The one new account and two anonymous calculation records remain auxiliary observations, not unique users, sessions or verified real external interactions.
- Cleared DATA VALUE in all nine period rows because no official numerical value has been substantiated. Status, evidence, missing inputs and recovery steps remain in COMMENTS and traceability. Blank means unavailable, not zero. This does not by itself satisfy Lasith’s request for real values.
- Preserved every official code, name, contextual definition, unit, target, declared baseline and collection frequency. The participant definition versus 100 registered users target and the territorial WEI/footprint target mapping require clarification.
- Recorded the literal statement “48 trainers” and the undertaking to check the March–August subset. The transcript verifies the claim was spoken, not the attendance or training dates. E15 no longer lists the original transcript as outstanding.
- Added read-only classification evidence: 32 current account records comprise 22 known synthetic IDs, two additional company-domain flags and eight unclassified records. At cut-off: two company-domain flags and three unclassified records. The one new in-period account remains unclassified. These are not external-user totals.
- Added the direct PostHog recovery procedure. No historical export or read access was available. Code introduced on 31 August does not prove historical deployment or capture coverage. Recovery depends on retained events and the owner’s access; no new capture or export-job configuration was created.

## What can be communicated

Verified instructions and auxiliary dated technical counts can be communicated with their limits. No numerical result for any of the nine official indicators is validated. NBS4.20, INNOV_002 and INNOV_004 are Not measured. NBS15.1, NBS24.18, RRTG.SC-01b and INNOV_003 are Not verified. INNOV_005 and INNOV_006 are Not assessable.

## Information still required

### P01 48 trainers and dated attendance

Evenor-Tech/Francisco: identify the 48-person claim’s meaning and events; obtain original registers or Teams/Meet attendance reports, training completion and event dates. Reconcile the March–August cohort and repetitions. The original transcript is now verified; only its exact meeting date remains unstated.

Impact: NBS15.1 and RRTG.SC-01b; no official total yet. References: E06 E08 E09 E14 E15.

### P02 Per-code delivery agreement

Evenor-Tech proposes, Lasith confirms the route for each of nine codes. Clarify AMT/API/DMS terminology, TRUE/FALSE semantics for non-DMS rows, unset values, missing-value encoding and annual/seasonal/quarterly windows. Request endpoint/schema/authentication and receipt requirements through normal project channels.

Impact: No confirmed DMS rows or API/AMT rows in the retained evidence. All nine route settings remain unassigned. References: E01 E15.

### P03 Eligibility and participant target

Evenor-Tech: owner-maintained classification of every account as internal/QA/synthetic/eligible external, with dated provenance and pseudonymous deduplication. Lasith: approve how # participants relates to the target of 100 registered users and how repeat attendance is counted.

Impact: Account counts cannot fill the official participant value or target percentage. References: E01 E11 E12 E20.

### P04 Historical users sessions and interactions

Evenor-Tech analytics owner: check project/cloud and retention, earliest production events and capture coverage; export retained March–August events with timestamp, event UUID/name, distinct/person identity mapping, $session_id, environment/source and event auth state. Exclude internal/QA/test activity and reconcile event duplicates. Supply deployment/consent coverage and session definition.

Impact: INNOV_003 remains Not verified. Instrumentation appears on 31 August; full-period recovery cannot be presumed. References: E10 E11 E12 E21.

### P05 Territorial water index and target mapping

Evenor-Tech with CHG/institutional data owner: same-area, same-season/year water-use and renewable-resource baseline/follow-up. Lasith: clarify the ratio wording and whether the 10–15% target belongs to territorial WEI or the project footprint KPI.

Impact: NBS4.20 remains Not measured; annual/seasonal contextual data do not establish attributable project reduction. References: E01 E17.

### P06 Employment and irrigation source records

Evenor-Tech HR: dated new-employment evidence, eligible role, hours/FTE and attribution. Farm/irrigation partners via Evenor-Tech: dated kWh, irrigated hectares and matched seasonal baseline/follow-up.

Impact: NBS24.18 Not verified; INNOV_002 Not measured. Existence of records with owners is unconfirmed. References: E01 E05 E13.

### P07 Paired savings surveys and demographics

Evenor-Tech: dated comparable baseline/adjusted scenario pairs, completed numerical survey export with cohort denominator, consented target-group declarations and missing-data handling. Lasith: agree aggregation, satisfaction-percent coding and demographic denominator/group-overlap handling.

Impact: INNOV_004 Not measured; INNOV_005 and INNOV_006 Not assessable. Missing inputs cannot be backfilled from current impressions. References: E01 E09 E11 E12 E13.

## Release decision

Keep the package as an internal draft. Prioritise the source of 48, dated attendance, account classification and historical analytics, followed by Lasith’s per-code route and metric clarifications. Do not report any missing outcome as zero or treat non-synthetic records as authenticated external people. Originals and the first review remain intact. No application code, operational records, credentials, configuration, deployments or Git history were modified.
