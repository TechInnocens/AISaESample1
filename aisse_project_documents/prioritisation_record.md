# AISaE byDesign: Implementation Approach Selection

*Choosing how much to take on and what matters most*

```yaml
project_info:
  project_id: "PROJ-2024-001"
```

## What You Have So Far

You've done the AISaE byDesign sessions and now you have:
- A list of values and/or principles that matter for your project's context
- Risks you want to avoid
- Good things you might be able to achieve
- Some ideas about how your AI should behave

Now what? This guide helps you decide how much to take on and what to prioritise.

---

# STEP 1: HOW MUCH ARE YOU TAKING ON?

## Three Approaches to Choose From

### Approach 1: "Keep It Simple" 

**What this means:**
- Focus on the most important stuff from your sessions
- Handle the biggest risks with basic solutions
- Write down what you decided and why

**Time commitment:**
- Maybe 5-10% of your development time
- You and your team figure out priorities
- Check in on risks when you hit major milestones

**Good for:**
- Solo developers or small teams
- Experimental or research projects
- Lower-risk applications
- First time trying this approach

---

### Approach 2: "Do It Properly"

**Everything from Approach 1, plus:**
- Implement more of the good ideas where you can
- Go after some of the positive opportunities you identified
- Be proactive about managing risks
- Actually talk to your users regularly when the tool is in-life

**Time commitment:**
- About 10-15% of your development time
- Get input from users or stakeholders to prioritise requirements
- Check progress regularly

**Good for:**
- Commercial projects with real users
- Systems people interact with publicly
- Teams with some experience doing responsible development

---

### Approach 3: "Set the Standard"
*Showing everyone how it should be done*

**Everything from Approaches 1 & 2, plus:**
- Implement the nice-to-have features too
- Pursue additional beneficial opportunities
- Comprehensive risk management
- Share what you learn with others

**Time commitment:**
- 20-25% of your development time
- Get feedback from the wider community
- Monthly check-ins, quarterly deep reviews
- Maybe get external people to check your work

**Good for:**
- High-stakes stuff (health, finance, safety, legal)
- Systems that affect lots of people
- Experienced teams who know what they're doing

### Quick check

**What kind of project is this?**
- [x] High-stakes (could really hurt people): Approach 2 minimum, Approach 3 better
- [ ] Public-facing (people are using it and affected): Approach 1 minimum, Approach 2 better  
- [ ] Low-stakes (mostly just affects you): Approach 1 might be enough

### Your Choice

**I'm going with Approach number (checkbox):**
<!--%APPROACH_NUMBER-->
- [ ] Approach 1: "Keep It Simple" 
- [x] Approach 2: "Do It Properly"
- [ ] Approach 3: "Set the Standard"

**Why:**
<!--%APPROACH_RATIONALE-->This is a high-stakes healthcare project that will affect patient safety and clinical decision-making. We need comprehensive risk management and stakeholder involvement, but as a first NHS deployment we want to focus on solid implementation rather than trying to set industry standards.

**Who decided this:** Clinical Advisory Board and Development Team

**Date:** 2024-03-15

---

# STEP 2: WHAT'S ACTUALLY IMPORTANT?

Your approach determines how you figure out priorities:

## For Approach 2: Ask Your Stakeholders  
**Process:** Get input from people who matter
- Invite users, customers, advisors - whoever has a stake
- Share what came out of your sessions
- Workshop together to decide priorities
- Use voting or discussion to resolve disagreements

---

## Priority Worksheet

Go through everything from your AISaE sessions and mark each as:
- **Must Address (High)** - Critical, can't ship without this
- **Should Address (Medium)** - Important, will do if we can
- **Could Address (Low)** - Nice bonus if we have time
- **Won't Address (Omit)** - Not this time

This will be based on input received, relevance to the project, but also the Approach you've chosen.

**Priority Setting Status:**
<!--%PRIORITIES_COMPLETE-->
- [x] Complete
- [ ] In Progress
- [ ] Not Started

### Your Values & Principles

| What Came Out of Sessions | Must/Should/Could/Won't | Why?             |
| ------------------------- | ----------------------- | ---------------- |
| Patient Safety First | M | Fundamental to medical practice, regulatory requirement |
| Clinical Decision Support | M | Core purpose of the system |
| Transparency in AI Reasoning | M | Essential for clinical trust and accountability |
| Equity of Care | S | Important for NHS values but secondary to safety |
| Clinician Autonomy | M | Critical for professional acceptance |
| Data Privacy Protection | M | Legal requirement under GDPR and NHS standards |
| Continuous Learning | S | Important for system improvement |
| User-Friendly Interface | S | Needed for adoption but not safety-critical |

### Risks to Handle

| Risk from Sessions | High/Med/Low/Omit | Why?             |
| ------------------ | ----------------- | ---------------- |
| Misdiagnosis leading to patient harm | H | Direct patient safety impact |
| Over-reliance on AI recommendations | H | Could undermine clinical judgement |
| Bias in diagnostic suggestions | H | Could worsen health inequalities |
| System downtime during consultations | M | Disruptive but has manual fallbacks |
| Data breach of patient records | H | Legal and ethical requirements |
| False confidence in AI accuracy | H | Could lead to complacency |
| Integration failures with NHS systems | M | Important for usability |
| Resistance from clinical staff | M | Needed for successful deployment |

### Good Things to Pursue

| Opportunity from Sessions | Must/Should/Could/Won't | Why?             |
| ------------------------- | ----------------------- | ---------------- |
| Reduce diagnostic errors | M | Primary beneficial outcome |
| Improve consistency of care | S | Important NHS goal |
| Support less experienced GPs | S | Valuable but not core requirement |
| Identify rare conditions earlier | C | Nice benefit but complex to implement |
| Reduce consultation time | C | Potential benefit but not primary goal |
| Generate clinical insights | C | Future opportunity, not initial focus |

---

## Next Steps: Two Parallel Paths

You've now prioritised everything from your sessions. Time to move forward on two parallel paths:

### Path A: Risk Management
1. **Risk Register** - Record your Must/Should/Could risks in the Risk Register
2. **Risk Threshold Setting** - Set acceptable risk levels for Must and Should risks
3. **Ongoing Risk Assessment** - Monitor and manage risks throughout development

### Path B: Feature Development  
1. **Feature Design Template** - Record your Must/Should/Could values and opportunities
2. **User Story Development** - Turn priorities into buildable features
3. **Implementation Planning** - Build your features with risk mitigations

**Documents to create next:**
- Use the **Risk Register** to record the risks from this MoSCoW prioritisation then move on to **Risk Threshold Setting**
- Use the **Feature Design Template** to record the values and opportunities from this MoSCoW prioritisation

---

## Keep This Updated

**Document version:** 1.0
**Last updated:** 2024-03-15
**Next review:** 2024-04-15
**Responsible person:** Dr Sarah Chen, Clinical Lead

Remember: This isn't about being perfect. It's about being intentional. Focus on what you can actually deliver and build from there.