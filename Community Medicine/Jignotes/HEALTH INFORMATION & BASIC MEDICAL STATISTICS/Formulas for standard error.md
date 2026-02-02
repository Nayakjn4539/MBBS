---
status: pending
tags: [StandardError, Biostatistics, MedicalStatistics, SamplingError, ZTest, StandardDeviation]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 400
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Formulas for standard error

### **Standard Error (SE): Concept and Formulas**

[[Standard Error]] is a measure of the variability of sample summaries (like means or proportions) derived from a population. It measures the likely **divergence of the sample estimate from the true population parameter due to chance** (sampling error). It is *not* a measure of a mistake, but of biological variation.

> **Key Concept:** Standard Error is inversely proportional to the square root of the sample size ($n$). To reduce the SE (increase precision), you must increase the sample size.

---

### **1. Standard Error of Mean ($SE_{\bar{x}}$)**

This is the standard deviation of the sampling distribution of the means. It is used for quantitative data (e.g., Height, Weight, BP).

**Formula:**
$$SE_{\bar{x}} = \frac{SD}{\sqrt{n}}$$
*OR*
$$SE_{\bar{x}} = \frac{\sigma}{\sqrt{n}}$$

*   **SD / $\sigma$** = Standard Deviation of the sample or population
*   **$n$** = Sample size

**Applications:**
*   To estimate [[Confidence Limits]] within which the population mean lies (Mean $\pm$ 1.96 SE).
*   To determine if a sample is drawn from a known population.
*   To calculate the required [[Sample Size]].

---

### **2. Standard Error of Proportion ($SE_p$)**

This is used for qualitative data (e.g., percentage of cured patients, morbidity rates).

**Formula:**
$$SE_p = \sqrt{\frac{pq}{n}}$$

*   **$p$** = Percentage/Proportion of positive character (e.g., disease present)
*   **$q$** = Percentage/Proportion of negative character ($1 - p$ or $100 - p$)
*   **$n$** = Sample size

**Applications:**
*   To check if an observed proportion in a sample differs significantly from the population proportion.

---

### **3. Standard Error of Difference Between Two Means**

Used to test the significance of the difference between the means of two independent large samples (e.g., Mean height of boys vs. Mean height of girls).

**Formula:**
$$SE_{(d)} = \sqrt{\frac{\sigma_1^2}{n_1} + \frac{\sigma_2^2}{n_2}}$$
*OR (using sample SD)*
$$SE_{(d)} = \sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}$$

*   **$\sigma_1^2, s_1^2$** = Variance (square of SD) of the first sample
*   **$\sigma_2^2, s_2^2$** = Variance of the second sample
*   **$n_1, n_2$** = Size of the first and second samples respectively

**Applications:**
*   Used in the [[Z-test]] (for $n > 30$) to accept or reject the Null Hypothesis ($H_0$).

---

### **4. Standard Error of Difference Between Two Proportions**

Used to test if the difference between two rates or percentages is statistically significant (e.g., Cure rate of Drug A vs. Drug B).

**Formula:**
$$SE_{(p_1 - p_2)} = \sqrt{\frac{p_1q_1}{n_1} + \frac{p_2q_2}{n_2}}$$

*   **$p_1, q_1$** = Proportions in the first sample
*   **$p_2, q_2$** = Proportions in the second sample
*   **$n_1, n_2$** = Sample sizes

*Note: Sometimes a pooled estimate (P) is used for calculation under the assumption of the null hypothesis:*
$$SE_{(p_1 - p_2)} = \sqrt{PQ \left( \frac{1}{n_1} + \frac{1}{n_2} \right)}$$
Where $P = \frac{n_1p_1 + n_2p_2}{n_1 + n_2}$ and $Q = 1 - P$.

---

### **Summary Table of Formulas**

| Statistic | Formula | Symbol Key |
| :--- | :--- | :--- |
| **SE of Mean** | $\frac{SD}{\sqrt{n}}$ | SD = Standard Deviation<br>n = Sample size |
| **SE of Proportion** | $\sqrt{\frac{pq}{n}}$ | p = % of occurrence<br>q = 1 - p |
| **SE Diff. (Means)** | $\sqrt{\frac{SD_1^2}{n_1} + \frac{SD_2^2}{n_2}}$ | $SD_{1,2}$ = SD of respective groups |
| **SE Diff. (Proportions)**| $\sqrt{\frac{p_1q_1}{n_1} + \frac{p_2q_2}{n_2}}$ | $p_{1,2}$ = Proportion of respective groups |

---

### **Clinical Relevance**
*   **Hypothesis Testing:** These formulas are the denominator in calculating the **Z-score** (Critical Ratio).
    *   $Z = \frac{\text{Observed Difference}}{Standard Error}$.
    *   If $Z > 1.96$, the result is significant at $P < 0.05$ (the difference is real and not due to chance).
*   **Confidence Intervals:** Doctors use SE to calculate the 95% Confidence Interval ($Mean \pm 2 SE$). If the CI does not include the null value, the finding is significant.

---

### **Mnemonics**

**1. For SE of Mean:**
**"S**ome **P**eople **D**ivide **R**oots"
*   **S**tandard Error = **S**tandard **D**eviation **Divided** by **Root** of n.

**2. For SE of Proportion:**
**"P**ea**Q**u-**N"** (Peacock-N)
*   **P** $\times$ **Q** divided by **N** (all under the root umbrella).

---
**Previous:** [[Pictogram]]  **Next:** [[Describe stratified sampling and its purpose]]