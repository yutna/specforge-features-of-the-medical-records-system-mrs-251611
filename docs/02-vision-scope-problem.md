# Vision / Scope / Problem Statement

## Problem statement

Baseline requirements for a Medical Records System (MRS) assembled from the provided source note. The described scope includes patient registration, outpatient and inpatient records, pharmacy, laboratory, imaging, document management, appointments, billing and insurance, reporting, integrations, compliance, and key operational quality requirements.

## Scope statement

Requirements baseline for an end-to-end medical records platform supporting patient administration, clinical documentation, diagnostics, medication management, billing, reporting, external integrations, compliance, security, reliability, and usability.

## Planning profile

| Area | Value |
| --- | --- |
| Primary actors | 0 |
| In-scope capabilities | 10 |
| Documented assumptions | 0 |
| Known risks | 1 |
| Open questions | 2 |

## Business goals

- None captured in the current baseline.

## Primary actors

- None captured in the current baseline.

## In-scope capabilities

- **FR-01 — Patient registration and profile management**
  - Support core patient administration capabilities: - Register patients - Search patients by HN, national ID, name, or phone number - Detect duplicate patients - Enter demographic data - Update patient profiles - Manage allergy records - Manage emergency contact information
- **FR-02 — Outpatient medical record management**
  - Support outpatient care documentation and ordering: - Create OPD visits - Record vital signs - Document chief complaint, HPI, PMH, family history, medication history, and physical examination - Record ICD-10 diagnoses - Enter medication orders - Enter lab and X-ray orders - Document treatment plans - Generate medical certificates
- **FR-03 — Inpatient admission and inpatient record management**
  - Support inpatient care activities: - Manage patient admissions - Document nursing notes - Document doctor progress notes - Chart intake and output - Monitor continuous vital signs - Manage Medication Administration Records (MAR) - Enter lab and X-ray orders during admission - Prepare discharge summaries with ICD-10 and ICD-9-CM - Document referrals
- **FR-04 — Medication and pharmacy management**
  - Support medication and pharmacy operations: - Enter medication orders - Check drug interactions - Check allergies - Manage dispensing workflow - Track lot numbers and expiry dates - Manage drug inventory - Produce drug utilization reporting
- **FR-05 — Laboratory order and result management**
  - Support laboratory operations: - Enter laboratory orders - Print barcodes - Enter laboratory results - Integrate laboratory results with medical records - Display laboratory results graphically - Report turnaround time (TAT)
- **FR-06 — Imaging and radiology management**
  - Support imaging-related capabilities: - Create imaging orders for X-ray, CT, and MRI - Enter radiologist reports - Attach images in DICOM or JPEG formats
- **FR-07 — Clinical document management**
  - Support storage and retrieval of clinical documents: - Upload documents - Store consent forms - Store medical certificates - Store referral documents
- **FR-08 — Appointment scheduling and reminder management**
  - Support appointment operations: - Schedule patient appointments - Send SMS/LINE reminders - Manage doctor schedules - Report no-shows
- **FR-09 — Billing and insurance management**
  - Support financial processing: - Calculate charges - Manage medication, procedure, and room charges - Verify insurance eligibility - Generate invoices and receipts - Produce revenue reporting
- **FR-10 — Operational and statutory reporting**
  - Support reporting for operational monitoring and external obligations: - Daily patient census reports - ICD-10 disease reports - Drug utilization reports - OPD/IPD statistical reports - Reports for the provincial health office / NHSO

## Assumptions affecting scope

- None captured in the current baseline.

## Key delivery risks

- **RSK-01 — Integration contracts and interface details are undefined**
  - Multiple external integrations are required, but the source does not define interface standards, message formats, ownership, or environment dependencies. This creates delivery and testing risk.

## Clarifications still needed

- **Q-01 — RBAC role definitions are not specified**
  - The source requires RBAC but does not define the user roles, permissions, or segregation-of-duties model needed to implement and test access control.
- **Q-02 — SNOMED CT support remains optional**
  - The source marks SNOMED CT support as optional, so scope, priority, and implementation depth are not yet fixed.