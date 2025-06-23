# AISaE byDesign: Implementation Approach Selection

```yaml
project_info:
  project_id: ""
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
<!--%APPROACH_RATIONALE-->This is a high-stakes content moderation system affecting user safety and free expression. Approach 2 provides the right balance of thoroughness without overengineering for our current team size and timeline.

**Who decided this:** Development Team Lead

**Date:** 2024-12-01

---

# STEP 2: WHAT'S ACTUALLY IMPORTANT?

## Priority Worksheet

**Priority Setting Status:**
<!--%PRIORITIES_COMPLETE-->
- [ ] Complete
- [x] In Progress
- [ ] Not Started

### Your Values & Principles

| What Came Out of Sessions | Must/Should/Could/Won't | Why?             |
| ------------------------- | ----------------------- | ---------------- |
| Transparent decisions     | M                       | Users need to understand why content was moderated |
| Bias mitigation          | M                       | Critical for fair treatment across communities |
| Human oversight          | M                       | Final decisions should involve humans for complex cases |
| User appeal process      | S                       | Important for user trust but not core functionality |
| Cultural sensitivity     | S                       | Important for global deployment |

### Risks to Handle

| Risk from Sessions | High/Med/Low/Omit | Why?             |
| ------------------ | ----------------- | ---------------- |
| False positives silencing legitimate speech | H | Core risk that could harm user trust and platform reputation |
| Bias against minority communities | H | Could cause real harm to vulnerable users |
| Gaming by bad actors | M | Important but can be addressed iteratively |