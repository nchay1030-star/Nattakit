DRAFT
  │
  ▼
SUBMITTED
  │
  ▼
PRE-SCREENING
  │
  ▼
TECHNICAL_REVIEW
  │
  ▼
MANAGER_APPROVAL
  │
  ▼
DIRECTOR_APPROVAL
  │
  ▼
DIGITAL_SIGN
  │
  ▼
ISSUED
  │
  ▼
ACTIVE
ชื่อผู้ขอ
เลขบัตรประชาชน
องค์กร
ประเภทใบอนุญาต
เอกสารแนบ
DRAFT
Applicant
Required Documents
Format Validation
PDPA Consent
Duplicate Check
SUBMITTED
เอกสารครบหรือไม่
ลายเซ็นถูกต้องหรือไม่
ข้อมูลตรงกับฐานทะเบียนหรือไม่
PRE-SCREENING
RETURN_FOR_CORRECTION
GIS License
Energy License
Mining License
Environmental License
Qualification Score
Training Records
License Requirements
Compliance Check
TECHNICAL_REVIEW
Supervisor
Approve
Reject
Request Revision
TECHNICAL_REVIEW
      │
      ▼
MANAGER_APPROVAL
Director
วงเงินสูง
ใบอนุญาตสำคัญ
หนังสือรับรองพิเศษ
DIRECTOR_APPROVAL
Authorized Signer
Generate PDF

Generate SHA256

PKI Digital Signature

Timestamp

Blockchain Registration
DIGITAL_SIGN
License Number

LIC-2026-000001
QR Verification
R2 Storage
D1 Database
ISSUED
ACTIVE
ใบอนุญาตมีผล
15 ต.ค. 2569

หมดอายุ
15 ต.ค. 2571
ACTIVE
   │
   ▼
RENEW_REQUEST
   │
   ▼
REVIEW
   │
   ▼
APPROVED
   │
   ▼
ACTIVE
ACTIVE
   │
   ▼
INVESTIGATION
   │
   ▼
HEARING
   │
   ▼
REVOKED
ข้อมูลเท็จ
หมดคุณสมบัติ
ฝ่าฝืนเงื่อนไข
คำสั่งทางปกครอง
export enum LicenseStatus {
  DRAFT="DRAFT",
  SUBMITTED="SUBMITTED",
  PRE_SCREENING="PRE_SCREENING",
  TECHNICAL_REVIEW="TECHNICAL_REVIEW",
  MANAGER_APPROVAL="MANAGER_APPROVAL",
  DIRECTOR_APPROVAL="DIRECTOR_APPROVAL",
  DIGITAL_SIGN="DIGITAL_SIGN",
  ISSUED="ISSUED",
  ACTIVE="ACTIVE",
  RENEW_REQUEST="RENEW_REQUEST",
  EXPIRED="EXPIRED",
  REVOKED="REVOKED"
}
Audit Trail
ทุกการเปลี่ยนสถานะบันทึกทันที
{
  "licenseId":"LIC-2026-000001",
  "oldStatus":"TECHNICAL_REVIEW",
  "newStatus":"MANAGER_APPROVAL",
  "actor":"manager01@gov.go.th",
  "timestamp":"2026-10-15T10:30:00Z",
  "ip":"203.x.x.x"
}
ใบอนุญาตทั้งหมด

Active
Expired
Pending Review
Pending Approval
Renewal Request
Revoked

Approval SLA

Officer KPI

Director Approval Queue

Blockchain Verification Status
Applicant
    │
    ▼
Officer Review
    │
    ▼
Technical Committee
    │
    ▼
Manager Approval
    │
    ▼
Director Approval
    │
    ▼
Digital Signature
    │
    ▼
Blockchain Register
    │
    ▼
Issue License
    │
    ▼
Active License
    │
    ▼
Renew / Revoke / Expire
