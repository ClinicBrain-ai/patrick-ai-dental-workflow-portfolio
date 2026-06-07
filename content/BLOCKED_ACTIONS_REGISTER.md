# Blocked Actions Register

| Blocked action | Why it is blocked | Future approval required | Risk reason |
| --- | --- | --- | --- |
| Public deployment | The portfolio has not been approved for public release. | Separate explicit human deployment approval gate. | Deployment-risk |
| GitHub Pages deployment | No deployment setup has been approved. | Separate explicit human deployment approval gate. | Deployment-risk |
| Analytics | Tracking is outside the local-only portfolio scope. | Explicit analytics/privacy approval. | Privacy |
| Contact forms | Forms may collect user data. | Explicit data collection and privacy approval. | Privacy |
| Real user intake | The portfolio is not an intake system. | Explicit product, privacy, and safety approval. | Safety/privacy |
| Real patient data | The portfolio is synthetic-first only. | Explicit privacy/legal/clinical approval. | Privacy/legal/clinical |
| Real PHI | PHI is blocked in all gates. | Explicit privacy/legal/clinical approval. | Privacy/legal/clinical |
| Real imaging files | Image files are not used; metadata labels only. | Explicit privacy/legal/clinical approval. | Privacy/clinical |
| Real clinic details | Clinic details could imply real-world service relationships. | Explicit content and privacy approval. | Privacy/legal |
| Backend services | The site is static-only. | Separate architecture and safety approval. | Deployment-risk |
| Database integrations | Databases imply data collection/storage. | Explicit privacy and architecture approval. | Privacy/deployment-risk |
| Payment integration | Payment implies commercial transaction handling. | Explicit legal/product approval. | Legal/deployment-risk |
| Gmail / Line / Supabase / Calendar / email integrations | External integrations transmit or store data. | Explicit integration approval. | Privacy/deployment-risk |
| Automated patient-facing messages | The portfolio requires manual review and no automatic final messages. | Explicit clinical/product/legal approval. | Safety/legal/clinical |
| Clinical claims | The portfolio is not a clinical service or clinical validation product. | Explicit clinical/legal approval. | Clinical/legal |
| Diagnosis | Diagnosis is blocked. | Explicit clinical/legal approval. | Clinical/legal |
| Treatment recommendation | Treatment recommendation is blocked. | Explicit clinical/legal approval. | Clinical/legal |
| Prognosis | Outcome prediction is blocked. | Explicit clinical/legal approval. | Clinical/legal |
| Image interpretation | Image interpretation is blocked. | Explicit clinical/legal approval. | Clinical/legal |
| Automatic second opinion | Automatic second-opinion positioning is blocked. | Explicit clinical/legal approval. | Clinical/legal |
| Teledentistry | Teledentistry positioning is blocked. | Explicit clinical/legal approval. | Clinical/legal |
| Clinical validation claims | The portfolio is not clinically validated. | Explicit clinical validation evidence and legal review. | Clinical/legal |
| U.S. dental licensure claims | No U.S. licensure is claimed. | Explicit credential/legal review. | Legal/clinical |
| Clinical care offer | The portfolio is not a clinical care offer. | Explicit credential/legal/clinical approval. | Legal/clinical |

## Public Deployment Review Note

Public deployment is being reviewed, but it remains blocked until a separate explicit approval gate. The current readiness review does not create deployment files, GitHub Pages configuration, GitHub Actions, analytics, forms, contact capture, external integrations, or public deployment approval.

Public copy hardening has been completed for final review, but public deployment remains blocked until a separate explicit approval gate.

## Static Public Deployment Final Approval Note

Static public deployment implementation may be discussed in a separate implementation gate. All real patient use, real user intake, patient data submission, dental record upload, forms, analytics, backend services, integrations, payment, email sending, diagnosis, treatment recommendation, image interpretation, second opinion, teledentistry, clinical validation, medical device claims, U.S. dental licensure claims, and clinical care offers remain blocked.

## Static Public Deployment Implementation Note

Static public deployment implementation documentation has been prepared, but actual public deployment was not performed. GitHub push, GitHub Pages enablement, deployment commands, deployment scripts, GitHub Actions, analytics, forms, contact capture, backend services, external integrations, real user intake, real patient data, and clinical claims remain blocked unless separately and explicitly approved.
