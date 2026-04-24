# Decision / Assumption / Open Questions Log

Structured review log for **Features of the Medical Records System (MRS)**.

| ID | Type | Title | Status | Notes |
| --- | --- | --- | --- | --- |
| Q-01 | Open questions | RBAC role definitions are not specified | Open | The source requires RBAC but does not define the user roles, permissions, or segregation-of-duties model needed to implement and test access control. |
| Q-02 | Open questions | SNOMED CT support remains optional | Open | The source marks SNOMED CT support as optional, so scope, priority, and implementation depth are not yet fixed. |
| RSK-01 | Risks | Integration contracts and interface details are undefined | Monitor | Multiple external integrations are required, but the source does not define interface standards, message formats, ownership, or environment dependencies. This creates delivery and testing risk. |

## Recommended follow-up actions

- **Q-01 — RBAC role definitions are not specified**
  - The source requires RBAC but does not define the user roles, permissions, or segregation-of-duties model needed to implement and test access control.
  - Suggested follow-up: Resolve 'RBAC role definitions are not specified' before implementation and test planning are finalized.
- **Q-02 — SNOMED CT support remains optional**
  - The source marks SNOMED CT support as optional, so scope, priority, and implementation depth are not yet fixed.
  - Suggested follow-up: Resolve 'SNOMED CT support remains optional' before implementation and test planning are finalized.
- **RSK-01 — Integration contracts and interface details are undefined**
  - Multiple external integrations are required, but the source does not define interface standards, message formats, ownership, or environment dependencies. This creates delivery and testing risk.
  - Suggested follow-up: Define mitigation and ownership for 'Integration contracts and interface details are undefined'.