# SentinelAI Compliance — Risk Register

## Overview

This risk register identifies, assesses, and documents all potential risks facing SentinelAI Compliance, with full inherent and residual risk scoring aligned to CRISC 8th Edition methodology.

| Field | Details |
|-------|---------|
| Last Updated | December 2024 |
| Document Owner | Risk Management Team |
| Review Frequency | Quarterly |
| Methodology | CRISC 8th Edition |

---

## Company Profile

| Attribute | Details |
|-----------|---------|
| Company Name | SentinelAI Compliance |
| Industry | RegTech / AI Governance |
| Product | AI compliance platform + Agentic AI monitoring |
| Employees | 75 |
| Customers | Financial institutions, healthcare providers, government agencies |
| Infrastructure | Multi-cloud (AWS + Azure) |
| Stage | Series B funded, expanding into EU market |

---

## Risk Scoring Methodology

### Likelihood Scale

| Score | Rating | Description |
|-------|--------|-------------|
| 1 | Rare | Unlikely to occur |
| 2 | Unlikely | Could occur but not expected |
| 3 | Possible | May occur occasionally |
| 4 | Likely | Will probably occur |
| 5 | Almost Certain | Expected to occur frequently |

### Impact Scale

| Score | Rating | Description |
|-------|--------|-------------|
| 1 | Negligible | Minimal impact on operations |
| 2 | Minor | Small impact, easily managed |
| 3 | Moderate | Noticeable impact requiring response |
| 4 | Major | Significant impact on objectives |
| 5 | Severe | Critical impact, potential business failure |

### Risk Score Matrix

### Control Effectiveness

| Rating | Description |
|--------|-------------|
| High | Control is well-designed and operating effectively |
| Moderate | Control exists but has gaps or inconsistent application |
| Low | Control is weak or poorly implemented |

---

## Risk Summary

### By Category

| Category | Count |
|----------|-------|
| Strategic | 6 |
| Operational | 6 |
| AI/Model | 7 |
| Agentic AI | 8 |
| Cybersecurity | 8 |
| Regulatory/Compliance | 8 |
| Third-Party/Vendor | 6 |
| Financial | 6 |
| **Total** | **55** |

### Inherent Risk Summary (Before Controls)

| Risk Level | Count | Percentage |
|------------|-------|------------|
| Critical (17-25) | 3 | 5% |
| High (10-16) | 32 | 58% |
| Medium (5-9) | 18 | 33% |
| Low (1-4) | 2 | 4% |
| **Total** | **55** | **100%** |

### Residual Risk Summary (After Controls)

| Risk Level | Count | Percentage |
|------------|-------|------------|
| Critical (17-25) | 0 | 0% |
| High (10-16) | 2 | 4% |
| Medium (5-9) | 26 | 47% |
| Low (1-4) | 27 | 49% |
| **Total** | **55** | **100%** |

---

## 1. Strategic Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| STR-001 | Regulatory landscape changes faster than product can adapt | 4 | 4 | 16 | High | Regulatory monitoring team; Legal counsel retainer; Agile product roadmap | Moderate | 3 | 3 | 9 | Medium | Mitigate | CEO | Q3 2025 |
| STR-002 | Competition from established GRC vendors adding AI features | 4 | 3 | 12 | High | Competitive intelligence programme; Differentiation strategy | Low | 4 | 3 | 12 | High | Accept | CEO | Q3 2025 |
| STR-003 | Failure to secure key enterprise clients in target verticals | 3 | 4 | 12 | High | Sales pipeline reviews; Pilot programmes; Reference customers | Moderate | 2 | 4 | 8 | Medium | Mitigate | CRO | Q2 2025 |
| STR-004 | Over-reliance on single geographic market | 3 | 3 | 9 | Medium | EU expansion roadmap; Market diversification plan | Low | 3 | 2 | 6 | Medium | Mitigate | CEO | Q4 2025 |
| STR-005 | Reputational damage if client suffers AI compliance failure | 2 | 5 | 10 | Medium | Client SLAs; Indemnity clauses; Incident response plan | Moderate | 2 | 4 | 8 | Medium | Transfer | CEO | Q3 2025 |
| STR-006 | Inability to attract AI/ML talent in competitive market | 4 | 3 | 12 | High | Compensation benchmarking; Remote work policy; Equity programme | Moderate | 3 | 3 | 9 | Medium | Mitigate | CHRO | Q2 2025 |

---

## 2. Operational Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| OPS-001 | Platform outage affecting customer compliance monitoring | 3 | 5 | 15 | High | 99.9% SLA; Redundant infrastructure; DR plan | High | 2 | 4 | 8 | Medium | Mitigate | CTO | Q2 2025 |
| OPS-002 | Inadequate customer onboarding causing delayed implementations | 3 | 3 | 9 | Medium | Onboarding playbook; Dedicated CSM; 30-day check-ins | Moderate | 2 | 2 | 4 | Low | Mitigate | COO | Q2 2025 |
| OPS-003 | Knowledge concentration in key employees (key person risk) | 4 | 4 | 16 | High | Documentation requirements; Cross-training; Succession planning | Moderate | 3 | 3 | 9 | Medium | Mitigate | COO | Q2 2025 |
| OPS-004 | Insufficient capacity to scale support during rapid growth | 4 | 3 | 12 | High | Scalable support model; Hiring plan; Self-service portal | Low | 3 | 2 | 6 | Medium | Mitigate | COO | Q3 2025 |
| OPS-005 | Ineffective change management processes | 3 | 3 | 9 | Medium | Change Advisory Board; Release management policy | Moderate | 2 | 2 | 4 | Low | Mitigate | CTO | Q3 2025 |
| OPS-006 | Business continuity plan not tested or outdated | 3 | 4 | 12 | High | Annual BCP test scheduled; BCP owner assigned | Low | 2 | 3 | 6 | Medium | Mitigate | COO | Q2 2025 |

---

## 3. AI/Model Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| MOD-001 | Bias in AI compliance scoring algorithms | 3 | 5 | 15 | High | Bias testing in SDLC; Fairness metrics; Third-party audit | High | 2 | 4 | 8 | Medium | Mitigate | Chief AI Officer | Q2 2025 |
| MOD-002 | Model drift causing inaccurate risk classifications | 4 | 4 | 16 | High | Monthly drift monitoring; Automated retraining triggers | Moderate | 3 | 3 | 9 | Medium | Mitigate | Chief AI Officer | Q2 2025 |
| MOD-003 | Training data poisoning by malicious actors | 2 | 5 | 10 | Medium | Data provenance controls; Anomaly detection; Access controls | High | 1 | 4 | 4 | Low | Mitigate | CISO | Q3 2025 |
| MOD-004 | Lack of explainability in AI-driven recommendations | 4 | 4 | 16 | High | SHAP/LIME explainability layer; Human review step | Moderate | 3 | 3 | 9 | Medium | Mitigate | Chief AI Officer | Q2 2025 |
| MOD-005 | Hallucinations in AI-generated compliance reports | 4 | 5 | 20 | Critical | Human-in-the-loop review; Confidence thresholds; Output validation | High | 2 | 4 | 8 | Medium | Mitigate | Chief AI Officer | Q1 2025 |
| MOD-006 | Inadequate model validation and testing procedures | 3 | 4 | 12 | High | Model validation framework; Staging environment; UAT | Moderate | 2 | 3 | 6 | Medium | Mitigate | CTO | Q2 2025 |
| MOD-007 | Failure to detect model performance degradation | 3 | 4 | 12 | High | Automated performance dashboards; KRI alerts | Moderate | 2 | 3 | 6 | Medium | Mitigate | Chief AI Officer | Q2 2025 |

---

## 4. Agentic AI Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| AGT-001 | AI agent takes autonomous action without human approval | 3 | 5 | 15 | High | Human-in-the-loop gates; Action approval workflows | High | 2 | 4 | 8 | Medium | Mitigate | Chief AI Officer | Q1 2025 |
| AGT-002 | Agent goal misalignment with business objectives | 3 | 5 | 15 | High | Goal specification review; Alignment testing; Red-teaming | Moderate | 2 | 4 | 8 | Medium | Mitigate | Chief AI Officer | Q2 2025 |
| AGT-003 | Uncontrolled agent-to-agent communication creating feedback loops | 2 | 5 | 10 | Medium | Communication rate limits; Circuit breakers; Monitoring | High | 1 | 4 | 4 | Low | Mitigate | CTO | Q2 2025 |
| AGT-004 | Prompt injection attack manipulating agent behavior | 4 | 5 | 20 | Critical | Input sanitisation; Prompt hardening; Red-team testing | High | 3 | 4 | 12 | High | Mitigate | CISO | Q1 2025 |
| AGT-005 | Agent exceeds defined operational boundaries | 3 | 5 | 15 | High | Boundary enforcement rules; Sandbox environment; Alerts | High | 2 | 4 | 8 | Medium | Mitigate | Chief AI Officer | Q2 2025 |
| AGT-006 | Inability to audit or explain agent decision chains | 4 | 4 | 16 | High | Decision logging; Audit trail system; Explainability module | Moderate | 3 | 3 | 9 | Medium | Mitigate | Chief AI Officer | Q2 2025 |
| AGT-007 | Agent persists erroneous actions at scale before detection | 3 | 5 | 15 | High | Real-time monitoring; Kill switch; Rollback capability | High | 2 | 4 | 8 | Medium | Mitigate | CTO | Q1 2025 |
| AGT-008 | Accountability gaps — unclear liability for agent decisions | 4 | 4 | 16 | High | Liability framework; Policy documentation; Legal review | Moderate | 3 | 3 | 9 | Medium | Mitigate | CLO | Q2 2025 |

---

## 5. Cybersecurity Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| SEC-001 | Data breach exposing customer compliance data | 3 | 5 | 15 | High | Encryption at rest/transit; DLP; Access controls | High | 2 | 4 | 8 | Medium | Mitigate | CISO | Q2 2025 |
| SEC-002 | Ransomware attack on platform infrastructure | 3 | 5 | 15 | High | EDR solution; Immutable backups; IR plan | High | 2 | 4 | 8 | Medium | Mitigate | CISO | Q2 2025 |
| SEC-003 | Unauthorized access via compromised credentials | 4 | 4 | 16 | High | MFA enforced; PAM solution; Zero trust architecture | High | 2 | 3 | 6 | Medium | Mitigate | CISO | Q1 2025 |
| SEC-004 | DDoS attack causing service unavailability | 3 | 4 | 12 | High | CDN with DDoS scrubbing; Rate limiting; WAF | High | 2 | 3 | 6 | Medium | Mitigate | CISO | Q2 2025 |
| SEC-005 | Insider threat from privileged employee | 2 | 5 | 10 | Medium | Least privilege; Activity monitoring; Offboarding checklist | High | 1 | 4 | 4 | Low | Mitigate | CISO | Q3 2025 |
| SEC-006 | Insecure API integrations with customer systems | 3 | 4 | 12 | High | API gateway; OAuth 2.0; Penetration testing | Moderate | 2 | 3 | 6 | Medium | Mitigate | CTO | Q2 2025 |
| SEC-007 | Inadequate encryption of sensitive data | 2 | 5 | 10 | Medium | Encryption standard enforced; Key management policy | High | 1 | 3 | 3 | Low | Mitigate | CISO | Q2 2025 |
| SEC-008 | Supply chain attack via third-party dependencies | 3 | 5 | 15 | High | SCA tooling; Vendor assessments; SBOM | High | 2 | 4 | 8 | Medium | Mitigate | CISO | Q2 2025 |

---

## 6. Regulatory/Compliance Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| REG-001 | Non-compliance with EU AI Act requirements | 4 | 5 | 20 | Critical | EU AI Act compliance programme; Legal counsel; Conformity assessments | High | 2 | 4 | 8 | Medium | Mitigate | CLO | Q1 2025 |
| REG-002 | Failure to meet NIST AI RMF guidelines | 3 | 4 | 12 | High | NIST RMF mapping exercise; Gap assessment | Moderate | 2 | 3 | 6 | Medium | Mitigate | Chief AI Officer | Q2 2025 |
| REG-003 | GDPR violations in handling EU customer data | 3 | 5 | 15 | High | DPA appointed; DPIA process; Data minimisation controls | High | 2 | 4 | 8 | Medium | Mitigate | DPO | Q2 2025 |
| REG-004 | Inadequate documentation for regulatory audits | 4 | 4 | 16 | High | Document management system; Audit readiness reviews | High | 2 | 3 | 6 | Medium | Mitigate | CLO | Q2 2025 |
| REG-005 | Failure to conduct required AI conformity assessments | 3 | 5 | 15 | High | Conformity assessment schedule; Notified body engaged | High | 2 | 4 | 8 | Medium | Mitigate | CLO | Q2 2025 |
| REG-006 | Breach of customer contractual SLAs | 3 | 4 | 12 | High | SLA monitoring dashboards; Escalation procedures | Moderate | 2 | 3 | 6 | Medium | Mitigate | CLO | Q3 2025 |
| REG-007 | Cross-border data transfer violations | 3 | 4 | 12 | High | SCCs in place; Data transfer impact assessments | Moderate | 2 | 3 | 6 | Medium | Mitigate | DPO | Q2 2025 |
| REG-008 | Failure to maintain required audit trails | 3 | 4 | 12 | High | Audit logging system; Log retention policy | Moderate | 2 | 3 | 6 | Medium | Mitigate | CISO | Q2 2025 |

---

## 7. Third-Party/Vendor Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| VEN-001 | Foundation model provider changes terms or discontinues service | 2 | 5 | 10 | Medium | Multi-model strategy; Contractual protections; Open-source fallback | Moderate | 1 | 4 | 4 | Low | Mitigate | CTO | Q3 2025 |
| VEN-002 | Cloud provider outage (AWS/Azure) | 2 | 5 | 10 | Medium | Multi-cloud architecture; DR plan; RTO/RPO defined | High | 1 | 4 | 4 | Low | Mitigate | CTO | Q2 2025 |
| VEN-003 | Vendor security breach exposing shared data | 3 | 5 | 15 | High | Vendor security assessments; Data isolation; Contractual obligations | High | 2 | 4 | 8 | Medium | Mitigate | CISO | Q2 2025 |
| VEN-004 | Lack of transparency in third-party AI models (black box) | 4 | 4 | 16 | High | Model cards required; Explainability clauses in contracts | Moderate | 3 | 3 | 9 | Medium | Accept | Chief AI Officer | Q3 2025 |
| VEN-005 | Contractual liability gaps with vendors | 3 | 3 | 9 | Medium | Legal review of all vendor contracts; Indemnity clauses | Moderate | 2 | 2 | 4 | Low | Mitigate | CLO | Q3 2025 |
| VEN-006 | Vendor lock-in limiting flexibility | 3 | 3 | 9 | Medium | Open standards preference; Exit clauses in contracts | Low | 2 | 2 | 4 | Low | Accept | CTO | Q3 2025 |

---

## 8. Financial Risks

| Risk ID | Risk Description | Inh. Likelihood | Inh. Impact | Inherent Score | Inherent Level | Existing Controls | Control Effectiveness | Res. Likelihood | Res. Impact | Residual Score | Residual Level | Treatment | Risk Owner | Review Date |
|---------|------------------|-----------------|-------------|----------------|----------------|-------------------|----------------------|-----------------|-------------|----------------|----------------|-----------|------------|-------------|
| FIN-001 | Cash flow shortage during expansion phase | 3 | 5 | 15 | High | 18-month cash runway maintained; Credit facility | Moderate | 2 | 4 | 8 | Medium | Mitigate | CFO | Q2 2025 |
| FIN-002 | Customer churn exceeding projections | 3 | 4 | 12 | High | NPS monitoring; Customer success programme; Churn KRIs | Moderate | 2 | 3 | 6 | Medium | Mitigate | CRO | Q3 2025 |
| FIN-003 | Unexpected infrastructure cost increases | 4 | 3 | 12 | High | Cloud cost monitoring; FinOps practice; Budget alerts | High | 3 | 2 | 6 | Medium | Mitigate | CFO | Q2 2025 |
| FIN-004 | Currency exchange losses from global customers | 3 | 2 | 6 | Medium | FX hedging policy; Multi-currency invoicing | Low | 2 | 2 | 4 | Low | Accept | CFO | Q4 2025 |
| FIN-005 | Delayed Series C funding impacting growth plans | 2 | 5 | 10 | Medium | Milestone-based funding triggers; Burn rate management | Moderate | 2 | 4 | 8 | Medium | Mitigate | CEO | Q2 2025 |
| FIN-006 | Customer concentration risk | 3 | 4 | 12 | High | Client diversification targets; Revenue concentration KRI | Moderate | 2 | 3 | 6 | Medium | Mitigate | CFO | Q3 2025 |

---

## Document Control

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | December 2024 | Risk Management Team | Initial risk register |

---

## Next Steps

- [ ] Create risk heat maps (inherent and residual)
- [ ] Define Key Risk Indicators (KRIs) for critical risks
- [ ] Schedule quarterly risk review meetings
- [ ] Develop detailed risk response plans for high/critical risks

---

*Document maintained as part of the AI Risk Management Framework portfolio project.*

*GitHub: [opeyemi-beatrice](https://github.com/opeyemi-beatrice)*
