# Reconciliation report: AIUC-1 2026-07-15

| Status | Check |
|---|---|
| PASS | NIST OSCAL JSON schema (oscal_catalog_schema_1.1.3.json) |
| PASS | oscal-cli validate (schema + Metaschema constraints) |
| INFO | inventory |
| PASS | active requirements have >=1 control |
| PASS | controls have >=1 activity |
| PASS | no activities without a numbered control |
| PASS | control numbering contiguous 1..n |
| INFO | control page order is numeric |
| PASS | retired requirements point at an existing requirement |
| PASS | requirement metadata complete |
| WARN | controls carry an evidence kind |
| PASS | controls carry an evidence category |
| PASS | control capabilities within requirement capabilities |
| INFO | source issues noted by parser |
| PASS | GitHub requirements.md covers same requirement IDs |
| PASS | requirement statements match GitHub requirements.md |
| WARN | control activities match GitHub controls.md (text) |
| INFO | control activities match GitHub controls.md (order) |
| PASS | current-edition changelog claims consistent with pages |
| PASS | internal #references resolve |

## PASS: oscal-cli validate (schema + Metaschema constraints)

- Validating 'file:/Users/badenh/claudetemp/aiuc1-oscal-builder/converter/out/2026-07-15/aiuc-1_catalog.json' as JSON.
- The file 'file:/Users/badenh/claudetemp/aiuc1-oscal-builder/converter/out/2026-07-15/aiuc-1_catalog.json' is valid.
- The operation couldn’t be completed. Unable to locate a Java Runtime.
- Please visit http://www.java.com for information on installing Java.

## INFO: inventory

6 domains; 53 requirements (51 active, 2 retired); 142 numbered controls; 184 control activities

## INFO: control page order is numeric

- B008: page order [1, 2, 5, 3, 4] (tier-grouped); catalog emits numeric order
- E015: page order [1, 3, 4, 2] (tier-grouped); catalog emits numeric order

## PASS: retired requirements point at an existing requirement

- E007 -> E004
- E014 -> E017

## WARN: controls carry an evidence kind

- C012.1

## INFO: source issues noted by parser

- C012.1: evidence title has no kind prefix (Documentation/Config/...): 'C012.1 Third-party evaluation report assessing customer-defined risk'
- E007.1: evidence title has no kind prefix (Documentation/Config/...): 'E007.1 Retired'
- E014.1: evidence title has no kind prefix (Documentation/Config/...): 'E014.1 Not applicable'

## WARN: control activities match GitHub controls.md (text)

- **id**: C009; **kind**: text; **site_only**: ['Reviewing user feedback and intervention logs at regular intervals, analyzing findings using structured methodologies (e. g., categorizing by risk domain, frequency, and severity), and integrating corrective actions into product backlogs or compliance workflows, with records maintained for traceability']; **github_only**: ['Reviewing user feedback and intervention logs at regular intervals, analyzing findings using structured methodologies (e.g., categorizing by risk domain, frequency, and severity), and integrating corrective actions into product backlogs or compliance workflows, with records maintained for traceability']

## INFO: control activities match GitHub controls.md (order)

- B008
- E015

