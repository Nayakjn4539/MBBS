---
status: pending
tags: [Biostatistics, TestOfSignificance, PValue, TTest, ChiSquare, Ztest, NullHypothesis]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 387
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Test of significances

### Test of Significance

**Tests of Significance** are mathematical methods used to determine the probability ($p$) that an observed difference between two groups (e.g., sample vs. population, or experiment vs. control) occurred purely by chance. These tests help researchers decide whether to accept or reject a hypothesis.

The ultimate goal is to rule out [[Sampling Error]] and establish if a result is statistically significant.

---

### 1. Basic Concepts and Steps

To perform a test of significance, the following standard steps are followed:

1.  **State the Null Hypothesis ($H_0$):** This assumes there is **no real difference** between the groups (e.g., Drug A is equal to Drug B). Any observed difference is due to chance.
2.  **State the Alternative Hypothesis ($H_1$):** This assumes there **is a significant difference** (e.g., Drug A is better than Drug B).
3.  **Determine the Level of Significance ($\alpha$):** Usually fixed at **5%** (0.05) or **1%** (0.01). This is the "zone of rejection." If the result falls in this zone, we reject $H_0$.
4.  **Calculate the Test Statistic:** Using specific formulas (e.g., $Z$, $t$, $\chi^2$) based on the data type.
5.  **Find the [[P-value]]:** The probability of the result occurring by chance.
    *   If **$P < 0.05$**: The difference is **Significant**. Reject $H_0$. (Chance is unlikely).
    *   If **$P > 0.05$**: The difference is **Not Significant**. Accept $H_0$. (Chance is likely).

> [!warning] Diagram Alert
> Normal distribution curve showing the Zone of Acceptance (95%) and Zone of Rejection (2.5% on each tail for a two-tailed test)

---

### 2. Types of Statistical Errors

When testing a hypothesis, two types of errors can occur:

| Error Type | Definition | Significance |
| :--- | :--- | :--- |
| **Type I Error ($\alpha$)** | Rejecting a **True** Null Hypothesis ($H_0$). | **False Positive**. Declaring a difference exists when it does not. (More serious in medicine). |
| **Type II Error ($\beta$)** | Accepting a **False** Null Hypothesis ($H_0$). | **False Negative**. Missing a difference that actually exists. |

*   **Power of a Test ($1 - \beta$):** The ability of a test to detect a difference when it actually exists.

> **Mnemonic for Errors:**
> *   **Type I is an Illusion:** You think you found something (effect), but there is nothing (False Positive).
> *   **Type II is a Miss:** You missed the effect that was actually there (False Negative).

---

### 3. Classification of Tests

Statistical tests are broadly divided based on the distribution of data:

#### A. Parametric Tests
*   **Assumption:** Data follows a [[Normal Distribution]] (Gaussian curve).
*   **Data Type:** Quantitative (Numerical) data.
*   **Parameters used:** Mean ($\bar{x}$) and Standard Deviation (SD).
*   **Examples:** t-test, Z-test, ANOVA.

#### B. Non-Parametric Tests
*   **Assumption:** Data does **not** follow a normal distribution (Skewed).
*   **Data Type:** Qualitative (Categorical) data or small samples.
*   **Parameters used:** Proportions, Percentages, Ranks.
*   **Examples:** Chi-square test, Wilcoxon rank-sum test.

---

### 4. Important Statistical Tests

#### **1. Z-Test (Standard Normal Variate)**
*   **Indication:** Used for **Large Samples** ($n > 30$).
*   **Application:**
    *   Comparing sample mean with population mean.
    *   Comparing two sample means.
    *   Comparing two proportions.
*   **Interpretation:** If the Z-value is $> 1.96$, the result is significant at the 5% level ($P < 0.05$).

#### **2. Student's t-test**
*   **Indication:** Used for **Small Samples** ($n < 30$) where population SD is unknown.
*   **Types:**
    *   **Unpaired t-test:** Compares means of **two independent** groups (e.g., Hb levels in males vs. females).
    *   **Paired t-test:** Compares means of the **same group** before and after an intervention (e.g., BP before and after giving an antihypertensive drug).

#### **3. Chi-Square Test ($\chi^2$)**
*   **Indication:** **Non-parametric** test for **Qualitative** data (Proportions/Frequencies).
*   **Applications:**
    *   **Test of Association:** e.g., Is there an association between *Smoking* and *Lung Cancer*?.
    *   **Goodness of Fit:** Does the observed distribution fit the theoretical expectation?.
    *   **Test of Proportions:** Comparing success rates of two drugs.
*   **Constraint:** The expected frequency in any cell of the contingency table must not be less than 5. If $< 5$, use **Fisher's Exact Test**.

#### **4. ANOVA (Analysis of Variance)**
*   **Indication:** Used to compare means of **three or more groups** simultaneously.
*   **Statistic:** F-ratio (F-test).
*   **Example:** Comparing the weight gain of infants on three different diets (Diet A, Diet B, Diet C).

---

### Summary Table of Tests

| Test | Data Type | Sample Size | Comparison |
| :--- | :--- | :--- | :--- |
| **Z-test** | Quantitative | Large ($>30$) | 2 Means / 2 Proportions |
| **Unpaired t-test** | Quantitative | Small ($<30$) | 2 Independent Means |
| **Paired t-test** | Quantitative | Small ($<30$) | Means of same group (Before/After) |
| **ANOVA (F-test)** | Quantitative | Any | **> 2** Means |
| **Chi-Square ($\chi^2$)** | Qualitative | Any | Association between attributes |
| **Fisher's Exact** | Qualitative | Small | Association (when cell count $<5$) |

---

### Clinical Relevance
*   **Drug Trials:** To prove a new drug is effective, we must reject the Null Hypothesis using these tests. If $P < 0.05$, the drug works better than chance.
*   **Epidemiology:** To determine if a risk factor (like smoking) is significantly associated with a disease (like cancer) using the [[Chi-Square Test]].

---
**Previous:** [[Sampling error]]  **Next:** [[Sampling methods]]