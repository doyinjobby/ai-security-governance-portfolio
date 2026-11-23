
# AI Third-Party Supplier Assurance Assessment

**Author:** Dr. Olajumoke Bello, PhD  
**Version:** 1.0  
**Classification:** Public Portfolio Sample  
**Status:** Illustrative AI Supplier Assurance Deliverable

## 1. Purpose

This document establishes a risk-based approach to assessing the cybersecurity, privacy, governance, operational resilience and contractual risks associated with third-party AI suppliers.

It demonstrates how supplier due diligence, assurance evidence, risk scoring, remediation and continuous monitoring can support responsible AI adoption.

The methodology is informed by NIST AI RMF, ISO/IEC 42001, ISO/IEC 27001, ISO/IEC 27036 and established third-party risk management principles.

**Guiding Principle: Protect to Enable**

AI supplier assurance should enable responsible innovation through evidence-based due diligence, proportionate safeguards, clear accountability and continuous validation.

---

## 2. Assessment Objectives

The objectives are to:

- Identify material AI suppliers and service dependencies.
- Evaluate supplier cybersecurity and AI governance arrangements.
- Assess data protection, privacy and confidentiality risks.
- Review AI model security and application safeguards.
- Evaluate supplier operational resilience.
- Identify subcontractors and fourth-party dependencies.
- Review contractual security obligations.
- Assess supplier assurance evidence and control effectiveness.
- Determine inherent and residual supplier risk.
- Define remediation and escalation requirements.
- Support risk-based procurement and deployment decisions.
- Establish continuous supplier monitoring arrangements.

---

## 3. Assessment Scope

This methodology may apply to:

- Third-party AI model providers
- Generative AI SaaS applications
- Cloud-hosted AI platforms
- AI infrastructure and hosting providers
- AI development and integration vendors
- AI data processing and annotation providers
- AI security and monitoring service providers
- Material fourth-party AI service dependencies

Assessment depth should reflect the supplier's criticality, data access, system permissions, operational dependencies and potential impact on individuals and the organisation.

---

## 4. Illustrative Supplier Profile

### Supplier Identifier

AI-VEN-001

### Supplier Name

Fictional Enterprise AI Model Provider

### Related AI System

AI-SYS-001 — Enterprise AI Knowledge Assistant

### Related Risk

AI-RISK-004 — Third-Party AI Provider Risk

### Service Description

The fictional supplier provides large language model inference services supporting an internal retrieval-augmented generation (RAG) knowledge assistant.

### Intended Business Use

The AI assistant retrieves approved internal knowledge documents and generates informational responses for authorised employees.

### Data Classification

Internal business information, with potential exposure to personal or confidential information depending on the retrieved source documents.

### Potential Data Flows

- Employee submits an authorised query.
- The application retrieves relevant internal document content.
- Selected contextual information is provided to the model service.
- The model generates a response.
- The application returns the response to the authorised user.

### Material Dependencies

- Model inference infrastructure
- Cloud hosting
- Network and API connectivity
- Identity and access management
- Internal document retrieval services
- Supplier subcontractors

### Supplier Assessment Status

Illustrative — No actual supplier has been assessed.

All supplier characteristics, evidence requirements and risk ratings in this document are hypothetical.

---

## 5. AI Supplier Risk Classification

Supplier criticality should be determined before detailed due diligence.

### Classification Factors

- Sensitivity of information processed
- Access to personal or confidential data
- Importance of the AI-enabled business process
- Degree of system integration
- Privileged access or action-taking capabilities
- Potential impact of incorrect AI outputs
- Availability and recovery requirements
- Concentration and vendor lock-in risks
- Regulatory and contractual obligations
- Material fourth-party dependencies

### Illustrative Criticality Ratings

**Low:** Limited business impact, minimal sensitive data exposure and no significant system privileges.

**Moderate:** Material operational dependency or controlled access to internal information.

**High:** Sensitive data processing, significant business dependency or material security and compliance exposure.

**Critical:** Potential for severe organisational or individual harm, highly sensitive processing or essential operational dependency.

### AI-VEN-001 Classification

**Provisional Supplier Criticality: High**

**Rationale:**

The supplier supports a business-facing AI application that may process internal or sensitive information and introduces dependencies on external model inference and hosting services.

This is a hypothetical classification requiring validation against an actual supplier architecture and data-flow assessment.

---

## 6. Supplier Due Diligence Domains

The assessment should evaluate the following control domains.

### Domain 1 — Information Security Governance

**Assessment Questions:**

- Does the supplier maintain an information security governance framework?
- Are security policies approved and periodically reviewed?
- Are security responsibilities clearly assigned?
- Are independent audits or certifications available?
- Are material security risks tracked and remediated?

**Expected Evidence:**

- Security policies
- ISO/IEC 27001 certificate and applicable scope
- SOC 2 report where available
- Risk management documentation
- Relevant independent assurance reports

### Domain 2 — AI Governance and Accountability

**Assessment Questions:**

- Does the supplier maintain documented AI governance arrangements?
- Are AI model ownership and responsibilities defined?
- Are AI-related risks assessed throughout the lifecycle?
- Are model changes subject to governance review?
- Are human oversight and escalation arrangements documented?

**Expected Evidence:**

- AI governance policy
- AI risk management methodology
- Model governance documentation
- Model cards or equivalent system documentation
- ISO/IEC 42001 evidence where applicable

### Domain 3 — Data Protection and Privacy

**Assessment Questions:**

- What information is processed by the AI service?
- Where is customer data stored and processed?
- Is customer data used for model training or improvement?
- What retention and deletion controls apply?
- Are international transfers appropriately governed?
- Are data subject rights and breach notification responsibilities defined?

**Expected Evidence:**

- Data Processing Agreement
- Privacy and data handling policies
- Data-flow documentation
- Retention and deletion commitments
- Subprocessor information
- Transfer safeguards where applicable

### Domain 4 — AI Model and Application Security

**Assessment Questions:**

- Are prompt injection and jailbreak risks assessed?
- Are model inputs and outputs subject to appropriate safeguards?
- Are sensitive information disclosure risks evaluated?
- Are application APIs protected?
- Are model and application vulnerabilities tracked?
- Are relevant AI security tests performed?

**Expected Evidence:**

- AI security testing methodology
- Relevant security assessment summaries
- Vulnerability management procedures
- Application security documentation
- Remediation and retesting evidence

### Domain 5 — Identity and Access Management

**Assessment Questions:**

- Are privileged accounts appropriately controlled?
- Is multifactor authentication enforced where required?
- Are access rights reviewed?
- Are service accounts and API credentials protected?
- Are permissions restricted according to least privilege?

**Expected Evidence:**

- Access control policy
- Identity architecture
- Privileged access management procedures
- Access review records
- API credential management requirements

### Domain 6 — Secure Development and Change Management

**Assessment Questions:**

- Does the supplier operate a secure development lifecycle?
- Are code and dependencies subject to security testing?
- Are model updates evaluated before deployment?
- Are material changes communicated to customers?
- Are security defects tracked through remediation?

**Expected Evidence:**

- Secure SDLC policy
- Change management procedures
- Security testing summaries
- Vulnerability remediation process
- Model update and release governance records

### Domain 7 — Logging, Monitoring and Incident Response

**Assessment Questions:**

- Are security events logged and monitored?
- Are AI-specific security incidents considered?
- Are customer notification procedures documented?
- Are incident response arrangements periodically tested?
- Are investigation and recovery responsibilities defined?

**Expected Evidence:**

- Incident response plan
- Security monitoring procedures
- Incident notification commitments
- Relevant exercise summaries
- Incident escalation arrangements

### Domain 8 — Business Continuity and Operational Resilience

**Assessment Questions:**

- Does the supplier maintain business continuity arrangements?
- Are service recovery objectives defined?
- Are significant infrastructure dependencies identified?
- Are availability and resilience tests conducted?
- Are customer exit and data portability arrangements documented?

**Expected Evidence:**

- Business continuity policy
- Disaster recovery plan
- Recovery testing evidence
- Service availability commitments
- Exit and transition procedures

### Domain 9 — Fourth-Party and Supply Chain Risk

**Assessment Questions:**

- Which subcontractors support the AI service?
- Do subprocessors access customer information?
- Are material fourth-party risks assessed?
- Are supplier security requirements flowed down contractually?
- Are customers informed of material subprocessor changes?
- Are concentration and geographic risks considered?

**Expected Evidence:**

- Subprocessor register
- Fourth-party dependency information
- Supplier risk management policy
- Subcontractor assurance summaries
- Material change notification procedures

### Domain 10 — Contractual and Regulatory Assurance

**Assessment Questions:**

- Are information security responsibilities contractually defined?
- Are confidentiality and data processing obligations established?
- Are incident notification timeframes specified?
- Are audit and assurance rights proportionate to the risk?
- Are liability, termination and exit provisions reviewed?
- Are applicable AI and data protection obligations addressed?

**Expected Evidence:**

- Master Services Agreement
- Data Processing Agreement
- Security schedule
- Service Level Agreement
- Contractual audit provisions
- Exit and data deletion commitments

---

## 7. Supplier Risk Assessment Methodology

The illustrative assessment uses a five-point likelihood and impact model consistent with the AI Risk and Impact Assessment.

**Risk Score = Likelihood × Impact**

### Risk Rating

| Score | Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

### Assessment Principles

- Inherent risk is assessed before considering evaluated safeguards.
- Residual risk is assessed after evaluating controls and their effectiveness.
- Supplier claims must be supported by appropriate evidence.
- Missing evidence should be recorded as an assurance gap.
- Unverified controls must not be assumed effective.
- Risk ratings require documented rationale.
- Material risks must follow established escalation procedures.

### AI-VEN-001 Inherent Risk

**Likelihood:** 3 — Possible

**Impact:** 4 — Major

**Risk Score:** 12 — High

**Rationale:**

The fictional supplier represents a material external dependency with potential exposure to internal or sensitive information.

### Illustrative Residual Risk

**Likelihood:** 2 — Unlikely

**Impact:** 4 — Major

**Risk Score:** 8 — Moderate

**Important Qualification:**

This residual score is hypothetical and assumes that appropriate safeguards would be implemented and independently evaluated.

Because no supplier evidence has been reviewed, the actual residual risk is **Not Determined**.

The hypothetical score must not be used as an approved risk rating.

---

## 8. Supplier Assurance Evidence Evaluation

Evidence should be assessed for:

- Relevance to the contracted service
- Scope and applicability
- Currency and reporting period
- Completeness
- Independence and reliability
- Identified exceptions or qualifications
- Remediation status
- Applicability to relevant subcontractors

### Evidence Evaluation Status

**Verified:** Evidence has been reviewed and supports the relevant requirement.

**Partially Verified:** Evidence supports some, but not all, aspects of the requirement.

**Insufficient:** Evidence does not adequately demonstrate the required safeguard.

**Not Provided:** Required evidence has not been received.

**Not Applicable:** The requirement is not relevant, with documented justification.

### AI-VEN-001 Evidence Status

**Not Provided — Illustrative Assessment**

No real supplier documentation has been requested or reviewed.

---

## 9. Illustrative Supplier Findings

### AI-TPRM-001 — Data Processing Transparency

**Finding:** Data retention, processing location and model training arrangements have not been evidenced.

**Potential Impact:** Unauthorised processing, privacy exposure or contractual non-compliance.

**Priority:** High

**Required Action:** Obtain and review supplier data processing commitments.

**Status:** Evidence Outstanding

### AI-TPRM-002 — AI Security Testing Assurance

**Finding:** No security testing evidence is available for the fictional supplier.

**Potential Impact:** Undetected AI application or model security weaknesses.

**Priority:** High

**Required Action:** Obtain relevant testing methodology, assurance summaries and remediation evidence.

**Status:** Evidence Outstanding

### AI-TPRM-003 — Fourth-Party Visibility

**Finding:** Material subcontractors and infrastructure dependencies have not been validated.

**Potential Impact:** Unidentified concentration, privacy, resilience or supply chain exposure.

**Priority:** High

**Required Action:** Obtain material subprocessor and dependency information.

**Status:** Evidence Outstanding

### AI-TPRM-004 — Incident Notification Arrangements

**Finding:** Contractual incident notification requirements have not been evaluated.

**Potential Impact:** Delayed incident awareness, response or regulatory reporting.

**Priority:** Moderate

**Required Action:** Review proposed contractual notification and cooperation provisions.

**Status:** Evidence Outstanding

### AI-TPRM-005 — Model Change Governance

**Finding:** Model update notification and reassessment arrangements have not been evidenced.

**Potential Impact:** Material changes may invalidate earlier security and governance assumptions.

**Priority:** High

**Required Action:** Review supplier change governance, notification and customer assurance arrangements.

**Status:** Evidence Outstanding

These findings represent hypothetical assurance gaps, not verified deficiencies of an actual supplier.

---

## 10. Consolidated Supplier Findings Register

| Finding ID | Assurance Area | Priority | Status |
|---|---|---|---|
| AI-TPRM-001 | Data Processing | High | Evidence Outstanding |
| AI-TPRM-002 | AI Security Testing | High | Evidence Outstanding |
| AI-TPRM-003 | Fourth-Party Visibility | High | Evidence Outstanding |
| AI-TPRM-004 | Incident Notification | Moderate | Evidence Outstanding |
| AI-TPRM-005 | Model Change Governance | High | Evidence Outstanding |

The findings register should be updated as evidence is received, assessed and validated.

---

## 11. Contractual Security Requirements

Risk-based contractual safeguards should address, where applicable:

### Information Protection

- Confidentiality obligations
- Data classification and permitted use
- Encryption and access control requirements
- Restrictions on unauthorised data disclosure

### AI-Specific Data Processing

- Permitted purposes of AI processing
- Model training and data reuse restrictions
- Data retention and deletion requirements
- Processing location and transfer arrangements

### Security and Incident Management

- Security incident notification obligations
- Incident cooperation and investigation support
- Vulnerability remediation expectations
- Material security change notifications

### Supplier and Fourth-Party Oversight

- Subprocessor transparency
- Material subcontractor change notifications
- Appropriate flow-down security obligations
- Supplier assurance and audit rights

### Service Continuity and Exit

- Availability commitments
- Business continuity arrangements
- Data export and portability
- Secure deletion at termination
- Exit assistance where appropriate

Contractual terms must be reviewed by authorised Legal, Procurement and business stakeholders.

---

## 12. Risk Treatment and Escalation

Supplier risks should be treated through one or more of the following options:

- **Mitigate:** Require additional safeguards or remediation.
- **Avoid:** Reject or discontinue the supplier relationship.
- **Transfer or Share:** Allocate defined responsibilities or financial exposure while retaining appropriate organisational accountability.
- **Accept:** Formally approve residual risk within delegated authority.

### Escalation Conditions

Escalation should occur when:

- Material assurance evidence is unavailable.
- High or Critical risks remain unresolved.
- Contractual protections are insufficient.
- Significant fourth-party dependencies are unidentified.
- Supplier controls fail validation.
- Material changes invalidate prior approval assumptions.
- Risks exceed approved tolerance.

The AI System Owner remains accountable for the associated AI system risk, while Third-Party Risk Management coordinates supplier assurance activities.

Risk acceptance must follow the organisation's approved delegation of authority.

---

## 13. Illustrative Supplier Approval Decision

**Supplier:** AI-VEN-001

**Related System:** AI-SYS-001

**Assessment Status:** Incomplete

**Assurance Decision: Not Approved — Further Evidence Required**

### Decision Rationale

- Supplier data processing arrangements have not been verified.
- AI security assurance evidence is unavailable.
- Material fourth-party dependencies remain unvalidated.
- Incident notification provisions have not been assessed.
- Model change governance arrangements remain unverified.
- Actual residual risk cannot be determined.

### Conditions for Reconsideration

- Obtain relevant supplier assurance documentation.
- Validate applicable security and privacy safeguards.
- Review material subcontractor dependencies.
- Confirm contractual security requirements.
- Update the supplier risk assessment.
- Resolve or escalate material findings.
- Obtain approval from the designated authority.

This is an illustrative governance decision, not an actual supplier rejection or procurement determination.

---

## 14. Continuous Supplier Monitoring

Supplier assurance should continue throughout the contractual relationship.

### Monitoring Activities

- Review material supplier security incidents.
- Monitor significant model and service changes.
- Review updated assurance reports.
- Track outstanding remediation actions.
- Monitor contractual and regulatory developments.
- Review changes to material subprocessors.
- Evaluate service availability and resilience.
- Reassess changes in supplier criticality.
- Review emerging AI security threats.

### Reassessment Triggers

- Material model updates
- New data processing purposes
- Changes in data location or retention
- New material subcontractors
- Significant security incidents
- Major architecture or integration changes
- Repeated service failures
- Relevant regulatory changes
- Expiry or qualification of assurance evidence
- Failure to remediate material findings

### Monitoring Outcomes

Monitoring should support:

- Updated risk ratings
- New remediation requirements
- Supplier escalation decisions
- Contractual control improvements
- Renewal or termination recommendations
- Reauthorisation where required

---

## 15. Governance and Framework Alignment

### NIST AI RMF — GOVERN

- Establish supplier governance responsibilities.
- Define AI risk appetite and approval authority.
- Maintain supplier oversight arrangements.
- Establish contractual and accountability requirements.

### NIST AI RMF — MAP

- Identify AI suppliers and dependencies.
- Map data processing and system interactions.
- Identify affected stakeholders.
- Evaluate supplier-related risks and impacts.

### NIST AI RMF — MEASURE

- Evaluate supplier assurance evidence.
- Assess control effectiveness.
- Identify security and governance gaps.
- Document uncertainty and residual risk.

### NIST AI RMF — MANAGE

- Prioritise supplier risk treatment.
- Escalate unacceptable exposure.
- Monitor material supplier changes.
- Reassess supplier risks throughout the lifecycle.

### ISO/IEC 42001

Supports consideration of AI management responsibilities, AI system lifecycle governance, risk management and relevant third-party relationships.

### ISO/IEC 27001 and ISO/IEC 27036

Support information security governance and supplier relationship security management.

Framework alignment should be adapted to organisational scope and applicable requirements.

---

## 16. Expected Outcomes

This supplier assurance approach should support:

- Improved visibility of AI supplier risks
- Stronger evidence-based due diligence
- Clear supplier risk ownership
- Better understanding of fourth-party dependencies
- Proportionate contractual safeguards
- Consistent remediation and escalation
- Defensible supplier approval decisions
- Continuous monitoring of material supplier changes
- Responsible AI adoption aligned with organisational risk appetite

---

## 17. Conclusion

Third-party AI assurance should not rely solely on supplier questionnaires or declarations of compliance.

Effective supplier governance requires understanding service dependencies, validating relevant evidence, assessing risk, addressing material gaps and maintaining continuous oversight.

Supplier approval is a governance decision supported by assurance evidence, not simply a procurement milestone.

**Protect to Enable — Assess Suppliers, Validate Evidence and Continuously Monitor AI Dependencies.**

---

## Disclaimer

This document is an illustrative, sanitised professional portfolio example.

The supplier, AI system, risk ratings, findings and assurance decisions are fictional.

No actual supplier has been assessed, approved, rejected or certified through this document.

The approach must be tailored to organisational risk appetite, supplier criticality, contractual arrangements, applicable legal obligations and approved governance procedures.

This document is informed by NIST AI RMF, ISO/IEC 42001, ISO/IEC 27001 and ISO/IEC 27036 principles. It is not an official framework publication or certification.
