# Public Deployment Risk Register

Public deployment remains `PUBLIC_DEPLOYMENT_NOT_APPROVED`.

## PDR-001

- Risk category: AI dentist misunderstanding.
- Risk description: A public visitor could misunderstand the portfolio as an AI dentist product.
- Severity: high.
- Likelihood: medium.
- Current mitigation: workflow infrastructure positioning, non-diagnostic boundaries, and a homepage public boundary note.
- Required mitigation before deployment: final human review of homepage and project-page copy.
- Status: mitigated and monitored; not eliminated.

## PDR-002

- Risk category: Clinical service misunderstanding.
- Risk description: Public readers could interpret the site as offering clinical service or patient advice.
- Severity: high.
- Likelihood: medium.
- Current mitigation: no forms, no patient intake, no clinical care offer, and clear public-facing disclaimers on Home, Safety, Contact, and Disclaimer.
- Required mitigation before deployment: final human review of public-facing boundary copy.
- Status: mitigated and monitored; not eliminated.

## PDR-003

- Risk category: Second-opinion misunderstanding.
- Risk description: Public readers could misread preparation workflows as second-opinion workflows.
- Severity: high.
- Likelihood: medium.
- Current mitigation: second-opinion framing is blocked in safety language and Taiwan Dental Prep now includes a public boundary note.
- Required mitigation before deployment: final human review of Taiwan Dental Prep and project pages for preparation-only framing.
- Status: mitigated and monitored; not eliminated.

## PDR-004

- Risk category: Taiwan Dental Prep service framing.
- Risk description: Taiwan Dental Prep could be read as a clinical service, treatment planning, or patient-facing dental consultation.
- Severity: high.
- Likelihood: medium.
- Current mitigation: appointment-preparation and document-organization framing plus explicit no-service, no-second-opinion, no-treatment-recommendation boundary language.
- Required mitigation before deployment: final human review for Taiwan Dental Prep service-framing risk.
- Status: mitigated and monitored; not eliminated.

## PDR-005

- Risk category: U.S. licensure implication.
- Risk description: Public readers could infer U.S. dental licensure or U.S. clinical care.
- Severity: high.
- Likelihood: low.
- Current mitigation: profile states no U.S. licensure claim and now clarifies it is not a U.S. clinical care offer or patient-facing service.
- Required mitigation before deployment: final public-facing licensure boundary audit.
- Status: mitigated and monitored; not eliminated.

## PDR-006

- Risk category: Real patient contact / inquiry risk.
- Risk description: Public visitors could attempt to send real patient information.
- Severity: high.
- Likelihood: medium.
- Current mitigation: no forms, no inputs, no contact capture, and Contact page rejects patient data, dental records, imaging files, treatment plans, and personal health information.
- Required mitigation before deployment: final Contact page boundary audit.
- Status: mitigated and monitored; not eliminated.

## PDR-007

- Risk category: Public indexing risk.
- Risk description: A public deployment may be indexed by search engines and seen outside intended hiring/research audiences.
- Severity: medium.
- Likelihood: medium.
- Current mitigation: no deployment configured.
- Required mitigation before deployment: explicit indexing and sharing decision.
- Status: mitigated and monitored; not eliminated.

## PDR-008

- Risk category: Lack of final public-facing disclaimer.
- Risk description: Private-review boundary language may not be sufficient for public readers.
- Severity: high.
- Likelihood: medium.
- Current mitigation: multiple not-for-real-patient-use statements exist.
- Required mitigation before deployment: final public-facing disclaimer pass.
- Status: mitigated and monitored; not eliminated.

## PDR-009

- Risk category: Overemphasis on healthcare terms.
- Risk description: Healthcare terms could make the site sound more clinical than intended.
- Severity: medium.
- Likelihood: medium.
- Current mitigation: wording polish changed broad clinical labels to dental workflow wording.
- Required mitigation before deployment: public-copy audit for positive-positioning language.
- Status: mitigated and monitored; not eliminated.

## PDR-010

- Risk category: Clinical AI Review Harness naming ambiguity.
- Risk description: The project name may sound more clinical than the bounded prototype intends.
- Severity: medium.
- Likelihood: medium.
- Current mitigation: paired subtitle `Workflow Safety Review Harness for Synthetic Drafts` and project-page boundary note stating it is not a medical benchmark, clinical validation, or diagnostic evaluation system.
- Required mitigation before deployment: final check that subtitle pairing appears in all public references.
- Status: mitigated and monitored; not eliminated.

## PDR-011

- Risk category: Accidental future addition of forms or analytics.
- Risk description: Future public-deployment work could add forms, analytics, tracking, or integrations.
- Severity: high.
- Likelihood: low.
- Current mitigation: blocked actions register prohibits these additions.
- Required mitigation before deployment: technical static-site audit and explicit no-forms/no-analytics confirmation.
- Status: mitigated and monitored; not eliminated.

## Final Approval Review Note

All listed risks are treated as mitigated and monitored, not eliminated. The final approval decision permits a separate static public deployment implementation gate, but it does not approve real patient use, forms, analytics, backend services, integrations, clinical claims, or patient-facing medical use.
