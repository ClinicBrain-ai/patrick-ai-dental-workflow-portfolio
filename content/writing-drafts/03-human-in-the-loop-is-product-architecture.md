# Human-In-The-Loop Is Product Architecture

Human-in-the-loop is not just a disclaimer at the bottom of a page. In safe AI workflow design, it has to be part of the product architecture.

AI can draft, organize, flag, and route. Human reviewers approve, reject, edit, escalate, or request more information.

The boundary is the workflow state model.

## A Safer Review Queue

A simple review lifecycle might look like:

```text
drafted -> needs_review -> edited -> approved_for_manual_send
```

The draft is not final. The `needs_review` state makes manual review mandatory. The `edited` state records that a human changed the draft. The `approved_for_manual_send` state means a human may handle the communication manually outside the prototype. It does not mean automatic sending.

## Interruption Matters

High-risk outputs should be interrupted.

Another lifecycle might look like:

```text
safety_interrupted -> needs_review -> escalated
```

This matters when a draft contains language that sounds like a diagnosis, treatment recommendation, prognosis, image interpretation, automatic second opinion, or final patient-facing medical advice.

The system should not smooth over that risk. It should stop, label the issue, and route the item to a human.

## Manual Approval Is The Boundary

Final patient-facing communication must be manually approved. A safe workflow should make it difficult for sensitive drafts to bypass review.

That means:

- Drafts should be visibly non-final.
- Review status should be explicit.
- Risk flags should be visible.
- Escalation should be supported.
- Automatic patient-facing final messages should remain blocked.

Human-in-the-loop is not decoration. It is the architecture that prevents workflow support from becoming unsafe automation.
