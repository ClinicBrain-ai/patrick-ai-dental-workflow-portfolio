# Public Copy Boundary Audit

## Pages Reviewed

- `index.html`
- `profile.html`
- `contact.html`
- `safety.html`
- `walkthrough.html`
- `projects.html`
- `projects/taiwan-dental-prep.html`
- `projects/clinical-ai-review-harness.html`
- `narrative.html`
- `DISCLAIMER.md`

## Risk Phrases Checked

Checked public-facing copy for wording that could imply:

- Clinical service.
- AI dentist.
- Second-opinion service.
- Treatment recommendation service.
- Teledentistry service.
- Real patient intake.
- Deployed medical product.
- Clinical validation.
- U.S. dental licensure.
- Patient-facing medical advice.

## Boundary Notes Added

- Homepage now includes a compact public boundary note near the hero copy.
- Profile now states that it describes portfolio and workflow-infrastructure work, not a U.S. clinical care offer or patient-facing service.
- Contact page now states there is no contact form, no inquiry collection, and no patient data submission path.
- Safety page now states that public deployment, if ever approved, would still not make the portfolio a clinical service, real patient intake system, or deployed medical product.
- Walkthrough now explicitly frames the scenario as a fictional synthetic case with no real PHI, real patient data, real imaging files, clinical service, or real patient use.
- Projects page now frames the projects as static portfolio prototypes and artifacts, not active clinical services or production products.

## Taiwan Dental Prep Framing Check

Taiwan Dental Prep is now framed as:

- Preparation-oriented.
- Document-organization oriented.
- Appointment-preparation oriented.
- Human-reviewed concept.
- Conservative commercial exploration concept.

It is explicitly not framed as:

- Clinical service.
- Second-opinion service.
- Treatment recommendation service.
- Diagnosis.
- Price guarantee.
- Timeline guarantee.
- Patient intake.
- Teledentistry.
- Patient-facing dental advice.

## Clinical AI Review Harness Naming Check

Clinical AI Review Harness remains paired with:

`Workflow Safety Review Harness for Synthetic Drafts`

The project page now also states that the harness evaluates workflow-safety boundaries in synthetic drafts and is not a medical benchmark, clinical validation, or diagnostic evaluation system.

## Contact Page Data-Submission Warning Check

Contact page now states:

- No contact form is provided.
- The site does not collect inquiries.
- Do not submit patient information.
- Do not submit dental records, X-rays, CBCT files, photos, treatment plans, or personal health information.
- The portfolio is for professional discussion only, not patient care or clinical advice.

No email address, phone number, form, external contact link, or contact capture was added.

## U.S. Licensure / Clinical Care Implication Check

Profile and related public pages preserve the boundary that the portfolio does not claim U.S. dental licensure, clinical care, clinical validation, production readiness, or medical device readiness.

## Remaining Risks

- Public readers may still skim past disclaimers.
- Clinical AI Review Harness naming should remain paired with its safer subtitle.
- Taiwan Dental Prep should continue to be monitored so it does not drift toward service or second-opinion framing.
- Public deployment remains blocked until a separate final approval gate.

## Decision

`PUBLIC_COPY_HARDENED_FOR_FINAL_REVIEW`
