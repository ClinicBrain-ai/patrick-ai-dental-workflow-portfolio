# Private Feedback Revision Priorities

## Purpose

This local-only document classifies safe revision priorities based on anonymized trusted private reviewer feedback.

It does not publish changes, approve deployment, collect reviewer identities, or create clinical, regulatory, product-market, deployment, or real-user readiness claims.

## Current Status

- `LIMITED_PRIVATE_SHARING_READY`
- `TRUSTED_REVIEWER_CONFIRMED_PRIVATE_SHARING_FIT`
- `PUBLIC_DEPLOYMENT_NOT_APPROVED`
- `NOT_FOR_REAL_PATIENT_USE`
- `SYNTHETIC_FIRST_ONLY`

## Must Fix Before Wider Private Sharing

Current classification: none.

Reason:

- The recorded trusted reviewer decision is `SAFE_FOR_LIMITED_PRIVATE_HIRING_RESEARCH_SHARING`.
- No major risky claims were found.
- No immediate confusion point blocks limited private sharing.

## Useful But Not Urgent

### PRI-001: Projects Page Simplification

- Source theme: Projects page clarity.
- Affected file: `projects.html`.
- Possible revision: Further simplify Projects if future anonymized reviewers still find it slightly crowded, abstract, or index-like.
- Priority: low.
- Status: deferred.
- Safety note: No safety concern; clarity improvement only.

### PRI-002: Positive-Positioning Wording Polish

- Source theme: English polish / claim-boundary caution.
- Affected file: `narrative.html` or any future copy where the phrase appears.
- Possible revision: Review positive-positioning use of `clinical workflow realities` and prefer safer wording such as `dental workflow realities`.
- Priority: low.
- Status: deferred.
- Safety note: Keeps positioning centered on dental workflow infrastructure rather than broad clinical claims.

### PRI-003: Manual Reviewer Path Reminder

- Source theme: navigation / reviewer path.
- Affected files: private sharing materials only.
- Possible revision: Keep telling private reviewers to start with `handoff.html -> profile.html -> walkthrough.html`.
- Priority: low.
- Status: accepted for private sharing guidance.
- Safety note: Local-only guidance; no public claim added.

## Do Not Change Yet

- Do not rewrite the Walkthrough; it is currently the strongest evidence page.
- Do not dilute the main positioning sentence.
- Do not reduce safety boundaries unless future reviewers identify a specific repetition problem.
- Do not expand project claims beyond synthetic, reviewable, human-in-the-loop workflow infrastructure.
- Do not add new public-facing pages from this synthesis alone.

## Blocked Until Public-Readiness Decision

- Public launch copy.
- Public deployment instructions.
- GitHub Pages setup.
- Search/indexing language.
- Public contact workflow.
- Public announcement messaging.
- Product-market validation language.
- Deployment readiness language.
- Real-user onboarding language.

## Blocked Until Legal/Privacy/Clinical Review

- Real patient data handling.
- PHI handling.
- Real medical data examples.
- Real imaging files.
- Clinical validation claims.
- Diagnosis, treatment recommendation, prognosis, image interpretation, automatic second opinion, teledentistry, or patient-facing final medical advice language.
- Medical device readiness language.
- Regulatory compliance language.
- U.S. dental licensure language.
- Clinical care offer language.

## Revision Queue Sync

The current low-priority queue items remain appropriate:

- `REV-002`: wording polish around dental workflow realities.
- `REV-003`: Projects page simplification if future reviewers repeat the theme.
- `REV-004`: private sharing path reminder.

No new urgent revision item is required from the current trusted reviewer feedback.
