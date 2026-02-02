---
status: pending
tags: [epidemiology, case_control_study, odds_ratio, bias, study_design, observational_study]
subject: Community medicine - kpark
topic: Principles Of Epidemiology And Epidemiologic Methods
up: 24
---

# [[Principles Of Epidemiology And Epidemiologic Methods]] > Case-Control Study

### Case-Control Study

**Case-Control Study**, often referred to as a **Retrospective Study**, is a type of analytical (observational) epidemiological study. It is the first approach used to test a causal hypothesis. The study proceeds backwards from **Effect to Cause**,.

> [!warning] Diagram Alert
> Schematic diagram of Case-Control Study Design showing Cases and Controls looking back at exposure history

#### **Synonyms**
*   Retrospective study
*   Backward-looking study
*   Effect-to-cause study
*   **TROHOC study** (Cohort spelled backwards),

---

### **Distinct Features**
1.  Both **exposure** and **outcome** (disease) have occurred *before* the start of the study.
2.  The study proceeds backwards from effect to cause.
3.  It uses a **Control** or comparison group to support or refute an inference.

---

### **Basic Steps in Conducting a Case-Control Study**

There are four basic steps involved in the study design:

#### **1. Selection of Cases and Controls**
This is the most crucial step.

*   **Selection of Cases (The Diseased):**
    *   **Definition:** The case must be defined by [[Diagnostic Criteria]] (e.g., Stage I breast cancer, histologically confirmed) and [[Eligibility Criteria]] (e.g., newly diagnosed cases within a specific time).
    *   **Sources:**
        *   **Hospitals:** Common and easy, but subject to selection bias.
        *   **General Population:** A random sample of all cases in a defined geographic area (population-based). This is scientifically superior but logistically difficult.

*   **Selection of Controls (The Non-Diseased):**
    *   Controls must be **free from the disease** under study.
    *   They must be as similar to the cases as possible (drawn from the same population source) except for the disease status.
    *   **Sources of Controls:**
        *   **Hospital Controls:** Patients with other diseases. *Caution:* Do not choose controls suffering from a disease known to be associated with the risk factor under study (e.g., using lung cancer patients as controls for a study on smoking and heart disease).
        *   **Relatives:** Spouses or siblings (unsuitable for genetic studies).
        *   **Neighborhood Controls:** People living in the same locality.
        *   **General Population:** Random sample from the healthy population.

#### **2. Matching**
*   **Definition:** The process of selecting controls so they are similar to cases in regards to certain variables (e.g., age, sex, social class).
*   **Purpose:** To eliminate [[Confounding factors]].
*   **Rule:** Do **not** match the suspected risk factor (exposure) being studied, otherwise, its etiological role cannot be determined.

#### **3. Measurement of Exposure**
*   Definitions and criteria for exposure must be defined *beforehand*.
*   Information is collected via interviews, questionnaires, or hospital records.
*   **Crucial Point:** Information must be obtained in **precisely the same manner** for both cases and controls to avoid [[Interviewer bias]].

#### **4. Analysis and Interpretation**
*   **Exposure Rates:** Calculate the frequency of exposure in cases vs. controls.
*   **Estimation of Risk:** Since we cannot measure incidence, we calculate the **[[Odds Ratio]] (OR)**.

---

### **Analysis: The 2x2 Contingency Table**

| | Disease Present (Cases) | Disease Absent (Controls) |
| :--- | :---: | :---: |
| **Exposure Present** | **a** | **b** |
| **Exposure Absent** | **c** | **d** |
| **Total** | **a + c** | **b + d** |

*   **Exposure Rate in Cases:** $a / (a+c)$
*   **Exposure Rate in Controls:** $b / (b+d)$

#### **Odds Ratio (Cross-Product Ratio)**
Since a case-control study does not provide incidence, [[Relative Risk]] cannot be calculated directly. We use the Odds Ratio (OR) as an estimate of Relative Risk.

$$ \text{Odds Ratio (OR)} = \frac{ad}{bc} $$

**Interpretation of OR:**
*   **OR = 1:** No association (Risk factor is not related to disease).
*   **OR > 1:** Positive association (Exposure increases disease risk).
*   **OR < 1:** Negative association (Exposure is a protective factor),.

---

### **Bias in Case-Control Studies**
Systematic errors (Bias) are a significant drawback of this design.

1.  **[[Recall Bias]] (Memory Bias):** Cases are more likely to remember past exposures (e.g., trauma, drug use) than healthy controls. *This is the most common bias in case-control studies.*
2.  **Selection Bias:** Cases and controls may not be representative of the general population.
3.  **[[Berkesonian Bias]] (Admission Rate Bias):** A specific type of selection bias seen in hospital-based studies where admission rates for different diseases vary.
4.  **Interviewer Bias:** The interviewer may probe cases more thoroughly than controls if they know the hypothesis.
5.  **Confounding:** A factor associated with both exposure and disease (e.g., Age, Smoking) distorts the result. Handled by **Matching**.

---

### **Advantages vs. Disadvantages**

| Advantages | Disadvantages |
| :--- | :--- |
| **Ideal for [[Rare Diseases]]** | Cannot measure **Incidence** or **Prevalence** |
| Rapid and Inexpensive (Quick results) | Prone to **Bias** (Recall, Selection) |
| Can study **multiple risk factors** for one disease | Selection of an appropriate Control group is difficult |
| No attrition (loss to follow-up) | Cannot calculate Relative Risk directly (Only OR) |
| No ethical risks (exposure already happened) | Cannot distinguish between causes and associated factors |

---

### **Mnemonics**

**"RETRO"** (for Case-Control features):
*   **R** - **R**are diseases (Best for).
*   **E** - **E**stimate of Relative Risk (Odds Ratio).
*   **T** - **T**ime (Quick and cheap).
*   **R** - **R**ecall Bias (Major disadvantage).
*   **O** - **O**dds Ratio (The calculation used).

**"MATCH"** (Why we match):
*   **M** - **M**aking groups comparable.
*   **A** - **A**ge/Sex (Common variables).
*   **T** - **T**o remove.
*   **C** - **C**onfounding.
*   **H** - **H**elps validity.

---

### **Clinical Relevance**
*   **Thalidomide Tragedy:** A classic case-control study linked thalidomide use in pregnancy to congenital limb defects.
*   **Lung Cancer & Smoking:** Doll and Hill’s early studies used this design to establish the link between smoking and cancer.
*   **Investigating Outbreaks:** When a food poisoning outbreak occurs, epidemiologists use case-control studies to compare what sick people ate versus what healthy people ate to identify the source.

---
**Previous:** [[Cross-sectional Studies]]  **Next:** [[Cohort Study]]