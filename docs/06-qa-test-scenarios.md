# QA Test Scenarios / Use Cases

This pack captures scenario-ready QA coverage for **Features of the Medical Records System (MRS)**.

## QA coverage snapshot

| Area | Value |
| --- | --- |
| Workflows under test | 2 |
| Executable scenarios | 3 |
| Feature references | 10 |
| Exploratory question areas | 2 |

## Workflow under test

- WF-01 — OPD encounter documentation workflow
- WF-02 — IPD admission-to-discharge workflow

## TS-01 — Patient lookup and duplicate detection behavior

- **Derived from:** AC-01
- **Feature focus:** FR-01 — Patient registration and profile management

```gherkin
Feature: Features of the Medical Records System (MRS)
  Scenario: Patient lookup and duplicate detection behavior
    Given the onboarding workflow is available
    When the system shall allow a patient to be found using hn, national id, name, or phone number, and shall support duplicate patient detection during patient registration and profile management.
    Then the expected outcome is produced
```

### Test intent

- Validate the happy path, rejection path, and observable system response.
- Capture traceability to source requirements in test evidence and defect reports.

## TS-02 — Laboratory results availability and visualization

- **Derived from:** AC-02
- **Feature focus:** FR-02 — Outpatient medical record management

```gherkin
Feature: Features of the Medical Records System (MRS)
  Scenario: Laboratory results availability and visualization
    When laboratory results are entered, they shall be available in the medical record and support graphical result display.
```

### Test intent

- Validate the happy path, rejection path, and observable system response.
- Capture traceability to source requirements in test evidence and defect reports.

## TS-03 — Required report outputs

- **Derived from:** AC-03
- **Feature focus:** FR-03 — Inpatient admission and inpatient record management

```gherkin
Feature: Features of the Medical Records System (MRS)
  Scenario: Required report outputs
    Given the onboarding workflow is available
    When the reporting capability shall produce daily patient census, icd-10 disease, drug utilization, opd/ipd statistical, and provincial health office / nhso reports.
    Then the expected outcome is produced
```

### Test intent

- Validate the happy path, rejection path, and observable system response.
- Capture traceability to source requirements in test evidence and defect reports.

## Exploratory follow-up areas

- Q-01 — RBAC role definitions are not specified
- Q-02 — SNOMED CT support remains optional