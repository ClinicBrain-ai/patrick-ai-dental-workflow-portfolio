# Synthetic Portfolio Artifact Index

## Purpose

This folder contains static, synthetic-only portfolio artifacts for Patrick Chen's Dental AI Workflow Safety Stack.

The artifacts make the portfolio more concrete by showing example packet structures, review rubrics, fictional review results, queue-state lifecycles, preparation packets, safety checklists, and safe rewrite patterns.

## Artifact List

- `dental-case-packet-schema-v0.1.synthetic.json`
  - Supports: Dental Case Packet / AI-ready Dental Data Layer
  - Purpose: Describes the intended structure of a synthetic dental case packet.

- `dental-case-packet-example.synthetic.json`
  - Supports: Dental Case Packet / AI-ready Dental Data Layer
  - Purpose: Provides one fictional packet example using synthetic fields only.

- `clinical-ai-review-harness-rubric.synthetic.md`
  - Supports: Clinical AI Review Harness
  - Purpose: Defines non-clinical review categories for checking AI-assisted workflow outputs against safety boundaries.

- `clinical-ai-review-harness-result.synthetic.json`
  - Supports: Clinical AI Review Harness
  - Purpose: Shows one fictional evaluation result for a non-final workflow draft.

- `ai-native-dental-phone-layer-review-queue.synthetic.json`
  - Supports: AI Native Dental Phone Layer
  - Purpose: Shows a fictional review queue item moving through manual review states.

- `taiwan-dental-prep-packet.synthetic.md`
  - Supports: Taiwan Dental Prep / 台灣安心看牙
  - Purpose: Provides a fictional preparation packet for organizing materials before an in-person Taiwan dental visit.

- `human-in-the-loop-review-checklist.md`
  - Supports: All flagship projects
  - Purpose: Provides a reusable human-review checklist.

- `prohibited-claims-and-safe-rewrites.md`
  - Supports: All flagship projects
  - Purpose: Shows clearly marked unsafe examples and safer preparation-oriented rewrites.

## Safety Note

All examples are fictional, synthetic, local-only, and not for clinical use.

These artifacts are portfolio materials only. They do not contain real PHI, real patient records, real imaging files, real clinic details, real contact information, diagnosis, treatment recommendations, prognosis, image interpretation, automatic second opinions, teledentistry, clinical validation claims, or automatic patient-facing final messages.
