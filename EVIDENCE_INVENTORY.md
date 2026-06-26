# Batch 5 Phase 0 - Evidence Inventory

This inventory is a repository-first intake baseline for Batch 5.

- Inspection scope: this repository only
- Repository scan result: no evidence artifact files (screenshots, diagrams, pcaps, logs, reports) are currently stored in this repository
- Next action: populate `Location` with approved evidence sources (for example, sanitized Google Drive paths) before page implementation

## Evidence Inventory Table

| Artifact ID | Category | Project | Evidence Type | Location | Public Safe | Redaction Needed | Chain of Custody Required | Evidence Confidence | Status | Reviewer | Date Verified | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| HL-001 | Home Lab screenshots | Home Lab Architecture | Screenshot | TBD | TBD | TBD | No | Medium | Planned | TBD | TBD | Add sanitized lab screenshots only |
| HL-002 | Network diagrams | Home Lab Architecture | Diagram | TBD | TBD | TBD | No | Medium | Planned | TBD | TBD | Prefer sanitized logical diagrams |
| SIEM-001 | Splunk dashboards | Splunk SOC Lab | Screenshot | TBD | TBD | TBD | No | Medium | Planned | TBD | TBD | Remove host/user identifiers |
| NET-001 | Packet captures | Network Security | PCAP/PCAPNG | TBD | TBD | TBD | Yes | High | Planned | TBD | TBD | Remove sensitive payload context |
| DET-001 | SIEM detections | Splunk SOC Lab | Search/Alert Evidence | TBD | TBD | TBD | No | Medium | Planned | TBD | TBD | Include query + result evidence |
| IR-001 | Incident response artifacts | Incident Response | Report/Timeline | TBD | TBD | TBD | Yes | Medium | Planned | TBD | TBD | Separate verified evidence vs interpretation |
| DFIR-001 | Digital forensics artifacts | Digital Forensics | Case Report/Screenshot | TBD | TBD | TBD | Yes | High | Planned | TBD | TBD | Preserve chain-of-custody notes |
| CLOUD-001 | Cloud security artifacts | Cloud Security | Config/Assessment Evidence | TBD | TBD | TBD | No | Medium | Planned | TBD | TBD | Avoid tenant and account identifiers |
| CRX-001 | CrownX sanitized evidence | CrownX Assessments | Sanitized Report Extract | TBD | TBD | TBD | No | Low | Planned | TBD | TBD | Public Safe only, no proprietary details |
| AD-001 | Architecture diagrams | Architecture Diagrams | Diagram | TBD | TBD | TBD | No | Medium | Planned | TBD | TBD | Use non-production representations |

## Controlled Status Lifecycle

- Planned
- Collected
- Redaction Required
- Ready for Review
- Approved for Release
- Published
- Archived

## Evidence Confidence Scale

- High = directly observed and preserved
- Medium = partially preserved or reconstructed
- Low = narrative or inferred

## Intake and Release Workflow

Evidence Inventory -> Collect -> Verify -> Redact -> Human Review -> Approve for Release -> Build Page -> Validate -> Commit -> Push -> Archive

## Public-Release Redaction Rules

- Remove IP addresses
- Remove hostnames
- Remove usernames
- Remove tenant identifiers
- Remove API keys, tokens, and secrets
- Sanitize screenshots
- Prefer diagrams over exposing live infrastructure
- Remove MAC addresses
- Remove serial numbers and asset tags
- Remove internal URLs and DNS names
- Remove cloud account IDs and subscription IDs
- Remove geolocation information when unnecessary
