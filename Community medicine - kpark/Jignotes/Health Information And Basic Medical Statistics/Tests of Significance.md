---
status: pending
tags: [Biostatistics, TestsOfSignificance, ChiSquareTest, tTest, ZTest, ResearchMethodology, HypothesisTesting, QualitativeData, QuantitativeData]
subject: Community medicine - kpark
topic: Health Information And Basic Medical Statistics
up: 175
---

# [[Health Information And Basic Medical Statistics]] > Tests of Significance

# Tests of Significance (Z-test, t-test, Chi-square)

Statistical tests of significance are mathematical methods used to calculate the [[Probability (p-value)]] of an observed difference occurring by chance. These tests help determining whether to accept or reject the **Null Hypothesis ($H_0$)**.

### 1. Z-Test (Normal Deviate Test)
This is a parametric test based on the **normal distribution**.

**Prerequisites:**
*   **Sample Size:** Must be **Large** ($n > 30$).
*   Data: [[Quantitative data]].
*   Distribution: Variables assumed to follow a normal distribution.
*   Sampling: Randomly selected.

**Applications:**
1.  To test the significance of difference between a sample mean ($\bar{X}$) and a known population mean ($\mu$).
2.  To test the significance of difference between **two sample means** ($\bar{X}_1 - \bar{X}_2$).
3.  To test the significance of difference between a sample proportion and population proportion.
4.  To test the significance of difference between **two sample proportions** ($p_1 - p_2$).

**Formula:**
$$Z = \frac{\text{Observed Difference}}{\text{Standard Error (SE)}}$$

**Interpretation (Critical Values):**
If the calculated Z value is:
*   **> 1.96**: Significant at 5% level ($p < 0.05$). $H_0$ rejected.
*   **> 2.58**: Significant at 1% level ($p < 0.01$).
*   **< 1.96**: Not significant ($p > 0.05$). Difference is likely due to chance.

---

### 2. Student's t-Test
Developed by W.S. Gossett (pen name "Student"). This follows the **'t' distribution** and is used when the sample size is small.

**Prerequisites:**
*   **Sample Size:** **Small** ($n < 30$).
*   Data: [[Quantitative data]].
*   Distribution: Normal distribution.

**Types of t-tests:**

#### A. Unpaired t-test (Independent t-test)
*   **Use:** Applied to **two independent groups** to test if the difference between their means is real (e.g., Mean height of Group A vs. Group B).
*   **Degrees of Freedom (df):** $n_1 + n_2 - 2$
*   **Method:** Utilizes pooled variance.

#### B. Paired t-test
*   **Use:** Applied to **one sample** where each individual gives a pair of observations (Dependent observations).
*   **Scenario:** **Before and After** studies (e.g., BP before and after giving a drug).
*   **Degrees of Freedom (df):** $n - 1$
*   **Logic:** Eliminates individual sampling variation as the patient acts as their own control.

> [!warning] Diagram Alert
> Flowchart showing decision tree: Is data Quantitative? -> Yes -> Is n > 30? -> Yes (Z-test) / No (t-test). If No (t-test) -> Are groups paired? -> Yes (Paired t-test) / No (Unpaired t-test)

---

### 3. Chi-Square Test ($\chi^2$ Test)
A non-parametric test developed by Karl Pearson. It does not rely on the assumption of normal distribution.

**Prerequisites:**
*   **Data:** [[Qualitative data]] (Categorical/Discrete).
*   **Input:** Must use **actual numbers/frequencies**, NOT percentages or ratios.
*   **Sample:** Random.
*   **Constraint:** Expected frequency in any cell should **not be less than 5**.

**Applications:**
1.  **Test of Association:** To find if two attributes are associated (e.g., [[Smoking]] and [[Lung Cancer]]).
2.  **Test of Proportions:** To compare proportions in two or more groups (Alternative to Z-test for proportions, especially if $>2$ groups).
3.  **Goodness of Fit:** To determine if observed frequencies fit a theoretical distribution (e.g., Mendelian genetics ratio).

**Formula:**
$$\chi^2 = \sum \frac{(O - E)^2}{E}$$
*Where $O = \text{Observed frequency}$, $E = \text{Expected frequency}$*

**Degrees of Freedom (df):**
For a contingency table: $df = (c - 1)(r - 1)$
*(c = number of columns, r = number of rows)*

**Special Variations:**
*   **Yates Correction:** Used in a $2 \times 2$ table if the expected frequency in any cell is **< 5**. Formula is modified by subtracting 0.5 from the absolute difference $|O - E|$.
*   **Fisher's Exact Test:** Used if the sample size is very small ($< 30$) or cell values are too small for Chi-square.

---

### Comparison of Tests

| Feature | **Z-Test** | **t-Test** | **Chi-Square ($\chi^2$)** |
| :--- | :--- | :--- | :--- |
| **Data Type** | Quantitative (Means/Proportions) | Quantitative (Means) | Qualitative (Attributes/Counts) |
| **Sample Size** | **Large ($> 30$)** | **Small ($< 30$)** | Any (Expected cell count $\ge 5$) |
| **Distribution** | Normal | 't' distribution | Chi-square distribution |
| **Parametric?** | Yes | Yes | No (Non-parametric) |
| **Main Use** | Significance of difference between means/proportions | Significance of difference between means (Paired/Unpaired) | Test of Association / Goodness of fit |

### Clinical Relevance
*   **Drug Trials:** Used to compare the efficacy of a new drug vs. placebo. If outcome is BP reduction (Quantitative), use **t-test** (small trial) or **Z-test** (large trial). If outcome is Cured/Not Cured (Qualitative), use **Chi-square**.
*   **Epidemiology:** Chi-square is the primary test for Case-Control studies to determine if a risk factor (Exposure) is associated with a Disease.
*   **Physiology:** To define normal limits (Mean $\pm$ 2SD).

### Mnemonics for Remembrance

*   **"T for Tiny"**: **t**-test is for **T**iny (small) samples ($< 30$).
*   **"Z for Zeroing in on the Crowd"**: **Z**-test is for large crowds ($> 30$).
*   **"Chi is for Cate-gory"**: **Chi**-square is for **C**ategorical (Qualitative) data.
*   **"PAIRed is PRE & POST"**: Paired t-test is used for Pre-test and Post-test on the same group.

---
**Previous:** [[Sampling Techniques]]  **Next:** [[Approaches to Health Education]]