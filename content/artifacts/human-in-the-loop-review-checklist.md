# Human-In-The-Loop Review Checklist

Reusable checklist for safe review of synthetic AI-assisted dental workflow artifacts.

## Before Drafting

- Confirm the example is synthetic-only.
- Confirm no real PHI, patient records, clinic details, contact details, or real imaging files are present.
- Confirm the intended output is workflow support, not clinical advice.
- Identify missing information before drafting.
- Identify source labels that must be preserved.

## During AI-Assisted Drafting

- Keep all wording non-final.
- Preserve source labels and uncertainty notes.
- Mark missing information instead of guessing.
- Avoid diagnosis, treatment recommendations, prognosis, image interpretation, second opinions, and medical advice.
- Avoid administrative promises, price guarantees, timeline guarantees, or appointment guarantees.

## Before Manual Approval

- Check that every key statement is grounded in a source label or marked as uncertain.
- Check that sensitive outputs route to human review.
- Rewrite final-sounding text into preparation-oriented language.
- Confirm that no automatic patient-facing final message will be sent.

## Before Patient-Facing Communication

- Confirm the message has been manually reviewed.
- Confirm the communication channel is approved outside this static prototype.
- Confirm the message does not include diagnosis, treatment recommendation, prognosis, image interpretation, or second-opinion positioning.
- Confirm the message is not automatically generated or automatically sent by this portfolio.

## Escalation Conditions

- Any possible diagnosis or treatment recommendation.
- Any image interpretation.
- Any unsupported inference from missing information.
- Any real PHI or real patient record.
- Any unclear source provenance.
- Any request for clinical judgment.

## Never-Allowed Outputs

- Diagnosis.
- Treatment recommendation.
- Prognosis or success-rate claim.
- Image interpretation.
- Automatic second opinion.
- Teledentistry positioning.
- Clinical validation claim.
- Automatic patient-facing final message.
- Price guarantee or timeline guarantee.
- Real patient data, real PHI, or real imaging files.
