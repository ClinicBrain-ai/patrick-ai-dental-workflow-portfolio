# Synthetic Dataset Card

## Dataset Purpose

This synthetic dataset card describes the local-only fixture set used to make Patrick Chen's dental AI workflow safety portfolio reviewable.

The fixtures support workflow safety evaluation, provenance-aware case organization, and human-in-the-loop review design without using real patient data.

## Synthetic Fixture Types

- Dental Case Packet fixtures.
- Harness candidate output fixtures.
- Harness report fixtures.
- Review queue and workflow examples.
- Taiwan Dental Prep appointment-preparation examples.

## Dental Case Packet Fixtures

Dental Case Packet fixtures demonstrate structured, source-grounded dental workflow context.

They include synthetic case notices, fictional document labels, missing-information checklists, provenance-style records, reviewer notes, and out-of-scope boundaries.

## Harness Candidate Output Fixtures

Harness candidate output fixtures represent synthetic drafts or review items used to test workflow safety boundaries.

They can exercise boundary risk, unsupported inference, missing-information awareness, provenance failure, prohibited output patterns, and human-review routing.

## Harness Report Fixtures

Harness report fixtures demonstrate static workflow safety report examples.

They are not generated reports, not clinical validation, not medical model benchmarks, and not patient-facing medical advice.

## What The Fixtures Test

The fixtures test workflow safety patterns such as:

- Boundary-risk wording.
- Unsupported inference.
- Missing-information blindness.
- Provenance gaps or conflicts.
- Prohibited output checks.
- Human review routing.
- Safe reviewer-facing organization.

## What The Fixtures Do Not Test

The fixtures do not test:

- Clinical correctness.
- Diagnosis accuracy.
- Treatment quality.
- Prognosis accuracy.
- Image interpretation.
- Real patient communication.
- Medical model performance.
- Regulatory compliance.

## Data Boundary

- No real patient data.
- No real PHI.
- No real imaging files.
- No real clinic details.
- No real contact details.

## Validation Boundary

This fixture set is not clinical validation.

It is not a medical model benchmark.

It does not prove clinical safety, production readiness, medical device readiness, or real-world patient suitability.

## Relationship To Future Workflow Safety Evaluation

The synthetic fixture set can support future local-only workflow safety evaluation work by making boundary cases explicit before any real data, deployment, integration, or patient-facing workflow is considered.

