# In-Life Monitoring Plan

*Tracking system performance and impact once deployed*

```yaml
project_info:
  project_id: "PROJ-2024-001"
  project_name: "MedAssist AI: Primary Care Diagnostic Support System"
  monitoring_plan_date: "2024-03-22"
  expected_deployment: "2025-01-15"
```

## What We Need to Monitor

Based on our values priorities and risk assessment, we need to track whether our system is actually delivering the benefits we promised whilst avoiding the harms we identified.

---

## Safety & Effectiveness Monitoring

### Primary Safety Metrics

**Diagnostic Accuracy Tracking**
- **What:** Percentage agreement between AI suggestions and eventual confirmed diagnoses
- **Target:** >85% for high-confidence suggestions, >70% for medium-confidence
- **How measured:** Retrospective analysis of patient outcomes after 30 days
- **Frequency:** Weekly during pilot, monthly thereafter
- **Alert thresholds:** <80% triggers immediate review, <75% triggers deployment pause
- **Owner:** Clinical Quality Team

**Patient Harm Indicators**
- **What:** Incidents where AI suggestions potentially contributed to diagnostic delays or errors
- **Target:** Zero serious harm incidents attributable to AI
- **How measured:** Clinical incident reporting system + case note review
- **Frequency:** Real-time incident reporting, monthly trend analysis
- **Alert thresholds:** Any serious harm incident triggers immediate investigation
- **Owner:** Patient Safety Lead

### Clinical Integration Metrics

**System Override Patterns**
- **What:** Frequency and reasons why GPs dismiss or override AI suggestions
- **Target:** <30% override rate for high-confidence suggestions
- **How measured:** Automated logging of user interactions
- **Frequency:** Weekly analysis during pilot, monthly thereafter
- **Alert thresholds:** >50% override rate triggers interface review, >70% suggests fundamental issues
- **Owner:** Clinical User Experience Team

**Consultation Flow Impact**
- **What:** Average consultation time and workflow disruption
- **Target:** No increase in average consultation time, <10% of users report workflow disruption
- **How measured:** Time tracking + user surveys
- **Frequency:** Monthly user surveys, quarterly time studies
- **Alert thresholds:** >15% increase in consultation time or >25% reporting disruption
- **Owner:** Practice Management Team

---

## Equity & Fairness Monitoring

### Demographic Analysis

**Diagnostic Pattern Analysis**
- **What:** Diagnostic suggestions and outcomes across different demographic groups
- **Target:** No significant disparities in diagnostic accuracy or referral rates
- **How measured:** Anonymised analysis of diagnostic patterns by age, gender, ethnicity, socioeconomic status
- **Frequency:** Quarterly demographic equity reports
- **Alert thresholds:** >10% difference in accuracy between demographic groups
- **Owner:** Health Equity Officer

**Access and Usage Patterns**
- **What:** Whether all patient groups benefit equally from AI-supported consultations
- **Target:** Consistent usage across all practice populations
- **How measured:** Usage analytics by practice demographics
- **Frequency:** Monthly usage reports
- **Alert thresholds:** Significant under-usage in vulnerable populations
- **Owner:** Community Engagement Team

---

## System Performance Monitoring

### Technical Reliability

**System Availability**
- **What:** Uptime during consultation hours
- **Target:** >99.5% availability during practice hours
- **How measured:** Automated system monitoring
- **Frequency:** Real-time monitoring with monthly reports
- **Alert thresholds:** <99% monthly average or >2 hour cumulative downtime
- **Owner:** Technical Operations Team

**Response Time Performance**
- **What:** Time from data input to AI suggestion display
- **Target:** <3 seconds for standard cases, <10 seconds for complex cases
- **How measured:** Automated performance logging
- **Frequency:** Continuous monitoring with weekly reports
- **Alert thresholds:** >5 seconds average response time
- **Owner:** Technical Performance Team

---

## User Experience & Adoption

### Clinical User Satisfaction

**GP Satisfaction Survey**
- **What:** Quarterly survey of all system users
- **Target:** >85% report system as helpful, <10% report as disruptive
- **How measured:** Anonymous online survey
- **Frequency:** Quarterly
- **Alert thresholds:** <70% satisfaction or >20% reporting negative impact
- **Owner:** User Experience Team

**Clinical Confidence Tracking**
- **What:** GP confidence in AI suggestions and their own diagnostic decisions
- **Target:** Maintained or improved clinical confidence levels
- **How measured:** Monthly pulse surveys + annual detailed assessment
- **Frequency:** Monthly pulse, annual deep dive
- **Alert thresholds:** Declining confidence trends over 3 months
- **Owner:** Professional Development Team

---

## Risk Monitoring (Ongoing)

### High-Priority Risk Indicators

**Over-reliance Detection**
- **What:** Signs that GPs are becoming overly dependent on AI suggestions
- **How monitored:** Analysis of diagnostic reasoning documentation, override patterns
- **Warning signs:** Declining documentation quality, very low override rates, reduced clinical questioning
- **Response:** Additional training, interface modifications to encourage critical thinking

**Bias Pattern Detection**
- **What:** Emerging patterns suggesting systematic bias in AI suggestions
- **How monitored:** Monthly demographic analysis, external algorithmic auditing
- **Warning signs:** Significant disparities in diagnostic patterns by protected characteristics
- **Response:** Model retraining, additional bias testing, clinical review process

**Data Security Monitoring**
- **What:** Ongoing security of patient data and system integrity
- **How monitored:** Continuous security monitoring, quarterly penetration testing
- **Warning signs:** Any attempted breach, unusual data access patterns
- **Response:** Immediate security team escalation, potential system isolation

---

## Reporting & Governance

### Regular Reporting Schedule

**Weekly Reports** (During pilot phase)
- Safety metrics dashboard
- System performance summary
- Critical incident log
- **Audience:** Clinical Leadership Team

**Monthly Reports**
- Comprehensive safety and effectiveness analysis
- User experience metrics
- Risk indicator updates
- **Audience:** Clinical Advisory Board + NHS Trust Board

**Quarterly Reports**
- Full equity and fairness analysis
- Long-term trend analysis
- Recommendations for system improvements
- **Audience:** NHS Digital + Regulatory bodies

**Annual Reports**
- Comprehensive evaluation of system impact
- Cost-benefit analysis
- Lessons learned and future recommendations
- **Audience:** Public health community + Academic partners

### Escalation Procedures

**Level 1: Operational Issues**
- Performance degradation, minor technical issues
- **Response:** Technical team investigation, 48-hour resolution target
- **Escalation:** To Clinical Lead if unresolved in 48 hours

**Level 2: Clinical Concerns**
- Quality issues, user satisfaction problems
- **Response:** Clinical review within 24 hours, mitigation plan within 1 week
- **Escalation:** To Medical Director if pattern persists

**Level 3: Safety Incidents**
- Any patient safety concern, significant system failure
- **Response:** Immediate clinical review, potential system suspension
- **Escalation:** To NHS Trust Board and regulatory bodies as required

### External Oversight

**Independent Monitoring Board**
- Quarterly review of all monitoring data
- External clinical experts + patient representatives
- Authority to recommend system modifications or suspension

**Regulatory Reporting**
- MHRA device performance reporting
- NHS Digital security and effectiveness updates
- Care Quality Commission inspection support

---

## Continuous Improvement Process

### Monthly Review Cycle
1. **Data Collection:** All monitoring streams consolidated
2. **Analysis:** Trend identification and pattern recognition
3. **Stakeholder Review:** Clinical team + user representatives
4. **Action Planning:** Improvements identified and prioritised
5. **Implementation:** Changes deployed with monitoring
6. **Evaluation:** Impact assessment in following cycle

### Learning and Adaptation

**System Evolution**
- Monthly model performance reviews
- Quarterly training data updates
- Annual comprehensive system evaluation
- **Triggers for major updates:** Significant performance changes, new clinical evidence, regulatory requirements

**Knowledge Sharing**
- Monthly case studies of interesting findings
- Quarterly presentations to clinical community
- Annual publication of outcomes and lessons learned
- **Goal:** Contribute to wider understanding of AI in healthcare

---

## Success Criteria for Continuation

**Must Achieve (Minimum viable success):**
- Zero serious harm incidents attributable to AI
- >80% diagnostic accuracy for high-confidence suggestions
- >75% GP satisfaction with system
- >99.5% system availability during practice hours

**Should Achieve (Good success):**
- 25% reduction in missed diagnoses
- >90% GP satisfaction
- No significant demographic disparities
- Evidence of improved clinical confidence

**Could Achieve (Excellent success):**
- Measurable improvement in patient outcomes
- Adoption by >90% of eligible practices
- Recognition as best practice by NHS
- Replication in other healthcare settings

---

## Keep This Updated

**Document version:** 1.0
**Last updated:** 2024-03-22
**Next review:** 2024-04-22 (monthly during development)
**Responsible person:** Dr Sarah Chen, Clinical Lead

**Monitoring data stored in:** NHS Clinical Governance System + Research Database
**Access permissions:** Clinical team, NHS oversight bodies, approved researchers

Remember: Monitoring in healthcare is about continuous learning, not just compliance. Every metric should help us understand how to better serve patients and support clinicians.