# Private Human Review Packet

## Purpose

This local-only private human review packet helps a trusted reviewer evaluate positioning, clarity, safety boundaries, and audience fit before any external sharing, hiring/research use, or separate deployment approval discussion.

It does not approve public deployment. It does not approve clinical use. Deployment requires a separate explicit human approval gate.

## Current Status

- `LOCAL_ONLY_PORTFOLIO_READY_FOR_PRIVATE_HUMAN_REVIEW`
- `PENDING_PRIVATE_HUMAN_REVIEW`
- `PUBLIC_DEPLOYMENT_NOT_APPROVED`
- `REQUIRES_SEPARATE_EXPLICIT_HUMAN_APPROVAL_GATE`
- `NOT_FOR_REAL_PATIENT_USE`
- `NOT_CLINICALLY_VALIDATED`
- `SYNTHETIC_FIRST_ONLY`

## Suggested Review Order

1. Home: `index.html`
2. Profile: `profile.html`
3. Hiring & Research Narrative: `narrative.html`
4. Projects: `projects.html`
5. Stack: `stack.html`
6. Safety: `safety.html`
7. Writing: `writing.html`
8. Review Checklist: `review.html`
9. Final Audit: `audit.html`
10. Artifact Index: `content/artifacts/ARTIFACT_INDEX.md`
11. Writing Drafts Index: `content/writing-drafts/WRITING_DRAFTS_INDEX.md`
12. Portfolio Overview Thumbnail: `assets/screenshots/portfolio-overview-thumbnail.html`

## Reviewer Questions

### Positioning

- Is Patrick's positioning clear within 30 seconds?
- Does the portfolio explain why a dentist is building AI workflow infrastructure?
- Does it avoid sounding like an AI dentist or clinical service?

### Audience Fit

- Would this make sense to a U.S. AI healthcare hiring manager?
- Would this make sense to a research collaborator?
- Does it clearly show clinical domain translation into AI workflow design?

### Safety

- Are boundaries clear and repeated enough without becoming distracting?
- Are any claims too close to diagnosis, treatment recommendation, prognosis, image interpretation, second opinion, teledentistry, clinical validation, medical device readiness, U.S. licensure, or clinical care?
- Are any pages at risk of being misunderstood as patient-facing clinical advice?

### Evidence

- Do the projects, artifacts, writing drafts, and thumbnails support the main narrative?
- Are the artifacts concrete enough?
- Are there gaps that should be fixed before private hiring/research sharing?

### Clarity

- Is the English professional and natural?
- Are any sections too repetitive?
- Are any pages too long?
- Is the relationship between the four projects easy to understand?

## Files Requiring Review

- `index.html`
- `profile.html`
- `narrative.html`
- `projects.html`
- `stack.html`
- `safety.html`
- `writing.html`
- `review.html`
- `audit.html`
- `private-review.html`
- All four project detail pages.
- All writing drafts.
- All synthetic artifacts.
- All visual thumbnails.
- `README.md`
- `DISCLAIMER.md`
- `AGENTS.md`

## Decision Options

- `NEEDS_MAJOR_REVISION`
- `NEEDS_MINOR_REVISION`
- `SAFE_FOR_PRIVATE_HIRING_RESEARCH_SHARING`
- `SAFE_TO_DISCUSS_DEPLOYMENT_SEPARATELY`
- `NOT_SUITABLE_FOR_EXTERNAL_SHARING`

`SAFE_TO_DISCUSS_DEPLOYMENT_SEPARATELY` does not approve deployment.

## Blocked Actions

- Public deployment.
- GitHub Pages deployment.
- Analytics.
- Contact forms.
- Real user intake.
- Real patient data.
- Real PHI.
- Real imaging files.
- Backend services.
- Database integrations.
- Payment integration.
- Gmail / Line / Supabase / Calendar / email integrations.
- Automated patient-facing messages.
- Clinical claims.
- Diagnosis.
- Treatment recommendation.
- Prognosis.
- Image interpretation.
- Automatic second opinion.
- Teledentistry.
- Clinical validation claims.
- U.S. dental licensure claims.
- Clinical care offer.
