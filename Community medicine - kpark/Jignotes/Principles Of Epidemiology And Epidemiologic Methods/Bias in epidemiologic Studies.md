---
status: pending
tags: [Bias, Epidemiology, SelectionBias, InformationBias, Confounding, ResearchMethodology, PreventiveAndSocialMedicine]
subject: Community medicine - kpark
topic: Principles Of Epidemiology And Epidemiologic Methods
up: 29
---

# [[Principles Of Epidemiology And Epidemiologic Methods]] > Bias in epidemiologic Studies

### **Definition**

[[Bias]] is defined as any **systematic error** in the determination of the association between the exposure and the disease. It results in an incorrect estimate of the association between exposure and risk of disease.

*   **Key Concept:** Unlike random errors (which affect precision and can be reduced by increasing sample size), **systematic errors (biases)** affect the **validity** (accuracy) of the study and cannot be eliminated simply by increasing the sample size.

> [!warning] Diagram Alert
> Flowchart showing the division of Total Error into Random Error (Sampling Error) and Systematic Error (Bias). Systematic Error further divides into Selection Bias, Information Bias, and Confounding.

---

### **Classification of Bias**

Biases are broadly classified into three main categories:
1.  **Selection Bias**
2.  **Information (Observation) Bias**
3.  **Confounding** (Often treated as a separate entity but distorts results like a bias)

#### **1. Selection Bias**
This occurs when the individuals or groups selected for the study differ systematically from the population of interest. The groups to be compared are differentially susceptible to the outcome even before the study begins.

*   **Prevalence-Incidence Bias (Neyman Bias):**
    *   Occurs in [[Case-control studies]] based on prevalent cases.
    *   It happens because early deaths (fatal cases) or rapid recoveries (mild cases) are excluded, leaving only survivors/chronic cases.
    *   *Clinical Relevance:* A study on MI looking only at survivors will miss the risk factors associated with sudden cardiac death.

*   **Admission Rate Bias (Berkson’s Bias):**
    *   A specific type of selection bias seen in **hospital-based case-control studies**.
    *   Occurs because admission rates to hospitals differ for different diseases (cases vs. controls).
    *   *Example:* If controls are selected from a digestive disease ward to study lung cancer, the association with smoking might be masked because digestive patients also have high smoking rates.

*   **Attrition Bias (Loss to Follow-up):**
    *   Seen in [[Cohort studies]] and Randomized Controlled Trials ([[RCT]]).
    *   Occurs when participants who drop out of the study differ systematically from those who remain.
    *   *Note:* If loss to follow-up is **>10%**, the validity of the study is questionable.

*   **Volunteer Bias (Self-selection Bias):**
    *   Volunteers are often healthier, more health-conscious, or different behaviorally than the general population.

*   **Healthy Worker Effect:**
    *   Workers usually exhibit lower overall death rates than the general population because the severely ill and disabled are ordinarily excluded from employment.

#### **2. Information (Observation) Bias**
This arises from systematic errors in measuring or collecting data on exposure or outcome.

*   **Recall Bias:**
    *   Most common in **Case-control studies**.
    *   Cases (diseased) are more likely to recall past exposures (especially negative ones) more accurately or vividly than controls (healthy).
    *   *Clinical Relevance:* Mothers of children with congenital anomalies are more likely to remember minor infections or drug intake during pregnancy compared to mothers of healthy babies.

*   **Interviewer Bias:**
    *   Occurs when the interviewer knows the hypothesis or the disease status and probes cases more thoroughly than controls.
    *   *Prevention:* Blinding the interviewer.

*   **Hawthorne Effect (Attention Bias):**
    *   Study subjects alter their behavior simply because they know they are being observed.
    *   *Example:* Doctors might wash hands more frequently if they know they are being monitored for hygiene compliance.

*   **Misclassification Bias:**
    *   Errors in categorizing either exposure or disease status.
    *   **Non-differential Misclassification:** Error is equal in both groups. Leads to **Bias toward the Null** (underestimation of effect).
    *   **Differential Misclassification:** Error differs between groups. Can exaggerate or hide the effect.

#### **3. Biases in Screening**
These create a false sense of improved survival.

*   **Lead Time Bias:**
    *   The "survival" appears longer because the disease was detected earlier by screening (during the preclinical phase) compared to clinical diagnosis, even if the actual time of death remains the same.
    *   *Concept:* It is a **Zero time shift bias**.

*   **Length Time Bias (Length Bias Sampling):**
    *   Screening tends to pick up cases with a **longer pre-clinical phase** (slow-growing, better prognosis) while missing rapidly progressive cases (which die before screening).
    *   This makes screening cases appear to have a better prognosis.

---

### **Mnemonics for Biases**

> **"BRAINS"**
> *   **B**erkesonian Bias (Hospital admission)
> *   **R**ecall Bias (Memory)
> *   **A**ttrition Bias (Loss to follow-up)
> *   **I**nterviewer Bias
> *   **N**eyman Bias (Prevalence-Incidence)
> *   **S**election Bias (General)

---

### **Control of Bias**

Different strategies are employed at the design and analysis stages to minimize bias.

#### **A. Randomization**
*   **The Heart of a Clinical Trial.**
*   It eliminates **Selection Bias**.
*   It ensures that both known and unknown **confounding factors** are distributed equally among the groups.
*   **Significance:** It ensures valid statistical tests and comparability.

#### **B. Blinding**
*   Used primarily to reduce **Information/Observation Bias**.

| **Type of Blinding** | **Who is Blinded?** | **Bias Eliminated** |
| :--- | :--- | :--- |
| **Single Blind** | Subject (Patient) | Subject Bias (e.g., Placebo effect) |
| **Double Blind** | Subject + Investigator (Doctor) | Subject Bias + **Observer/Interviewer Bias** |
| **Triple Blind** | Subject + Investigator + Analyst | All of the above + **Analyzer Bias** |

#### **C. Other Methods**
*   **Matching:** Primarily used to control **Confounding** (mostly in Case-Control studies). Note: Matching does *not* control selection bias; it forces similarity.
*   **Restriction:** Limiting the study to people with specific characteristics to remove confounders.
*   **Standardization:** Used to remove the effect of age/sex differences when comparing rates (e.g., Age-adjusted death rates).

---

### **Summary of Biases by Study Type**

| **Study Design** | **Common Biases** |
| :--- | :--- |
| **Case-Control** | Recall Bias, Berkson’s Bias, Interviewer Bias, Selection Bias |
| **Cohort** | Attrition Bias (Loss to follow-up), Healthy Worker Effect |
| **Screening** | Lead Time Bias, Length Time Bias |
| **RCT** | Subject variation, Observer bias (minimized by blinding) |

---
**Previous:** [[Experimental Epidemiology]]  **Next:** [[Association and Causation]]