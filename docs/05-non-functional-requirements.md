# Non-Functional Requirements

Non-functional constraints and quality expectations for **Features of the Medical Records System (MRS)**.

## Quality profile

| Area | Value |
| --- | --- |
| Explicit NFRs | 4 |
| Quality risks | 1 |
| Open questions | 2 |

## Explicit non-functional requirements

### NFR-01 — Performance targets

- **Source:** Lines 101-102

The system shall meet these performance expectations:
- Response times of less than 2 seconds
- Support for 50-500 concurrent users

### NFR-02 — Security controls

- **Source:** Lines 106-109

The system shall provide:
- Encryption at rest and in transit
- Role-based access control (RBAC)
- Full audit trail logging
- Unauthorized access prevention

### NFR-03 — Reliability targets

- **Source:** Lines 113-114

The system shall provide:
- Uptime of at least 99.5%
- Daily automated backups

### NFR-04 — Usability and device support

- **Source:** Lines 118-120

The system shall provide:
- A simple user interface
- Light and dark modes
- Support for mobile and tablet devices


## Related open questions

- **Q-01 — RBAC role definitions are not specified**
  - The source requires RBAC but does not define the user roles, permissions, or segregation-of-duties model needed to implement and test access control.
- **Q-02 — SNOMED CT support remains optional**
  - The source marks SNOMED CT support as optional, so scope, priority, and implementation depth are not yet fixed.

## Quality and delivery risks

- **RSK-01 — Integration contracts and interface details are undefined**
  - Multiple external integrations are required, but the source does not define interface standards, message formats, ownership, or environment dependencies. This creates delivery and testing risk.

## Operational readiness considerations

- Define monitoring, alerting, and recovery expectations for every production-critical workflow.
- Confirm ownership for performance, availability, security, and compliance controls before implementation starts.
- Translate open questions into measurable acceptance checks before release planning.