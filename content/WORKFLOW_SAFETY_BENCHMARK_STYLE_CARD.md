# Workflow Safety Benchmark-style Artifact

## Purpose

This is a workflow safety benchmark-style artifact.

It is not a clinical benchmark, not clinical validation, not medical model performance evidence, and not a diagnosis or treatment-quality benchmark.

## What It Evaluates

It evaluates workflow safety coverage for synthetic AI-assisted drafts and review items.

It focuses on whether outputs stay inside explicit boundaries, preserve provenance awareness, acknowledge missing information, avoid prohibited output patterns, and route sensitive outputs to human review.

## What It Does Not Evaluate

It does not evaluate:

- Diagnosis accuracy.
- Treatment quality.
- Prognosis accuracy.
- Image interpretation quality.
- Clinical correctness.
- Clinical safety.
- Patient outcomes.
- Medical model performance.
- Regulatory compliance.

## Risk Categories

Example workflow safety risk categories include:

- Diagnostic overreach.
- Treatment recommendation overreach.
- Prognosis or success-rate claim.
- Image interpretation violation.
- Unsupported inference.
- Missing-information blindness.
- Provenance failure.
- Human-review routing failure.
- Unsafe reassurance.
- Administrative distortion.
- Privacy or PHI risk.
- Patient-facing final advice.
- Cost or timeline guarantee.

## Failure Modes

Example workflow safety failure modes include:

- Direct diagnosis-like wording.
- Treatment recommendation-like wording.
- Image interpretation-like wording.
- Unsupported clinical inference.
- Missing information ignored.
- Provenance omitted.
- High-risk output without human review.
- Unsafe reassurance.
- Price reasonableness judgment.
- Timeline guarantee.
- Final patient-facing medical reply.

## Routing Outcomes

Example routing outcomes include:

- Allow low-risk information organization.
- Allow reviewer-facing draft only.
- Require human review.
- Safety interrupt.
- Block real data or PHI.
- Block patient-facing final advice.

## Human Review Requirements

Sensitive, high-risk, unsupported, missing-source, or boundary-risk outputs require human review.

Human review required does not imply treatment is required.

## Provenance Checks

Provenance checks are traceability checks only.

Provenance missing or provenance conflict does not decide clinical truth.

## Missing-information Checks

Missing-information checks identify workflow gaps.

They do not diagnose, recommend treatment, estimate prognosis, or determine clinical sufficiency.

## Prohibited-output Checks

Prohibited-output checks flag workflow boundary risks such as diagnosis-like wording, treatment recommendation-like wording, prognosis-like claims, image interpretation-like language, patient-facing final advice, and automatic second-opinion framing.

## Why This Is Not Clinical Validation

This artifact does not validate clinical correctness, clinical safety, diagnosis, treatment, prognosis, image interpretation, or patient outcomes.

## Why This Is Not Medical Model Performance Evidence

This artifact does not compare models, rank models, score model performance, or measure clinical accuracy.

## Why This Is Not A Diagnosis Or Treatment-quality Benchmark

This artifact does not score diagnosis quality or treatment quality.

It only describes workflow safety coverage for synthetic examples.

