---
status: pending
tags: [predictive_values, PPV, NPV, screening, biostatistics, epidemiology, prevalence, Bayes_theorem, diagnostic_accuracy]
subject: Community medicine - kpark
topic: Screening For Disease
up: 35
---

# [[Screening For Disease]] > Predictive Values

### Predictive Values (PPV and NPV)

**Predictive values** reflect the [[diagnostic power]] of a test. Unlike sensitivity and specificity, which describe the test's intrinsic characteristics, predictive values describe the **probability of having (or not having) the disease** given a specific test result. They are heavily dependent on the disease [[prevalence]] in the population.

> [!warning] Diagram Alert
> 2x2 contingency table showing Disease Status (Present/Absent) in columns and Test Result (Positive/Negative) in rows, labeling a(TP), b(FP), c(FN), d(TN)

#### The 2x2 Contingency Table
To calculate predictive values, data is organized as follows:

| **Test Result** | **Disease Present** | **Disease Absent** | **Total** |
| :--- | :--- | :--- | :--- |
| **Positive (+)** | True Positive (**a**) | False Positive (**b**) | **a + b** (Total Test Positives) |
| **Negative (-)** | False Negative (**c**) | True Negative (**d**) | **c + d** (Total Test Negatives) |
| **Total** | **a + c** (Total Diseased) | **b + d** (Total Healthy) | **N** (Total Population) |

---

### 1. Positive Predictive Value (PPV)

*   **Definition:** The ability of a screening test to identify correctly all those who **actually have the disease**, out of all those who test positive.
*   **Clinical Question:** "Doctor, my test is positive. What are the chances I actually have the disease?".
*   **Formula:**
    $$PPV = \frac{\text{True Positives } (a)}{\text{Total Test Positives } (a + b)} \times 100$$
    *   Also expressed as: $\frac{TP}{TP + FP} \times 100$.
*   **Significance:** It represents the **post-test probability** of the disease given a positive result.

### 2. Negative Predictive Value (NPV)

*   **Definition:** The ability of a screening test to identify correctly all those who **do not have the disease**, out of all those who test negative.
*   **Clinical Question:** "Doctor, my test is negative. How sure can we be that I am healthy?".
*   **Formula:**
    $$NPV = \frac{\text{True Negatives } (d)}{\text{Total Test Negatives } (c + d)} \times 100$$
    *   Also expressed as: $\frac{TN}{TN + FN} \times 100$.
*   **Significance:** It provides the probability of being disease-free given a negative result.

---

### The "Golden Rule": Dependence on Prevalence

Unlike Sensitivity and Specificity (which are fixed properties of a test), **Predictive Values vary according to the prevalence** (pre-test probability) of the disease in the population tested.

> [!warning] Diagram Alert
> Graph showing the relationship between Prevalence (x-axis) and Predictive Values (y-axis). PPV curve rises with prevalence; NPV curve falls with prevalence

#### Relationship Dynamics
1.  **PPV and Prevalence:** Directly Proportional.
    *   As [[prevalence]] **increases**, the **PPV increases**.
    *   **Clinical Relevance:** If you use a very good test (High Sensitivity/Specificity) on a **low prevalence** population (e.g., mass screening of general population for a rare cancer), the PPV will be **LOW**. This results in a high number of **False Positives**.
2.  **NPV and Prevalence:** Inversely Proportional.
    *   As [[prevalence]] **increases**, the **NPV decreases**.
    *   **Clinical Relevance:** In a high-risk setting (high prevalence), a negative test is less reassuring than in a low-risk setting because the chance of a **False Negative** is statistically higher.

#### Bayes' Theorem
This theorem mathematically relates predictive values to sensitivity, specificity, and prevalence:

$$PPV = \frac{\text{Sensitivity} \times \text{Prevalence}}{(\text{Sensitivity} \times \text{Prevalence}) + ((1 - \text{Specificity}) \times (1 - \text{Prevalence}))}$$

---

### Differences: Reliability vs. Validity vs. Predictive Value

| Parameter | Focus | Dependency |
| :--- | :--- | :--- |
| **[[Sensitivity]] / [[Specificity]]** | **Validity (Accuracy)**. How well the test picks up disease/health. | **Fixed**. Stable properties of the test kit/method. |
| **[[Reliability]] (Precision)** | **Reproducibility**. Getting the same result on repeat testing. | Dependent on observer variation and technical errors. |
| **Predictive Values (PPV/NPV)** | **Diagnostic Power**. Usefulness in clinical decision making. | **Variable**. Highly dependent on **Disease Prevalence**. |

---

### Clinical Application Example

**Scenario:** A test has 90% Sensitivity and 90% Specificity.
*   **High Risk Setting (Prevalence 40%):** A patient presents with a breast lump (Diagnostic test).
    *   **PPV = 86%**. A positive result strongly suggests cancer.
*   **Low Risk Setting (Prevalence 1%):** Asymptomatic women screened (Screening test).
    *   **PPV = 8.3%**. A positive result is more likely to be a **False Positive** than cancer.

**Take Home Message:** A positive result in a screening program (low prevalence) is *not* a final diagnosis; it usually requires a confirmatory diagnostic test because of the lower PPV.

---

### 💡 Mnemonics

*   **PPV loves P:** **P**ositive Predictive Value moves **P**arallel to **P**revalence. (Prevalence $\uparrow$ = PPV $\uparrow$).
*   **NPV hates P:** **N**egative Predictive Value is **N**ot friendly with Prevalence. (Prevalence $\uparrow$ = NPV $\downarrow$).
*   **P**PV uses **P**ositive results as the denominator (a+b).
*   **N**PV uses **N**egative results as the denominator (c+d).

---
**Previous:** [[Sensitivity and Specificity]]  **Next:** [[Validity vs Reliability]]