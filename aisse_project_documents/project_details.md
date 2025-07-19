# Project Details Template

## Project Context
*(These details are project-specific and will not be included in any reusable patterns)*

**Title**
- <!--%PROJ_NAME-->MedAssist AI: Primary Care Diagnostic Support System
- <!--%PROJ_ID-->PROJ-2024-001

**Team/Organisation**
- Lead organisation: HealthTech Innovations Ltd
- Primary contact: Dr Sarah Chen, Chief Medical Officer (s.chen@healthtech-innovations.co.uk)
- Project website: https://github.com/healthtech-innovations/medassist-ai

**Timeline**
- Project start: January 2024
- Expected prototype completion: August 2024
- Target pilot deployment: January 2025
- Full deployment target: June 2025

**Current Development Stage**
<!--%CURRENT_STAGE-->Concept

**Project Description**
- AI-powered diagnostic support system to assist GPs in primary care settings
- Analyses patient symptoms, medical history, and basic test results to suggest potential diagnoses and recommended next steps
- Designed to reduce diagnostic errors and improve consistency of care across different practice settings
- Target metric: Reduce missed diagnoses by 25% whilst maintaining GP decision-making authority

### Context

**Purpose**
- Supports GPs in making more accurate and timely diagnoses during routine consultations
- Provides evidence-based treatment suggestions and referral recommendations
- Helps identify patients who may need urgent specialist care
- Aims to reduce health inequalities by ensuring consistent diagnostic quality regardless of GP experience level

**Environment**
- Deployed within NHS primary care practices across England
- Integrated with existing clinical systems (EMIS, SystmOne)
- Used during patient consultations with real-time diagnostic support
- Operates under strict clinical governance and MHRA medical device regulations
- Patient safety-critical environment where diagnostic errors can have serious health consequences

*(Note: The Framework does not provide legal or regulatory advice. Projects should ensure they adhere to all legal and regulatory requirements for the project)*

**Stakeholders**
- **Direct users**: General Practitioners, Practice Nurses, Clinical Decision Units
- **Affected parties**: Patients receiving care, NHS Trusts, Clinical Commissioning Groups
- **Decision makers**: NHS Digital, MHRA, Practice Partners, Medical Directors
- **Vulnerable groups**: Elderly patients, patients with multiple comorbidities, patients with rare conditions, non-English speakers

## Categorisation of use-case

*(Combination of Purpose + Environment)*

**Purpose/Role** *(What role does this AI play in users' lives?)*
Select ALL that apply:
<!--%PURPOSE_CODES-->
- [x] **Creates (C)** - Makes things for users (content creation, synthesis)
- [x] **Decides (D)** - Chooses for users (decision making, recommendations)
- [ ] **Finds (F)** - Finds things for users (identification, discovery, information retrieval)
- [x] **Predicts (P)** - Tells users what's coming (prediction, monitoring)
- [x] **Helps (H)** - Helps users do things (digital assistance, performance improvement)
- [ ] **Acts (A)** - Takes actions for users (process automation, robotic automation)
- [x] **Multiple (M)** - System performs multiple roles at different times or upon request
- [ ] **Unknown (?)** - The purpose or role of this system is not known or decided

**Environment** *(In what context is the system operating?)*
Select ONE (or ? for unknown):
<!--%ENVIRONMENT_CODE-->
- [ ] **Low-stakes (L)** - Entertainment, convenience, internal tools
- [ ] **Social-facing (S)** - Public interaction, reputation, relationships
- [x] **High-stakes (H)** - Safety, health, finance, legal decisions, well-being affecting
- [ ] **Unknown (?)** - The environment for the use-case is not known or decided

## Categorisation of System Design Forces
*(Combination of Control + Capability considerations)*

***Note**: Control relationship combines three underlying dimensions:*
- ***Autonomy**: Supervised → Monitored → Independent*
- ***Self-learning**: Static → Adaptive/Agentic → Self-modifying
- ***Persistence**: Transactional → Stateful → Persistent operation*

**Control Relationship** *(What's the human-system control dynamic?)*
Select ONE (or ? for unknown):
<!--%CONTROL_CODE-->
- [ ] **Human-Controlled (C)** - Supervised autonomy + Static modification + Transactional interaction
- [x] **Human-Guided (G)** - Monitored autonomy + Adaptive/agentic + Stateful interaction
- [ ] **System-Independence (I)** - Independent/Agent autonomy + Self-modifying + Persistent operation
- [ ] **Unknown (?)** - The control relationship is not known or decided

**Capability Level** (What's the sophistication and power of the underlying system?)
Select ONE (or ? for unknown):
<!--%CAPABILITY_CODE-->
- [ ] **Basic (B)** - Simple algorithms, narrow processing (rule-based, basic ML). Does what you expect, clear decisions, predictable failures
- [x] **Advanced (A)** - Sophisticated models with reasoning (LLMs, multimodal models, complex ML), some surprises, novel failure modes. 
- [ ] **Emergent (E)** - Systems with unexpected or hard-to-predict capabilities. May surprise you with new capabilities, unclear boundaries 
- [ ] **Unknown (?)** - The capability level of the system is not known or decided


## Categorisation of Stakeholder and Cultural Forces

Select cultural contexts (can select multiple or ALL for universal):

**Europe & Anglo**
- [x] **Anglo (ANG)** - [ ] **Latin Europe (LAE)** - [ ] **Nordic Europe (NOR)**
- [ ] **Germanic Europe (GER)** - [ ] **Eastern Europe (EEU)** - [ ] **Jewish/Hebrew (HEB)**

**Asia & Middle East**
- [ ] **Confucian Asia (CAS)** - [ ] **Korean-Japanese (KJP)** - [ ] **Southern Asia (SAS)**
- [ ] **Southeast Asia (SEA)** - [ ] **Central Asia (CAZ)** - [ ] **Persian/Iranic (PER)**
- [ ] **Arab (ARA)** - [ ] **Turkic (TUR)** - [ ] **Pacific Islander (PAC)**

**Americas**
- [ ] **Latin America (LAM)** - [ ] **North American Indigenous (NAI)** - [ ] **South American Indigenous (SAI)**

**Africa & Oceania**
- [ ] **Sub-Saharan Africa (SSA)** - [ ] **African Indigenous (AFI)** - [ ] **Australian Indigenous (AUI)**

**Arctic**
- [ ] **Arctic Indigenous (ARI)** - [ ] **Indigenous Generic (IND)** 

- [ ] **ALL CULTURES (ALL)**


**Classification Notes**: 
- **Arrays allowed**: Projects can use [CDF] for multiple purposes or [ANG,LAE] for multiple cultures
- **Unknown (?) usage**: Use when classification help is needed
- **Pattern matching**: System will find relevant patterns based on classification
- **Project-specific details**: Team, timeline, funding, and contact info will not be included in reusable pattern documents