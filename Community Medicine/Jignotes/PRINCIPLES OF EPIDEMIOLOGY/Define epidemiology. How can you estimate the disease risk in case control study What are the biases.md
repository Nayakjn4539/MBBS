---
status: pending
tags: [epidemiology, case_control_study, odds_ratio, bias, confounding, berkesonian_bias, recall_bias, matching, blinding]
subject: Community Medicine
topic: PRINCIPLES OF EPIDEMIOLOGY
up: 29
---

# [[PRINCIPLES OF EPIDEMIOLOGY]] > Define epidemiology. How can you estimate the disease risk in case control study? What are the biases in case control study including the process of elimination as applicable?

### Definition of Epidemiology

Epidemiology is defined by John M. Last as:
*"The study of the **distribution** and **determinants** of health-related states or events in specified populations, and the **application** of this study to the control of health problems."*,

It essentially comprises three main components:
1.  **Distribution:** Analysis by time, place, and person (Descriptive Epidemiology).
2.  **Determinants:** Geophysical, biological, behavioral, social, cultural, economic, and political factors that influence health (Analytical Epidemiology),.
3.  **Application:** Using this knowledge to promote, protect, and restore health.

> [!warning] Diagram Alert
> Draw the "Triangle of Epidemiology" showing Agent, Host, and Environment at the three corners

---

### Estimation of Disease Risk in Case-Control Study

In a [[Case-Control Study]], we cannot calculate the direct incidence rate because we do not work with a population at risk (we start with the disease). Therefore, we cannot calculate Relative Risk (RR) directly. Instead, we calculate an estimate of the relative risk known as the **[[Odds Ratio]]** (also called Cross-Product Ratio),.

**The 2x2 Contingency Table**
To calculate risk, data is arranged as follows:,,

| Exposure History | Cases (Disease Present) | Controls (Disease Absent) |
| :--- | :---: | :---: |
| **Exposed** | **a** | **b** |
| **Not Exposed** | **c** | **d** |

**Calculation of Odds Ratio (OR):**
The [[Odds Ratio]] is the ratio of the odds of exposure among the cases to the odds of exposure among the controls.

$$OR = \frac{a \times d}{b \times c}$$

**Interpretation of OR:**
*   **OR > 1:** Positive association (Exposure is a risk factor, e.g., Smoking and Lung Cancer).
*   **OR = 1:** No association (Exposure does not affect disease).
*   **OR < 1:** Negative association (Exposure is a protective factor, e.g., Green tea and Diabetes).

**Clinical Relevance:**
The Odds Ratio provides a valid estimate of the Relative Risk only if:
1.  The disease is rare.
2.  The cases are representative of all cases with the disease.
3.  The controls are representative of the population without the disease.

---

### Biases in Case-Control Studies and Process of Elimination

[[Bias]] is any systematic error in an epidemiological study that results in an incorrect estimation of the association between exposure and disease,.

#### 1. Common Biases,,,

*   **[[Recall Bias]] (Memory Bias):** Cases (diseased individuals) are more likely to remember/recall past exposure to risk factors more vividly than healthy controls.
    *   *Example:* Mothers of deformed babies recall drug intake during pregnancy better than mothers of normal babies.
*   **[[Selection Bias]]:** Systematic differences in characteristics between those selected for the study (cases/controls) and those who are not. The sample is not representative of the target population.
*   **[[Berkesonian Bias]] (Admission Rate Bias):** A specific type of selection bias seen in hospital-based studies. It arises because admission rates to hospitals differ for different diseases (e.g., controls selected from patients with other diseases might have different exposure patterns),.
*   **[[Interviewer Bias]]:** If the interviewer knows the hypothesis or the disease status, they may probe cases more thoroughly for exposure history than controls,.
*   **[[Confounding]]:** A factor associated with both the exposure and the disease, which distributes unequally between groups (e.g., Age, Sex, Social class),.

#### 2. Process of Elimination (Reduction of Bias),,

| Type of Bias | Method of Elimination / Reduction |
| :--- | :--- |
| **Selection / Berkesonian Bias** | • **Randomization:** The ideal method to remove known and unknown bias (though harder in case-control than RCTs).<br>• Select controls from more than one source (e.g., different diseases).<br>• Use population-based controls rather than hospital controls., |
| **Recall Bias** | • Verify data with objective records (e.g., hospital files, prescriptions) rather than relying solely on memory.<br>• Use biological markers of exposure where possible. |
| **Interviewer Bias** | • **[[Blinding]]:** Keep the interviewer unaware of who is a "case" and who is a "control" (Blind the interviewer).<br>• Use standardized questionnaires., |
| **Confounding** | • **[[Matching]]:** Selecting controls that are similar to cases in specific variables (e.g., if the case is a 50-year-old male, select a 50-year-old male control).<br>• **Stratification** or **Multivariate Analysis** during the data analysis phase., |

**Mnemonic for Biases:**
**"S.R.I.B."** (Think of a rib cage protecting the heart of the study)
*   **S** - **S**election Bias
*   **R** - **R**ecall Bias
*   **I** - **I**nterviewer Bias
*   **B** - **B**erkesonian Bias

---

---
**Previous:** [[Enlist the types of epidemiological studies. Discuss the importance of incubation period in epidemio]]  **Next:** [[Describe the salient features of different types of time trends in disease occurrence with suitable]]