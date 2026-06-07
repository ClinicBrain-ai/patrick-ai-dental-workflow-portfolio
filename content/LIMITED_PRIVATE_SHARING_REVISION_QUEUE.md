# Limited Private Sharing Revision Queue

## Purpose

A local-only queue of possible revisions based on private reviewer feedback.

Do not include real reviewer data, real contact details, employer-sensitive details, confidential reviewer comments, real patient data, or private company information.

## Revision Template

Copy one block per possible revision.

## Limited Private Sharing Feedback Collection Buckets

Use these buckets for future anonymized reviewer feedback. Do not store real reviewer names, contact details, employer-sensitive details, confidential reviewer comments, real patient data, or private company information.

### Pending Reviewer Feedback

- Status: `open`
- Use for newly received anonymized reviewer feedback that has not yet been triaged.
- Record reviewer label only, such as `Trusted Reviewer C`.

### Minor Wording Edits

- Status: `open`
- Use for small language changes that improve clarity without changing positioning or safety boundaries.
- Examples: wording repetition, overly broad dental workflow phrasing, or unclear project-card explanation.

### Major Positioning Concerns

- Status: `watch`
- Use if a reviewer misunderstands Patrick as offering clinical care, acting as an AI dentist, building diagnostic AI, recommending treatment, providing second opinions, or offering teledentistry.
- These concerns should trigger a separate revision gate before more sharing.

### Deployment Blockers

- Status: `blocked`
- Public deployment remains `PUBLIC_DEPLOYMENT_NOT_APPROVED`.
- Use this bucket for anything that would need to be resolved before any future deployment approval discussion.

### Public-Readiness Blockers

- Status: `blocked`
- Use this bucket for public-facing risks such as real data, real PHI, external assets, reviewer identity exposure, clinical service claims, licensure implications, production-readiness claims, or medical device readiness claims.

## Portfolio Documentation Polish Addressed Items

The following Trusted Reviewer C items were addressed during the Portfolio Documentation Polish Gate:

- `REV-013`: Add a short `What I can do for a team` section. Status: `addressed`.
- `REV-014`: Create or polish architecture overview. Status: `addressed`.
- `REV-015`: Create or polish safety card. Status: `addressed`.
- `REV-016`: Create or polish synthetic dataset card. Status: `addressed`.
- `REV-017`: Create or polish workflow-safety benchmark-style card. Status: `addressed`.

Public deployment remains `PUBLIC_DEPLOYMENT_NOT_APPROVED`.

The portfolio remains local-only and static-only. No backend, analytics, forms, scripts, tracking, database, external integrations, external URLs, real PHI, real patient data, reviewer personal data, or clinical claims were added.

## Portfolio Documentation Polish Review Decision Recorded

- Decision: `APPROVE_FOR_CONTINUED_LIMITED_PRIVATE_SHARING`
- Approved next gate: `Continued Limited Private Sharing Gate`
- What I can do for a team: `reviewed`
- Architecture overview: `reviewed`
- Safety card: `reviewed`
- Synthetic dataset card: `reviewed`
- Workflow-safety benchmark-style card: `reviewed`
- Public deployment: `still blocked`

Public deployment remains `PUBLIC_DEPLOYMENT_NOT_APPROVED`.

## Trusted Reviewer C Prioritized Revision Items

### Revision ID

`REV-013`

### Source Feedback Theme

`Role-fit context`

### Page Or File Affected

`profile.html`, `handoff.html`, or future portfolio summary card.

### Proposed Change

Add a short `What I can do for a team` section.

### Safety Reason

Keep role-fit language focused on dental workflow infrastructure, human review, synthetic-first evaluation, and safety boundaries.

### Portfolio Clarity Reason

Helps hiring, research, AI healthcare product, and health data infrastructure reviewers map the portfolio to team needs.

### Priority

`high`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-014`

### Source Feedback Theme

`Portfolio-facing summary artifacts`

### Page Or File Affected

Future documentation polish packet.

### Proposed Change

Create or polish an architecture overview.

### Safety Reason

Architecture overview must remain local-only, synthetic-first, non-diagnostic, and human-in-the-loop.

### Portfolio Clarity Reason

Makes the four-project stack easier to understand as one coherent workflow system.

### Priority

`high`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-015`

### Source Feedback Theme

`Portfolio-facing summary artifacts`

### Page Or File Affected

Future documentation polish packet.

### Proposed Change

Create or polish a safety card.

### Safety Reason

Keeps public-readiness, clinical-use, real-data, integration, and patient-facing automation boundaries explicit.

### Portfolio Clarity Reason

Gives reviewers a compact safety summary without adding more warnings to the main path.

### Priority

`high`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-016`

### Source Feedback Theme

`Portfolio-facing summary artifacts`

### Page Or File Affected

Future documentation polish packet.

### Proposed Change

Create or polish a synthetic dataset card.

### Safety Reason

Clarifies that examples are synthetic-first and not real patient data, real PHI, or real imaging files.

### Portfolio Clarity Reason

Helps AI healthcare and research reviewers understand the evidence base and its limits.

### Priority

`medium`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-017`

### Source Feedback Theme

`Portfolio-facing summary artifacts`

### Page Or File Affected

Future documentation polish packet.

### Proposed Change

Create or polish a workflow-safety benchmark-style card.

### Safety Reason

Must be framed as workflow safety coverage, not medical benchmarking, clinical validation, clinical quality scoring, diagnosis scoring, or treatment quality scoring.

### Portfolio Clarity Reason

Makes the Clinical AI Review Harness easier for AI safety and evaluation reviewers to understand.

### Priority

`medium`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-018`

### Source Feedback Theme

`Naming caution`

### Page Or File Affected

`projects.html`, `projects/clinical-ai-review-harness.html`, and related portfolio docs.

### Proposed Change

Keep `Clinical AI Review Harness` subtitle paired with workflow safety wording: `Workflow Safety Review Harness for Synthetic Drafts`.

### Safety Reason

Prevents the project from being read as clinical validation or medical benchmarking.

### Portfolio Clarity Reason

Keeps the strongest project legible for AI healthcare, research, and hiring audiences.

### Priority

`medium`

### Decision

`ongoing guardrail`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-019`

### Source Feedback Theme

`Taiwan Dental Prep caution`

### Page Or File Affected

`projects/taiwan-dental-prep.html`, `projects.html`, and related portfolio docs.

### Proposed Change

Keep Taiwan Dental Prep language away from second opinion or treatment-decision framing.

### Safety Reason

Prevents the project from being read as diagnosis, treatment recommendation, second opinion, teledentistry, or patient-facing dental service.

### Portfolio Clarity Reason

Preserves the project as conservative appointment-preparation and document-organization workflow infrastructure.

### Priority

`high`

### Decision

`ongoing guardrail`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-020`

### Source Feedback Theme

`Deployment caution`

### Page Or File Affected

Portfolio process.

### Proposed Change

Continue limited private sharing; public deployment remains blocked.

### Safety Reason

Reviewer C supports limited private sharing but not public deployment, real data use, clinical use, integrations, or patient-facing automation.

### Portfolio Clarity Reason

Keeps next steps focused on documentation polish rather than technical expansion.

### Priority

`high`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

## Repeated Reviewer Pattern Monitored Items

### Revision ID

`REV-009`

### Source Feedback Theme

`Naming caution`

### Page Or File Affected

`projects.html` and `projects/clinical-ai-review-harness.html`

### Proposed Change

Monitor Clinical AI Review Harness naming and keep it paired with `Workflow Safety Review Harness for Synthetic Drafts`.

### Safety Reason

The subtitle keeps the project framed as workflow safety review for synthetic drafts rather than clinical validation.

### Portfolio Clarity Reason

Avoids unnecessary renaming unless future reviewers still get stuck on the name.

### Priority

`low`

### Decision

`deferred`

### Trigger

Revise only if two or more future reviewers still get stuck on the name even with the subtitle.

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-010`

### Source Feedback Theme

`Taiwan Dental Prep caution`

### Page Or File Affected

`projects/taiwan-dental-prep.html`, `projects.html`, and related private-sharing materials.

### Proposed Change

Monitor Taiwan Dental Prep framing.

### Safety Reason

Prevents the project from being read as a clinical service, second opinion, diagnosis, treatment recommendation, or patient-facing dental service.

### Portfolio Clarity Reason

Preserves the project as a conservative appointment-preparation workflow.

### Priority

`medium`

### Decision

`ongoing guardrail`

### Trigger

Revise immediately if any reviewer reads it as a clinical service, second opinion, treatment recommendation, or patient-facing dental service.

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-011`

### Source Feedback Theme

`Safety boundary clarity`

### Page Or File Affected

Primary path pages.

### Proposed Change

Avoid adding more prohibited-claim warnings to the main path.

### Safety Reason

Reviewers confirm safety boundaries are already clear enough.

### Portfolio Clarity Reason

More warnings may make the primary path too heavy.

### Priority

`low`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-012`

### Source Feedback Theme

`Deployment caution`

### Page Or File Affected

Portfolio process.

### Proposed Change

Pause new development gates.

### Safety Reason

Repeated reviewer pattern confirms limited private sharing readiness only; deployment and real-use paths remain blocked.

### Portfolio Clarity Reason

Further changes should be based on repeated concrete feedback only.

### Priority

`high`

### Decision

`accepted`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

## Trusted Reviewer B Completed Polish Items

### Revision ID

`REV-005`

### Source Feedback Theme

`Wording polish`

### Page Or File Affected

`profile.html`

### Proposed Change

Fix repeated profile wording from `Dentist from Taiwan. Dentist building...` to one concise positioning sentence.

### Safety Reason

No safety concern; clarity improvement only.

### Portfolio Clarity Reason

Removes distracting repetition from the primary profile page.

### Priority

`low`

### Decision

`completed`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-006`

### Source Feedback Theme

`Wording polish`

### Page Or File Affected

`profile.html`

### Proposed Change

Replace `Clinical Domain Translation` with `Dental Workflow Translation`.

### Safety Reason

Keeps positive positioning centered on dental workflow infrastructure.

### Portfolio Clarity Reason

Makes the capability label more precise for hiring/research reviewers.

### Priority

`low`

### Decision

`completed`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-007`

### Source Feedback Theme

`Wording polish`

### Page Or File Affected

`profile.html`

### Proposed Change

Replace `Treatment-planning-adjacent information organization` with `Appointment-preparation and document-organization context`.

### Safety Reason

Avoids positive positioning near treatment recommendation language.

### Portfolio Clarity Reason

Keeps the capability concrete and workflow-oriented.

### Priority

`low`

### Decision

`completed`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-008`

### Source Feedback Theme

`Project page clarity`

### Page Or File Affected

`projects.html`

### Proposed Change

Add compact `Why this matters for AI teams` lines to the four flagship project cards.

### Safety Reason

Lines remain non-diagnostic and do not imply clinical validation, production readiness, patient-facing automation, or real patient use.

### Portfolio Clarity Reason

Makes the Projects page more persuasive for hiring/research reviewers.

### Priority

`low`

### Decision

`completed`

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

## Trusted Reviewer A Revision Items

### Revision ID

`REV-002`

### Source Feedback Theme

`English polish`

### Page Or File Affected

`narrative.html`

### Proposed Change

Review any positive-positioning use of "clinical workflow realities" and consider safer wording such as "dental workflow realities."

### Safety Reason

Reduces chance that positive positioning sounds broader than dental workflow infrastructure.

### Portfolio Clarity Reason

Keeps the portfolio centered on dental workflow context for hiring/research reviewers.

### Priority

`low`

### Decision

`completed`

### Notes

Anonymized theme from Trusted Reviewer A. Completed during Limited Sharing Wording Polish Gate. No real reviewer data.

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-003`

### Source Feedback Theme

`Project page clarity`

### Page Or File Affected

`projects.html`

### Proposed Change

Further simplify Projects page if future reviewers still find it index-like.

### Safety Reason

No safety concern; clarity improvement only.

### Portfolio Clarity Reason

Helps trusted hiring/research reviewers focus on the four flagship projects first.

### Priority

`low`

### Decision

`accepted`

### Notes

Anonymized theme from Trusted Reviewer A. Projects page now includes compact AI-team relevance lines; further simplification remains optional only if future reviewers repeat the theme. No real reviewer data.

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

### Revision ID

`REV-004`

### Source Feedback Theme

`Navigation / reviewer path`

### Page Or File Affected

`content/LIMITED_PRIVATE_SHARING_MESSAGE_TEMPLATES.md`

### Proposed Change

In manual private sharing messages, explicitly tell reviewers to start with: handoff.html -> profile.html -> walkthrough.html.

### Safety Reason

No safety concern; reinforces local-only private review path.

### Portfolio Clarity Reason

Helps trusted reviewers reach the clearest positioning and evidence pages quickly.

### Priority

`low`

### Decision

`accepted`

### Notes

Apply in future message-template polish only if needed. No real reviewer data.

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

## Private Feedback Synthesis Status

The Private Feedback Synthesis Gate did not identify any must-fix item before wider limited private sharing.

Current synthesis classification:

- Must fix before wider private sharing: none.
- Useful but not urgent: Projects page simplification, wording polish around dental workflow realities, and private reviewer path reminders.
- Do not change yet: Walkthrough, core positioning, and safety boundaries.
- Blocked until public-readiness decision: public launch copy, deployment instructions, public contact workflow, and public announcement messaging.
- Blocked until legal/privacy/clinical review: real patient data handling, PHI handling, clinical validation claims, regulatory compliance claims, and clinical care language.

### Revision ID

`REV-001`

### Source Feedback Theme

`Projects page clarity`

### Page Or File Affected

`projects.html`

### Proposed Change

Further reduce secondary links if future reviewers still find the page index-like.

### Safety Reason

No safety concern; clarity improvement only.

### Portfolio Clarity Reason

Helps hiring/research reviewers focus on the four flagship projects first.

### Priority

`low`

Options: `low / medium / high`

### Decision

`deferred`

Options: `pending / accepted / deferred / rejected / completed`

### Notes

Placeholder example only. No real reviewer data.

### Constraint Check

- [x] No deploy.
- [x] No real data.
- [x] No clinical claims.
- [x] No external integrations.

## Empty Revision Block

### Revision ID

`REV-___`

### Source Feedback Theme

`Anonymized theme only`

### Page Or File Affected

`Local file path`

### Proposed Change

`Describe local-only content or structure change.`

### Safety Reason

`Describe safety rationale or state no safety concern.`

### Portfolio Clarity Reason

`Describe reviewer clarity benefit.`

### Priority

`low / medium / high`

### Decision

`pending / accepted / deferred / rejected / completed`

### Notes

`No real reviewer data.`

### Constraint Check

- [ ] No deploy.
- [ ] No real data.
- [ ] No clinical claims.
- [ ] No external integrations.
