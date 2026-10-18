# Reconciliation report: AIUC-1 2026-01-15

| Status | Check |
|---|---|
| PASS | NIST OSCAL JSON schema (oscal_catalog_schema_1.1.3.json) |
| PASS | oscal-cli validate (schema + Metaschema constraints) |
| INFO | inventory |
| PASS | active requirements have >=1 activity |
| PASS | retired requirements point at an existing requirement |
| PASS | requirement metadata complete |
| PASS | requirements carry at least one crosswalk framework |
| PASS | internal #references resolve |

## PASS: oscal-cli validate (schema + Metaschema constraints)

- Validating 'file:/Users/badenh/claudetemp/aiuc1-oscal-builder/converter/out/wayback/2026-01-15/aiuc-1_catalog.json' as JSON.
- The file 'file:/Users/badenh/claudetemp/aiuc1-oscal-builder/converter/out/wayback/2026-01-15/aiuc-1_catalog.json' is valid.
- The operation couldn’t be completed. Unable to locate a Java Runtime.
- Please visit http://www.java.com for information on installing Java.

## INFO: inventory

6 domains; 51 requirements (49 active, 2 retired); 127 control activities (flat; no numbered controls in Wayback aiuc-1.com snapshots)

## PASS: retired requirements point at an existing requirement

- E007 -> E004
- E014 -> E017

