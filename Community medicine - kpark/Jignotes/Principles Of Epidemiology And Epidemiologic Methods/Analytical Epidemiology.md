---
status: pending
tags: [AnalyticalEpidemiology, CaseControlStudy, CohortStudy, RelativeRisk, OddsRatio, Confounding, Bias, PublicHealth, ResearchMethodology]
subject: Community medicine - kpark
topic: Principles Of Epidemiology And Epidemiologic Methods
up: 27
---

# [[Principles Of Epidemiology And Epidemiologic Methods]] > Analytical Epidemiology

### **Analytical Epidemiology**

**Analytical Epidemiology** constitutes the second major type of epidemiological studies. While descriptive epidemiology formulates hypotheses (Who, Where, When), analytical epidemiology is used to **test hypotheses** (How and Why). The subject of interest is the individual within the population, and the goal is to determine the etiology of disease.

These studies are essentially **Observational Studies** (the investigator does not intervene, only observes).

---

### **1. Case-Control Study**
Also known as **[[Retrospective Study]]**, **Trohoc Study**, or **Backward-looking study**.

*   **Concept:** The study proceeds from **Effect to Cause**. Both exposure and outcome (disease) have occurred before the start of the study.
*   **Method:** It compares a group of patients who have the disease (**[[Cases]]**) with a group of free from the disease (**[[Controls]]**) regarding the past history of exposure to a suspected risk factor.

#### **Basic Steps**
1.  **Selection of Cases:** 
    *   **Diagnostic Criteria:** Must be strictly defined.
    *   **Eligibility:** Usually new (incident) cases are preferred over old (prevalent) cases to avoid survival bias.
    *   Sources: Hospitals (easy, but selection bias) or General Population (difficult, but representative).
2.  **Selection of Controls:**
    *   Controls must be free from the disease under study.
    *   They must be similar to cases in all respects *except* for the disease status.
    *   Sources: Hospitals (patients with other diseases), Relatives, Neighbors.
3.  **[[Matching]]:**
    *   Process of selecting controls so they are similar to cases in certain variables (e.g., age, sex) to eliminate **[[Confounding Factors]]**.
    *   *Note:* Do not match the risk factor being studied!
4.  **Measurement of Exposure:**
    *   Obtained by interviews, questionnaires, or hospital records.
    *   Must be done precisely the same way for cases and controls to avoid **[[Interviewer Bias]]**.
5.  **Analysis:**
    *   Calculates **[[Odds Ratio]] (OR)**.

#### **Analysis: The 2x2 Table**

| | Disease Present (Cases) | Disease Absent (Controls) |
| :--- | :---: | :---: |
| **Exposure Present** | $a$ | $b$ |
| **Exposure Absent** | $c$ | $d$ |

**Odds Ratio (Cross Product Ratio):**
$$OR = \frac{ad}{bc}$$

*   **OR > 1:** Positive association (Risk factor is associated with disease).
*   **OR < 1:** Negative association (Protective factor).
*   **OR = 1:** No association.

> **Mnemonic:** **C**ase **C**ontrol uses **C**ross Product Ratio (Odds Ratio).

---

### **2. Cohort Study**
Also known as **[[Prospective Study]]**, **Incidence Study**, **Forward-looking study**, or **Cause to Effect study**.

*   **Concept:** The study proceeds from **Cause to Effect**.
*   **Cohort:** A group of people sharing a common characteristic (e.g., birth cohort, smokers cohort).
*   **Method:** A group of exposed individuals and a group of non-exposed individuals are followed up over time to see who develops the disease.

#### **Types of Cohort Studies**
1.  **Prospective Cohort:** Outcome has not occurred when the study begins (e.g., [[Framingham Heart Study]]).
2.  **Retrospective (Historical) Cohort:** Outcomes have occurred before the start of the investigation. Investigator goes back in time (via records) to define exposure groups and traces them forward.
3.  **Mixed (Ambispective):** Combination of both.

#### **Analysis**
Cohort studies provide the **Incidence Rate**, allowing the calculation of:

**A. [[Relative Risk]] (RR):**
Measures the strength of association.
$$RR = \frac{\text{Incidence among exposed}}{\text{Incidence among non-exposed}} = \frac{I_{exp}}{I_{non-exp}}$$

**B. [[Attributable Risk]] (AR):**
Indicates how much of the disease is attributed to the exposure. Important for clinical practice.
$$AR = \frac{I_{exp} - I_{non-exp}}{I_{exp}} \times 100$$

**C. Population Attributable Risk (PAR):**
Important for Public Health/Policy.
$$PAR = \frac{I_{total} - I_{non-exp}}{I_{total}} \times 100$$

> [!warning] Diagram Alert
> Flowchart comparing the direction of Case-Control (Disease -> Exposure) vs Cohort (Exposure -> Disease)

---

### **Comparison: Case-Control vs Cohort**

| Feature | Case-Control Study | Cohort Study |
| :--- | :--- | :--- |
| **Direction** | Effect $\rightarrow$ Cause (Backward) | Cause $\rightarrow$ Effect (Forward) |
| **Timing** | Retrospective | Prospective (mostly) |
| **Sample Size** | Small | Large |
| **Cost/Time** | Inexpensive, Rapid | Expensive, Time-consuming |
| **Suitability** | Rare **Diseases** | Rare **Exposures** |
| **Risk Measure** | **Odds Ratio (OR)** | **Relative Risk (RR)** |
| **Incidence** | Cannot calculate | **Can calculate** |
| **Bias** | Recall Bias, Selection Bias | Attrition Bias, Hawthorne Effect |
| **Example** | Thalidomide tragedy | Smoking & Lung Cancer (Doll & Hill) |

---

### **3. Other Analytical Studies**

#### **Cross-Sectional Study**
*   Also called **[[Prevalence Study]]**.
*   Provides a "snapshot" of a population at a single point in time.
*   Exposure and Outcome are measured simultaneously.
*   *Limitation:* Cannot establish temporal association (Chicken or Egg dilemma).

#### **Ecological Study**
*   **Unit of study:** **[[Population]]** (not individuals).
*   Uses aggregate data (e.g., per capita sugar consumption vs diabetes rates in different countries).
*   *Risk:* **[[Ecological Fallacy]]** (results from populations may not apply to individuals).

---

### **Bias and Confounding**

**1. [[Bias]]** (Systematic Error)
*   **Recall Bias:** Cases remember exposure better than healthy controls (common in Case-Control).
*   **Selection Bias:** Study group is not representative of the population.
*   **Berkesonian Bias:** Admission rate bias in hospital-based studies.
*   **Hawthorne Effect:** Subjects change behavior because they are being observed (Cohort).

**2. [[Confounding]]**
A factor associated with both the exposure and the disease, but is not the causal pathway.
*   *Example:* In a study of Alcohol $\rightarrow$ Lung Cancer, **Smoking** is a confounder.
*   **Methods to Control Confounding:**
    *   *Design Stage:* Randomization (Best), Restriction, Matching.
    *   *Analysis Stage:* Stratification, Multivariate Analysis.

---

### **Clinical Relevance**
*   **Establishing Causality:** Analytical epidemiology provides the evidence needed to apply **Bradford Hill's Criteria** (Temporality, Strength, Dose-Response, etc.).
*   **Risk Assessment:** RR helps clinicians advise patients on individual risks (e.g., "Smoking increases your risk of cancer by 10x").
*   **Public Health:** PAR helps policymakers decide which risk factors to target to save the most lives in a community.

---
**Previous:** [[Randomized Controlled Trials]]  **Next:** [[Experimental Epidemiology]]