# AISaE byDesign: Feature Design Template

*From priorities to buildable features*

```yaml
project_info:
  project_name: "MedAssist AI: Primary Care Diagnostic Support System"
  project_id: "PROJ-2024-001"
  your_name_or_team: "HealthTech Innovations Clinical Development Team"
  planning_date: "2024-03-20"
```

## What You Have So Far

You've completed your Implementation Approach Selection and now you have:
- A chosen approach (2: "Do It Properly")
- Clear priorities for values, behaviours, risks, and opportunities
- Risks recorded in your Risk Register

Now it's time to turn your prioritised values and opportunities into concrete features you can actually build and test.

---

# STEP 3: TURN IDEAS INTO FEATURES

Convert your priorities into actual things you can build and test.

## Must-Do Features

### Patient Safety First & Clinical Decision Support

**Where this came from:** Clinical Advisory Board sessions on core medical values

**What you'll build:**
- **Feature**: As a GP, I want the AI to clearly indicate confidence levels for each diagnostic suggestion so that I can make informed decisions about how much weight to give the recommendations
  - **How you'll know it works**: 
    - [ ] If confidence is below 70%, when AI provides suggestion, then clear warning is displayed
    - [ ] If multiple diagnoses are suggested, when ranked by confidence, then most likely appears first with percentage
  - **How you'll test it**: Clinical simulation with test cases of varying diagnostic complexity

- **Feature**: As a GP, I want to see the key evidence the AI used for each suggestion so that I can validate the reasoning against my clinical knowledge
  - **How you'll know it works**: 
    - [ ] If diagnostic suggestion is provided, when I click "Show Reasoning", then key symptoms and risk factors are displayed
    - [ ] If evidence contradicts my observation, when I review reasoning, then I can identify potential errors
  - **How you'll test it**: Expert review sessions with consultant physicians

**Behind-the-scenes requirements:**
- The system needs to log all diagnostic suggestions and GP responses so that we can monitor accuracy and identify bias patterns
  - **How you'll measure**: Percentage agreement between AI suggestions and final GP diagnoses
  - **Target**: >85% alignment for high-confidence suggestions
  - **Check frequency**: Weekly analysis during pilot phase

### Transparency in AI Reasoning & Clinician Autonomy

**Where this came from:** Professional standards workshops with Royal College of GPs

**What you'll build:**
- **Feature**: As a GP, I want to easily override or dismiss AI suggestions so that my clinical judgement remains paramount
  - **How you'll know it works**: 
    - [ ] If I disagree with AI suggestion, when I click "Dismiss", then suggestion is removed without affecting workflow
    - [ ] If I choose different diagnosis, when I enter it, then system accepts without resistance or warnings
  - **How you'll test it**: Usability testing with practising GPs

### Data Privacy Protection

**Where this came from:** NHS Information Governance requirements

**What you'll build:**
- **Feature**: As a practice manager, I want all patient data to remain within NHS-approved infrastructure so that we comply with data protection requirements
  - **How you'll know it works**: 
    - [ ] If patient data is processed, when AI analysis occurs, then all computation happens on NHS-approved servers
    - [ ] If patient consultation ends, when session closes, then no patient data is retained in AI system memory
  - **How you'll test it**: Independent security audit and penetration testing

## Should-Do Features

### Equity of Care

**Where this came from:** Health inequality focus groups with community representatives

**What you'll build:**
- **Feature**: As a GP serving diverse communities, I want the AI to flag when diagnostic patterns might reflect demographic bias so that I can ensure equitable care
  - **How you'll know it works**: 
    - [ ] If demographic patterns emerge in diagnoses, when monthly analysis runs, then alerts are generated for review
    - [ ] If certain groups receive fewer referrals, when pattern is detected, then practice receives guidance
  - **How you'll test it**: Retrospective analysis of anonymised diagnostic data across different demographic groups

### Continuous Learning & User-Friendly Interface

**Where this came from:** Clinical user experience sessions

**What you'll build:**
- **Feature**: As a GP, I want the interface to integrate seamlessly with my existing clinical system so that AI support doesn't disrupt my consultation flow
  - **How you'll know it works**: 
    - [ ] If patient record is opened in EMIS/SystmOne, when AI panel loads, then all relevant data appears automatically
    - [ ] If consultation proceeds normally, when AI suggestions appear, then they fit naturally into my workflow
  - **How you'll test it**: Time-and-motion studies comparing consultations with and without AI support

## Could-Do Features

### Support Less Experienced GPs

**Where this came from:** Training needs analysis with GP registrars

**What you'll build:**
- **Feature**: As a newly qualified GP, I want access to educational explanations about why certain diagnoses are suggested so that I can learn while I work
  - **How you'll know it works**: 
    - [ ] If diagnostic suggestion includes educational flag, when I request explanation, then relevant clinical guidelines appear
    - [ ] If rare condition is suggested, when explanation is shown, then key diagnostic criteria are highlighted
  - **How you'll test it**: Feedback sessions with GP trainees and assessment of learning outcomes

---

## Keeping Track of How You're Doing

### Checking Your Values Are Working

**What you'll track:** 
- Clinical safety metrics (diagnostic accuracy, patient outcomes)
- Professional acceptance (usage rates, override patterns)
- Equity measures (diagnostic patterns across demographics)

**How you'll track it:** 
- Automated system logs for usage patterns
- Monthly clinical review meetings
- Quarterly patient outcome analysis
- Annual equity audit

**How often you'll check:** Monthly safety reviews, quarterly outcome analysis

### Measuring Success

**What success looks like:** 
- 25% reduction in missed diagnoses during pilot phase
- >90% of GPs find system helpful rather than intrusive
- No increase in diagnostic disparities across demographic groups
- System uptime >99.5% during consultation hours

**How you'll measure it:** 
- Retrospective case note analysis
- GP satisfaction surveys
- Demographic analysis of diagnostic patterns
- System availability monitoring

**Starting point:** 
- Current diagnostic accuracy baseline from practice audits
- Existing consultation time averages
- Current health outcome disparities

**Goals:** 
- Measurable improvement in diagnostic accuracy without compromising clinical autonomy
- Reduced variation in care quality across different practices
- Maintained or improved clinician satisfaction

---

## Keep This Updated

**Document version:** 1.0
**Last updated:** 2024-03-20
**Next review:** 2024-04-20
**Responsible person:** Dr Sarah Chen, Clinical Lead

Remember: This isn't about being perfect. It's about being intentional. Start with what you can handle, build it well, and learn as you go. You can always level up your approach for the next project.