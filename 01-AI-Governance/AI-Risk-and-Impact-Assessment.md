
# AI Risk and Impact Assessment

**Author:** Dr. Olajumoke Bello, PhD  
**Version:** 1.0  
**Classification:** Public Portfolio Sample  
**Status:** Illustrative AI Risk and Impact Assessment Deliverable

## 1. Purpose

This document establishes a structured approach for identifying, evaluating, treating and monitoring risks associated with AI systems.

The assessment considers cybersecurity, privacy, fairness, reliability, accountability, third-party dependencies and potential impacts on individuals and organisations.

It supports risk-based decisions throughout the AI system lifecycle and aligns with the principles of NIST AI RMF and ISO/IEC 42001.

**Guiding Principle: Protect to Enable**

AI risk assessment should enable responsible innovation through proportionate safeguards, accountable decisions and continuous assurance.

---

## 2. Assessment Objectives

The objectives are to:

- Understand the AI system's intended purpose and operational context.
- Identify stakeholders and potentially affected individuals.
- Identify cybersecurity, privacy, operational and societal risks.
- Evaluate threats, vulnerabilities and potential harmful outcomes.
- Assess existing safeguards and control effectiveness.
- Determine inherent and residual risks.
- Define risk treatment and remediation requirements.
- Support deployment approval and risk acceptance decisions.
- Establish monitoring and reassessment requirements.

---

## 3. Assessment Scope

This methodology may be applied to:

- Internally developed AI systems
- Third-party AI applications
- Generative AI and large language model systems
- AI-enabled business processes
- AI systems processing personal or sensitive information
- AI systems integrated with enterprise applications
- AI systems supporting consequential decisions

Assessment depth should be proportionate to system criticality, data sensitivity, potential harm, external exposure and regulatory obligations.

---

## 4. Illustrative AI System Profile

The following fictional example demonstrates how the assessment methodology may be applied.

### AI System Identifier

AI-SYS-001

### System Name

Enterprise AI Knowledge Assistant

### Intended Purpose

Provide authorised employees with AI-generated answers based on approved internal knowledge documents.

### Business Objectives

- Improve information retrieval.
- Reduce time spent searching internal documentation.
- Support employee productivity.
- Improve consistency of knowledge access.

### System Type

Generative AI application using a large language model and retrieval-augmented generation (RAG).

### Intended Users

Authorised employees.

### Data Sources

- Approved internal knowledge documents
- Organisational procedures
- Internal guidance and reference materials

### Potentially Sensitive Information

Internal business information and potentially personal information contained in source documents.

### External Dependencies

- Third-party AI model provider
- Cloud hosting services
- Identity and access management services
- Document storage and retrieval components

### System Boundary

The example assumes the AI assistant provides informational responses only.

It does not independently approve transactions, modify customer accounts or execute consequential business decisions.

### Assessment Assumptions

The architecture, safeguards and operating arrangements are illustrative.

No real system has been tested or assessed.

---

## 5. Stakeholder and Impact Analysis

### Employees

Potential benefits:

- Faster access to information
- Improved productivity
- More consistent responses

Potential harms:

- Exposure of information beyond authorised access
- Misleading or inaccurate responses
- Overreliance on AI-generated information

### Organisation

Potential benefits:

- Operational efficiency
- Improved knowledge accessibility
- Reduced administrative workload

Potential harms:

- Data leakage
- Security incidents
- Regulatory or contractual non-compliance
- Operational disruption
- Reputational damage

### Customers and Other Individuals

Potential harms may arise where personal or confidential information is disclosed, misused or inaccurately represented.

### Third-Party Providers

Potential impacts include contractual disputes, security incidents, service disruption and assurance failures.

---

## 6. Risk Assessment Methodology

The assessment uses a qualitative five-point likelihood and impact scale.

The numerical model is illustrative and should be replaced with the organisation's approved risk methodology before operational use.

### Likelihood Scale

| Score | Rating | Description |
|---|---|---|
| 1 | Rare | Unlikely under expected conditions |
| 2 | Unlikely | Possible but not expected |
| 3 | Possible | Credible scenario |
| 4 | Likely | Expected under relevant conditions |
| 5 | Almost Certain | Highly probable or recurring |

### Impact Scale

| Score | Rating | Description |
|---|---|---|
| 1 | Insignificant | Minimal harm or disruption |
| 2 | Minor | Limited and recoverable impact |
| 3 | Moderate | Material but manageable impact |
| 4 | Major | Significant operational, legal or individual harm |
| 5 | Severe | Critical or potentially widespread harm |

### Risk Calculation

**Risk Score = Likelihood × Impact**

### Risk Rating

| Score | Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

### Assessment Principles

- Inherent risk represents exposure before the evaluated safeguards.
- Residual risk represents exposure after considering safeguards and their effectiveness.
- Likelihood and impact must be supported by documented rationale.
- Control effectiveness should be supported by appropriate evidence.
- Uncertainty and assessment limitations must be recorded.
- Risk scores should not replace qualitative assessment of potential harm.
- Risks exceeding organisational tolerance must be escalated.

---

## 7. AI Risk Identification

The following illustrative risks have been identified for AI-SYS-001.

### AI-RISK-001 — Prompt Injection

**Risk Description:** Malicious instructions embedded in retrieved documents may influence the assistant's behaviour.

**Potential Impact:** Unauthorised disclosure, misleading responses or attempted security control bypass.

**Inherent Likelihood:** 4 — Likely

**Inherent Impact:** 4 — Major

**Inherent Risk Score:** 16 — High

**Proposed Safeguards:**

- Treat retrieved content as untrusted input.
- Apply document access controls.
- Restrict model permissions.
- Test prompt injection scenarios.
- Validate outputs for sensitive information exposure.
- Monitor suspicious activity.

**Illustrative Residual Likelihood:** 3 — Possible

**Illustrative Residual Impact:** 4 — Major

**Illustrative Residual Risk Score:** 12 — High

**Treatment:** Further mitigation and testing required.

**Risk Owner:** AI System Owner

**Status:** Illustrative — Not Tested

### AI-RISK-002 — Sensitive Information Disclosure

**Risk Description:** The assistant may expose confidential or personal information to unauthorised users.

**Potential Impact:** Privacy violations, contractual breaches and reputational damage.

**Inherent Likelihood:** 3 — Possible

**Inherent Impact:** 5 — Severe

**Inherent Risk Score:** 15 — High

**Proposed Safeguards:**

- Enforce user authentication.
- Apply document-level authorisation.
- Restrict retrieval to permitted content.
- Implement data classification.
- Test cross-user and cross-role access.
- Establish logging and incident escalation.

**Illustrative Residual Likelihood:** 2 — Unlikely

**Illustrative Residual Impact:** 5 — Severe

**Illustrative Residual Risk Score:** 10 — High

**Treatment:** Validate access controls and escalate residual risk.

**Risk Owner:** AI System Owner

**Status:** Illustrative — Not Tested

### AI-RISK-003 — Inaccurate or Misleading Outputs

**Risk Description:** The AI assistant may generate inaccurate answers or unsupported claims.

**Potential Impact:** Incorrect employee decisions, operational errors and loss of trust.

**Inherent Likelihood:** 4 — Likely

**Inherent Impact:** 3 — Moderate

**Inherent Risk Score:** 12 — High

**Proposed Safeguards:**

- Provide source references where feasible.
- Evaluate response accuracy.
- Apply content quality checks.
- Communicate system limitations.
- Require human verification for consequential uses.
- Monitor recurring response failures.

**Illustrative Residual Likelihood:** 3 — Possible

**Illustrative Residual Impact:** 3 — Moderate

**Illustrative Residual Risk Score:** 9 — Moderate

**Treatment:** Mitigate and monitor.

**Risk Owner:** AI System Owner

**Status:** Illustrative — Not Tested

### AI-RISK-004 — Third-Party AI Provider Risk

**Risk Description:** A model or hosting provider may introduce security, privacy, availability or governance risks.

**Potential Impact:** Data exposure, service disruption, contractual non-compliance or loss of operational assurance.

**Inherent Likelihood:** 3 — Possible

**Inherent Impact:** 4 — Major

**Inherent Risk Score:** 12 — High

**Proposed Safeguards:**

- Conduct supplier due diligence.
- Review security assurance evidence.
- Evaluate data retention and processing arrangements.
- Assess subcontractor dependencies.
- Define contractual security obligations.
- Monitor material supplier changes.

**Illustrative Residual Likelihood:** 2 — Unlikely

**Illustrative Residual Impact:** 4 — Major

**Illustrative Residual Risk Score:** 8 — Moderate

**Treatment:** Mitigate, monitor and obtain assurance evidence.

**Risk Owner:** AI System Owner

**Supporting Function:** Third-Party Risk Management

**Status:** Illustrative — Not Tested

### AI-RISK-005 — Excessive User Reliance

**Risk Description:** Employees may treat AI-generated responses as authoritative without appropriate verification.

**Potential Impact:** Poor decisions, process failures or inappropriate actions.

**Inherent Likelihood:** 4 — Likely

**Inherent Impact:** 3 — Moderate

**Inherent Risk Score:** 12 — High

**Proposed Safeguards:**

- Publish acceptable use requirements.
- Provide user training.
- Define prohibited and restricted uses.
- Display system limitations.
- Establish human review requirements.
- Monitor misuse and significant errors.

**Illustrative Residual Likelihood:** 2 — Unlikely

**Illustrative Residual Impact:** 3 — Moderate

**Illustrative Residual Risk Score:** 6 — Moderate

**Treatment:** Mitigate and monitor.

**Risk Owner:** AI System Owner

**Status:** Illustrative — Not Tested

---

## 8. Consolidated AI Risk Register

| Risk ID | Risk Area | Inherent Risk | Illustrative Residual Risk | Treatment |
|---|---|---|---|---|
| AI-RISK-001 | Prompt Injection | High (16) | High (12) | Further mitigation |
| AI-RISK-002 | Information Disclosure | High (15) | High (10) | Validate and escalate |
| AI-RISK-003 | Inaccurate Outputs | High (12) | Moderate (9) | Mitigate and monitor |
| AI-RISK-004 | Third-Party Provider | High (12) | Moderate (8) | Supplier assurance |
| AI-RISK-005 | Excessive Reliance | High (12) | Moderate (6) | Training and oversight |

**Important:** Residual scores are hypothetical estimates, not validated findings.

The listed safeguards are proposed controls. Their effectiveness has not been established through testing.

---

## 9. AI Impact Assessment

The assessment should consider both organisational risk and potential impacts on individuals.

### Privacy Impact

- Could personal information be exposed?
- Are access permissions appropriate?
- Is data processing limited to authorised purposes?
- Are retention and deletion arrangements defined?

### Security Impact

- Can malicious instructions influence the AI system?
- Can users access information outside their permissions?
- Are integrations and external dependencies appropriately restricted?
- Can security events be detected and investigated?

### Fairness and Human Impact

- Could outputs disadvantage particular users or groups?
- Are relevant accessibility requirements considered?
- Could inaccurate information cause material harm?
- Is human review available where needed?

### Reliability and Operational Impact

- Are outputs sufficiently accurate for intended use?
- How are errors detected and corrected?
- What happens when the model provider is unavailable?
- Are fallback arrangements documented?

### Accountability Impact

- Is there an accountable AI System Owner?
- Are deployment and risk acceptance authorities defined?
- Are decisions documented?
- Are escalation and reassessment triggers established?

---

## 10. Control Effectiveness Assessment

Proposed safeguards should be evaluated using suitable evidence.

### Evidence Sources

- Security architecture documentation
- Identity and access-control configurations
- AI security test results
- Prompt injection test records
- Data access validation results
- Supplier assurance reports
- Privacy and impact assessments
- Monitoring and incident records
- Remediation and retesting evidence

### Control Evaluation Ratings

**Effective:** Evidence demonstrates the control meets defined requirements.

**Partially Effective:** The control operates but has identified weaknesses or limitations.

**Ineffective:** The control does not meet its intended requirements.

**Not Tested:** Insufficient evidence is available to determine effectiveness.

For AI-SYS-001, all proposed safeguards remain **Not Tested**.

---

## 11. Risk Treatment and Remediation

Risks should be assigned treatment actions proportionate to severity and organisational tolerance.

### Treatment Options

- **Mitigate:** Implement or strengthen safeguards.
- **Avoid:** Discontinue an unacceptable use case.
- **Transfer or Share:** Allocate appropriate responsibilities or financial exposure without removing organisational accountability.
- **Accept:** Formally approve residual risk within authorised limits.

### Illustrative Remediation Priorities

**Priority 1 — Prompt Injection and Data Disclosure**

- Validate document-level access controls.
- Conduct authorised prompt injection testing.
- Evaluate sensitive information exposure.
- Restrict unnecessary model and application permissions.

**Priority 2 — Output Reliability**

- Define accuracy evaluation criteria.
- Test representative knowledge queries.
- Implement source referencing and user verification guidance.

**Priority 3 — Third-Party Assurance**

- Review model provider security evidence.
- Validate contractual data processing requirements.
- Assess supplier and subcontractor dependencies.

**Priority 4 — Human Oversight**

- Publish acceptable use requirements.
- Train employees.
- Define prohibited and high-impact uses.
- Establish escalation procedures.

### Remediation Tracking Fields

- Risk ID
- Action Description
- Assigned Owner
- Priority
- Target Completion Date
- Evidence Required
- Validation Method
- Status
- Closure Decision

---

## 12. Risk Acceptance and Deployment Decision

Deployment decisions should consider:

- Inherent and residual risks
- Evidence of control effectiveness
- Unresolved vulnerabilities
- Privacy and regulatory obligations
- Third-party assurance findings
- Human oversight arrangements
- Monitoring readiness
- Organisational risk appetite

### Illustrative Decision

**AI-SYS-001 Deployment Status: Not Approved — Further Assurance Required**

### Decision Rationale

- Prompt injection exposure has not been validated.
- Sensitive-information access controls have not been tested.
- Third-party assurance evidence has not been reviewed.
- Proposed residual risk estimates remain unverified.
- Two illustrative residual risks remain rated High.

This is an example of a governance decision, not an actual operational approval.

### Conditions for Reconsideration

- Complete required security testing.
- Validate access-control effectiveness.
- Review supplier assurance evidence.
- Update residual risk assessments.
- Resolve or formally escalate unacceptable risks.
- Obtain approval from the designated governance authority.

---

## 13. Continuous Monitoring and Reassessment

AI risks should be reviewed throughout the system lifecycle.

### Monitoring Activities

- Review AI security incidents and near misses.
- Monitor unauthorised access attempts.
- Review prompt injection testing results.
- Track sensitive information exposure.
- Monitor accuracy and reliability indicators.
- Review supplier changes.
- Track remediation progress.
- Review control effectiveness.

### Reassessment Triggers

- Model updates or replacements
- New data sources
- Changes to intended use
- New external integrations
- Material architecture changes
- New AI suppliers or subcontractors
- Significant security incidents
- Emerging vulnerabilities or attack techniques
- Regulatory or contractual changes
- Evidence that existing safeguards are ineffective

### Reassessment Decision

Where a material change invalidates the assumptions supporting an earlier approval, renewed assessment and authorisation should be required.

---

## 14. NIST AI RMF Alignment

### GOVERN

- Assign accountable owners.
- Define risk appetite and approval authority.
- Establish policies and escalation processes.
- Maintain governance evidence.

### MAP

- Define AI system purpose and context.
- Identify stakeholders and affected individuals.
- Map data, dependencies and foreseeable harms.
- Document assumptions and system boundaries.

### MEASURE

- Assess identified risks.
- Evaluate safeguards.
- Conduct AI security testing.
- Validate control effectiveness.
- Document limitations and uncertainty.

### MANAGE

- Prioritise and treat risks.
- Assign remediation owners.
- Escalate unacceptable risks.
- Monitor control performance.
- Reassess following material changes.

These functions are interconnected and iterative rather than a rigid linear sequence.

---

## 15. Expected Outcomes

This methodology should support:

- Clear AI system risk visibility
- Consistent risk identification and evaluation
- Better understanding of potential impacts
- Defined control and remediation requirements
- Evidence-based risk acceptance decisions
- Stronger supplier assurance
- Appropriate human oversight
- Continuous risk monitoring and reassessment
- Responsible AI deployment aligned with organisational objectives

---

## 16. Conclusion

AI risk assessment should not be treated as a one-time scoring exercise.

Effective assurance requires understanding the AI system's purpose, dependencies, potential harms, existing safeguards and evidence of control effectiveness.

Risk scores should inform, rather than replace, accountable governance decisions.

**Protect to Enable — Identify, Assess, Treat and Continuously Validate AI Risks.**

---

## Disclaimer

This document is an illustrative, sanitised professional portfolio example.

The AI system, risks, scores, controls and deployment decision are fictional and have not been validated against a real implementation.

This document does not contain confidential client or employer information.

The approach must be tailored to organisational risk appetite, system context, applicable legal obligations and approved governance procedures.

This is an implementation interpretation informed by NIST AI RMF and ISO/IEC 42001 principles, not an official framework publication or certification.
