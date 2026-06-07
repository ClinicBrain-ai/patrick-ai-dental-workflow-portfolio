# Static Public Deployment Final Checklist

This checklist does not itself deploy the site.

## Static-Site Constraints

- [x] Static HTML/CSS only.
- [x] No backend.
- [x] No runtime behavior.
- [x] No JavaScript.
- [x] No scripts.
- [x] No forms.
- [x] No inputs.
- [x] No analytics.
- [x] No tracking automation.
- [x] No database.
- [x] No external integrations.

## Public-Copy Boundary Constraints

- [x] Homepage includes a public boundary note.
- [x] Public copy reads as portfolio, not product launch.
- [x] Projects are framed as synthetic portfolio prototypes and artifacts.
- [x] Walkthrough is framed as fictional synthetic content.
- [x] Disclaimer is hardened for public readers.

## Clinical Boundary Constraints

- [x] Not clinical advice.
- [x] Not a dental service.
- [x] Not an AI dentist.
- [x] Not a second-opinion service.
- [x] Not teledentistry.
- [x] Not a diagnosis system.
- [x] Not a treatment recommendation system.
- [x] Not clinical validation.
- [x] Not a medical device claim.
- [x] Not for real patient use.

## Privacy / Data Constraints

- [x] No real PHI.
- [x] No real patient records.
- [x] No real imaging files.
- [x] No real clinic details.
- [x] No real contact details.
- [x] No real reviewer identities.
- [x] No personal data collection.

## Contact Page Constraints

- [x] No contact form.
- [x] No contact capture.
- [x] No email address.
- [x] No phone number.
- [x] No external contact link.
- [x] Clear warning not to submit patient information.
- [x] Clear warning not to submit dental records, X-rays, CBCT files, photos, treatment plans, or personal health information.

## Taiwan Dental Prep Constraints

- [x] Framed as synthetic preparation-oriented workflow concept.
- [x] Framed as appointment-preparation and document organization.
- [x] Not framed as public service.
- [x] Not framed as second-opinion service.
- [x] Not framed as treatment recommendation service.
- [x] Not framed as patient intake.
- [x] Not framed as patient-facing dental advice.

## Clinical AI Review Harness Constraints

- [x] Paired with `Workflow Safety Review Harness for Synthetic Drafts`.
- [x] Not framed as medical benchmark.
- [x] Not framed as clinical validation.
- [x] Not framed as diagnostic evaluation system.
- [x] Not framed as medical accuracy evaluation.

## Deployment Scope Constraints

- [x] No GitHub Pages config created in this gate.
- [x] No GitHub Actions created in this gate.
- [x] No deployment files created in this gate.
- [x] No external URLs added in this gate.
- [x] Future implementation gate must remain static-only unless separately reviewed.

## Post-Deployment Monitoring Expectations

If a later implementation gate deploys the site, monitor for:

- Unexpected patient inquiries.
- Misunderstanding as clinical service.
- Misunderstanding as AI dentist or second-opinion service.
- Taiwan Dental Prep service-framing drift.
- Clinical AI Review Harness naming confusion.
- Accidental addition of forms, analytics, scripts, backend, or contact capture.

Public deployment remains blocked until a separate implementation gate actually performs and verifies deployment.
