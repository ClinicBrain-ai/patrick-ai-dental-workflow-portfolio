# Static Public Deployment Implementation Plan

## 1. Deployment Scope

Allowed scope:

- Static site only.
- No backend.
- No analytics.
- No forms.
- No JavaScript.
- No external integrations.
- No real patient use.
- No clinical service.
- No contact capture.

Current local context:

- The current folder is not a git repository.
- No remote repository is configured in this folder.
- No deployment command was run.
- No public URL was created.

## 2. Recommended Hosting Path

Safest recommended path:

Option A: GitHub Pages from a static repository root.

Manual user steps only:

1. Create or confirm a GitHub repository named `[GitHub Repository Name]`.
2. Copy the static files into the repository root.
3. Review the copied files locally before committing.
4. Commit locally only after review.
5. Push only after explicit user approval.
6. Enable GitHub Pages manually in `[GitHub Pages Settings]` if desired.
7. Record `[Public URL After Manual Deployment]` only after manual deployment and post-deployment review.

Do not perform the push from this gate.

Do not enable GitHub Pages automatically from this gate.

Do not create a remote from this gate.

## 3. Pre-Deployment Checks

Before any manual deployment, run or confirm:

- Local link check.
- External URL check.
- Script / form / input check.
- PHI / contact detail scan.
- Disclaimer check.
- Homepage boundary check.
- Contact page no-intake warning check.
- Taiwan Dental Prep boundary check.
- Clinical AI Review Harness subtitle check.
- Public deployment final approval decision check.

Required final approval basis:

- `APPROVE_STATIC_PUBLIC_DEPLOYMENT_IMPLEMENTATION_GATE`

## 4. Deployment Constraints

Blocked items:

- No GitHub Actions.
- No analytics.
- No contact forms.
- No backend.
- No database.
- No payment.
- No real user intake.
- No clinical service claims.
- No patient data upload.
- No dental record upload.
- No X-ray / CBCT / photo upload.
- No email sending.
- No external integrations.

## 5. Manual Deployment Instructions

Manual static hosting instructions:

1. Confirm the local folder still passes the static smoke checks.
2. Create or open `[GitHub Repository Name]`.
3. Copy the static portfolio files into the repository root.
4. Confirm `index.html`, `styles.css`, `projects/`, `assets/`, `content/`, `README.md`, and `DISCLAIMER.md` are present.
5. Confirm no package files, build scripts, workflow files, forms, analytics, backend code, or external integrations were added.
6. Commit locally after manual review.
7. Push only after explicit approval.
8. Enable GitHub Pages manually in `[GitHub Pages Settings]`.
9. Open `[Public URL After Manual Deployment]`.
10. Complete `content/STATIC_PUBLIC_DEPLOYMENT_POST_DEPLOYMENT_CHECKLIST.md`.

This plan does not deploy the portfolio.
