# Human-in-the-Loop for High-Risk Algorithmic Decisions

## Purpose
Establish mandatory human oversight requirements for high-risk algorithmic and automated decision-making processes to ensure lawful, fair, and accountable outcomes, particularly when decisions may materially affect legal status, financial standing, or fundamental rights.

## Legal Basis
- ICCPR Articles 2(3) and 14 (effective remedy; fair hearing and due process).
- ECHR Articles 6 and 13 (right to a fair hearing; effective remedy).

## Scope & Definitions (High-Risk Criteria)
This module applies to automated or semi-automated decisions that produce material legal, financial, or rights-related effects. A decision is high-risk if it meets one or more of the following criteria:
- Determines, limits, or denies access to essential services, benefits, employment, housing, education, healthcare, or legal status.
- Creates or materially alters obligations, liabilities, or sanctions, including fines, penalties, or enforcement actions.
- Generates outcomes that may implicate liberty, security, nondiscrimination, or other protected rights.
- Uses sensitive or protected data categories, or combines multiple data sources in ways that increase error, bias, or privacy risk.
- Exhibits high uncertainty, low explainability, or significant potential for disparate impact.

## Mandatory Human Oversight Triggers
Human review is required before a decision is finalized when any of the following conditions apply:
- The decision meets any high-risk criteria in the Scope & Definitions section.
- The model output is used as the primary basis for adverse action.
- The system flags low confidence, conflict, or anomalous outputs.
- The affected individual submits a contestation, appeal, or request for review.
- A periodic threshold review indicates elevated error rates or disparate impact.

## Decision Authority & Accountability
- Final decision authority must rest with a qualified human decision-maker who is empowered to override the system output.
- Decision-makers must have access to relevant context, evidence, and model rationale sufficient to exercise independent judgment.
- Each decision must identify the responsible decision-maker and their role.
- Oversight responsibility must be documented in governance records and assigned to a named accountable owner.

## Procedural Safeguards (Reason-Giving, Reviewability)
- Provide timely, clear, and meaningful reasons for decisions, including the role of automated components.
- Ensure affected individuals can access a review mechanism that is independent, impartial, and capable of providing an effective remedy.
- Maintain a structured appeal process with defined timelines, documentation requirements, and outcome notifications.
- Ensure the review body can access the data and rationale used in the automated component.

## Outputs & Audit Trail
- Record system inputs, model versioning, confidence scores, and decision outcomes.
- Document human review steps, overrides, and rationale for acceptance or divergence from model outputs.
- Preserve logs for audit, compliance, and remediation, including retention periods aligned with legal requirements.
- Generate periodic oversight reports summarizing error rates, overrides, bias indicators, and remediation actions.

## Use Cases
- Automated eligibility determinations for public benefits or social services.
- Credit scoring, loan approvals, or insurance underwriting decisions.
- Hiring, promotion, or termination decisions informed by algorithmic assessments.
- Risk scoring for law enforcement, immigration, or security-related determinations.
- Automated disciplinary actions in education or employment contexts.

## Compliance & Risk Positioning
- Classify covered workflows as high-risk and subject to enhanced governance controls.
- Require pre-deployment risk assessments, including bias and impact testing.
- Mandate continuous monitoring with escalation pathways for material deviations.
- Treat failure to implement human oversight as a critical compliance risk requiring immediate remediation.
