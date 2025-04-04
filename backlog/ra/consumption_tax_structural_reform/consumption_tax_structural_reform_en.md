# Analysis of Structural Failures in Japan’s Consumption Tax System and Requirements Definition for System Redesign

---

## Chapter 1: Purpose of the Analysis

✅ Analytical Report  
— Analyzing Structural Failures in the Consumption Tax System

■ Purpose  
This chapter aims to identify the root causes of structural failures in Japan’s consumption tax system—introduced in 1989—through an analysis of its institutional structure, legal connectivity, and underlying design philosophy.

---

## Chapter 2: Background and Initial Requirements of the System

■ Background and Initial Objectives

The consumption tax was introduced with the following goals:

- Stabilization of tax revenue (a source less susceptible to economic fluctuations)  
- Fairness in taxation (correction of overreliance on income and corporate taxes)  
- Preparation for an aging society (as a source of social security funding)

Although these objectives appear rational, they were abstract slogans rather than concrete institutional requirements (e.g., coverage scope, legal integration, side effect evaluation), and no formal definition of system requirements was provided at inception.

---

## Chapter 3: Structural Problems and Post-Implementation Issues (Backlog)

■ Structural Problems and Post-Implementation Issues

- **Lack of Legal Compatibility**: No integration with civil, commercial, or tax laws; absence of system-level consistency led to numerous reactive amendments post-implementation (e.g., the Invoice System).

- **Conflict with Fiscal Structure**: Article 4 of the Public Finance Act prohibits deficit financing through government bonds, making the consumption tax an inflexible “pillar” of revenue.

- **Disconnection from Social Security**: While nominally a source of social security funding, the system fails to meet increasing social benefits, resulting in a repeated cycle of tax hikes.

- **Misalignment with Decentralization**: Though local consumption tax is collected, municipalities lack discretionary power, reinforcing central government dependency.

- **Lack of Economic Stimulus Function**: Despite expectations of stability, the regressive nature and consumption-suppressing effect of the tax exacerbate economic downturns.

---

## Chapter 4: Root Cause Analysis

■ Root Cause Analysis

- The system was treated as a “standalone application” without API design for integration with Japan’s legal framework (OS).  
- Implementation proceeded without legal amendments, leaving interface inconsistencies with the six major codes unresolved.  
- Due to political and institutional constraints, legal amendments remain difficult, and the growing backlog has turned into systemic debt.

---

## Chapter 5: Structural Validation Through As-Is/To-Be Gap Analysis

— Structural Validation via As-Is/To-Be Gap Analysis

🔹 1. Definition of System Objectives

- **As-Is (Current)**:  
  Officially aimed at “revenue stability” and “social security funding,”  
  but in reality prioritizes revenue supplementation,  
  containing regressive features that undermine redistributive fairness.

- **To-Be (Redesigned)**:  
  Reconstruct based on redistributive restructuring,  
  shifting taxation focus from consumption to surplus income and capital.

🔹 2. Legal Connectivity Structure

- **As-Is**:  
  Fragmented legislation (Consumption Tax Act, Local Tax Act, Public Finance Act, Income Tax Act, etc.)  
  lacks consistency.  
  Especially, Article 4 of the Public Finance Act prohibits tax cuts due to restrictions on bond-based expenditure.

- **To-Be**:  
  Redesign under the premise of legal consistency,  
  allowing an exception to Article 4 only when system redesign is based on the sovereign will.  
  Ensure integration across income, corporate, and financial taxation systems.

🔹 3. Structural Load and Consistency

- **As-Is**:  
  System flaws (e.g., the Invoice System) are patched operationally.  
  Local tax lacks actual discretion.  
  Social security funding is functionally broken, leaving only upward tax pressure.

- **To-Be**:  
  Abolish the consumption tax and invoice system; unify taxation under income-based tax.  
  Redesign local tax systems separately, ensuring municipal discretion and connection specifications.  
  Integrate social security considerations into tax system design from the start.

🔹 4. Structural Premises of Policy Implementation

- **As-Is**:  
  Slogan-driven, patchwork policies (e.g., “We’ll cut consumption tax,” “Double pensions”)  
  lack structural foundation and cause policy-structure misalignment.  
  No citizen participation; system design remains opaque.

- **To-Be**:  
  Policies to be drafted based on structural gap validation and redesign.  
  Ensure legal alignment with the six major codes, clarifying which parts require revision.  
  Legally establish a “Tax System Redesign Council” (tentative name) with citizen representation from the design stage.

✅ Summary of Gap Validation  

| Item                        | As-Is                              | To-Be                              |
|----------------------------|-------------------------------------|------------------------------------|
| **System Objective**        | Revenue stability, fiscal backup   | Redistributive system redesign     |
| **Fiscal Compatibility**    | Conflict with Public Finance Act   | Amend the act to allow redesign-based bond use |
| **Tax Structure**           | Consumption-based, regressive, invoice burden | Income/capital-based, aligned with redistribution |
| **Local Government Link**   | No real discretion with local tax  | Structural autonomy and discretion |
| **Policy-Structure Link**   | Slogans first, patch fixes later   | Structure-based implementation     |
| **Citizen Participation**   | Closed system, no public role      | Citizen participation from design phase |

---

## Chapter 6: Requirements Definition Phase for System Redesign

With these gaps now validated, we proceed to define the requirements necessary to institutionalize the redesigned system.

Acknowledged. Based on this, we will define a set of corrective requirements for the consumption tax abolition and structural redesign—structured clearly and hierarchically, like a systems engineering requirements document.

🛠️ Requirements Definition  
—Organizing the Corrective Policy for System Redesign

🔹 **Functional Objectives (Roles of the System)**

- Eliminate regressive effects in taxation and restore fair redistribution.  
- Ensure fiscal sustainability and systemic stability.  
- Restore integration and consistency across related legal frameworks.  
- Establish structural entry points for citizen involvement in system design.

🔹 **Correction Targets and Guidelines (By Structural Unit)**

1. **Consumption Tax Act & Local Tax Act**  
   - *Current*: Regressive, burdensome at field level, design–operation mismatch  
   - *Policy*: Abolish the system; new funding structure and integration to be designed separately

2. **Article 4 of the Public Finance Act**  
   - *Current*: Prevents co-existence of tax cuts and bond financing  
   - *Policy*: Clearly define exceptions allowing bond financing if redesign is based on the sovereign will

3. **Income, Corporate, and Financial Tax Laws**  
   - *Current*: Insufficient progressivity; underdeveloped surplus/capital taxation  
   - *Policy*: Reinforce progressivity and adapt capital/global taxation to enable redistribution

4. **Local Tax System**  
   - *Current*: Local grants via consumption tax are formalized; lacks municipal discretion  
   - *Policy*: Redesign as an independent module with guaranteed autonomy and transparency

5. **System Design Process (Citizen Participation)**  
   - *Current*: Design occurs in a closed environment with no public involvement  
   - *Policy*: Legally establish a permanent institution including citizen representatives in the design phase (e.g., Tax System Redesign Council)

