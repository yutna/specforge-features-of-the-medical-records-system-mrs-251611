# Requirements Traceability Matrix

Traceability for the current baseline and generated pack for **Features of the Medical Records System (MRS)**.

| Baseline ID | Kind | Title | Source lines | Referenced in | Delivery focus |
| --- | --- | --- | --- | --- | --- |
| FR-01 | Features and capabilities | Patient registration and profile management | Lines 13-19 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| DE-01 | Data entities | Patient master profile | Lines 13-19 | Functional requirements | Data design |
| AC-01 | Acceptance conditions | Patient lookup and duplicate detection behavior | Lines 13-19 | User stories with acceptance criteria, QA test scenarios / use cases | Verification |
| FR-02 | Features and capabilities | Outpatient medical record management | Lines 23-35 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| WF-01 | Workflows and processes | OPD encounter documentation workflow | Lines 23-35 | Functional requirements, QA test scenarios / use cases | Process orchestration |
| DE-02 | Data entities | OPD encounter record | Lines 23-35 | Functional requirements | Data design |
| FR-03 | Features and capabilities | Inpatient admission and inpatient record management | Lines 39-47 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| WF-02 | Workflows and processes | IPD admission-to-discharge workflow | Lines 39-47 | Functional requirements, QA test scenarios / use cases | Process orchestration |
| FR-04 | Features and capabilities | Medication and pharmacy management | Lines 51-57 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| BR-01 | Business rules | Medication safety checks | Lines 51-57 | Functional requirements, User stories with acceptance criteria | Validation and policy |
| DE-03 | Data entities | Medication inventory and dispensing traceability | Lines 51-57 | Functional requirements | Data design |
| FR-05 | Features and capabilities | Laboratory order and result management | Lines 61-66 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| INT-01 | Integrations | Laboratory results integrated with medical records | Lines 61-66 | Functional requirements | External dependency |
| AC-02 | Acceptance conditions | Laboratory results availability and visualization | Lines 61-66 | User stories with acceptance criteria, QA test scenarios / use cases | Verification |
| FR-06 | Features and capabilities | Imaging and radiology management | Lines 70-73 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| INT-02 | Integrations | PACS and image support | Lines 70-73 | Functional requirements | External dependency |
| FR-07 | Features and capabilities | Clinical document management | Lines 77-80 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| CON-01 | Constraints | Supported document upload formats | Lines 77-80 | Functional requirements, Non-functional requirements | Technical boundary |
| FR-08 | Features and capabilities | Appointment scheduling and reminder management | Lines 84-87 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| INT-03 | Integrations | SMS and LINE reminder integration | Lines 84-87 | Functional requirements | External dependency |
| FR-09 | Features and capabilities | Billing and insurance management | Lines 91-95 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| INT-04 | Integrations | Insurance eligibility verification | Lines 91-95 | Functional requirements | External dependency |
| NFR-01 | Non-functional requirements | Performance targets | Lines 101-102 | Non-functional requirements | Quality control |
| NFR-02 | Non-functional requirements | Security controls | Lines 106-109 | Non-functional requirements | Quality control |
| Q-01 | Open questions | RBAC role definitions are not specified | Derived during baseline refinement | Non-functional requirements, Decision / assumption / open questions log, QA test scenarios / use cases | Clarification needed |
| NFR-03 | Non-functional requirements | Reliability targets | Lines 113-114 | Non-functional requirements | Quality control |
| NFR-04 | Non-functional requirements | Usability and device support | Lines 118-120 | Non-functional requirements | Quality control |
| CON-02 | Constraints | Clinical coding and regulatory compliance | Lines 124-130 | Functional requirements, Non-functional requirements | Technical boundary |
| Q-02 | Open questions | SNOMED CT support remains optional | Derived during baseline refinement | Non-functional requirements, Decision / assumption / open questions log, QA test scenarios / use cases | Clarification needed |
| INT-05 | Integrations | External system integrations | Lines 134-138 | Functional requirements | External dependency |
| RSK-01 | Risks | Integration contracts and interface details are undefined | Derived during baseline refinement | Vision / scope / problem statement, Non-functional requirements, Decision / assumption / open questions log | Mitigation planning |
| FR-10 | Features and capabilities | Operational and statutory reporting | Lines 142-146 | Vision / scope / problem statement, Functional requirements, User stories with acceptance criteria | Functional implementation |
| AC-03 | Acceptance conditions | Required report outputs | Lines 142-146 | User stories with acceptance criteria, QA test scenarios / use cases | Verification |