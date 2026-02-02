---
status: pending
tags: [Biostatistics, StandardDeviation, NormalDistribution, Variance, StandardError]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 381
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Standard deviation

### Standard Deviation (SD)

**Standard Deviation** is the most frequently used and generally the most appropriate measure of **dispersion** (variability) in medical statistics. It measures the spread or scatter of individual observations around the **Mean** [[Arithmetic Mean]].

#### 1. Definition
*   Technically defined as the **"Root-Mean-Square Deviation"**.
*   It is the square root of the arithmetic average of the squared deviations of measured values from the mean.
*   It is denoted by the Greek letter **sigma (σ)** for the population and the Roman letter **'s'** for a sample.

#### 2. Calculation Steps
To calculate the SD of a series of observations:
1.  **Calculate the Mean** ($\bar{x}$) of the series.
2.  **Find the Deviation** ($x - \bar{x}$) of each observation from the mean.
3.  **Square the Deviations** $(x - \bar{x})^2$.
4.  **Sum the Squares** $\sum(x - \bar{x})^2$.
5.  **Calculate Variance:** Divide the sum by the number of observations minus one ($n-1$) for sample data. This value is called [[Variance]] ($s^2$).
6.  **Square Root:** Take the square root of the variance to get the **Standard Deviation**.

**Formula:**
$$SD = \sqrt{\frac{\sum(x - \bar{x})^2}{n-1}}$$
*(Note: Use $(n-1)$ for small samples to correct for bias; for large populations, 'n' can be used)*.

#### 3. Interpretation
*   **Large SD:** Indicates that the data points are widely spread out and far from the mean.
*   **Small SD:** Indicates that the data points are clustered closely around the mean.

#### 4. Relationship with Normal Distribution (The Empirical Rule)
In a **Normal Distribution** (Gaussian curve), the SD defines the limits of normality.

> [!warning] Diagram Alert
> Draw a Normal Distribution Curve (Bell Curve). Mark the center as Mean. Mark vertical lines at ±1 SD, ±2 SD, and ±3 SD. Shade the area between ±1 SD as 68%, ±2 SD as 95%, and ±3 SD as 99.7%

| Range from Mean | Percentage of Values Covered | Interpretation |
| :--- | :--- | :--- |
| **Mean $\pm$ 1 SD** | **68.27%** (approx 68%) | Roughly 2/3rds of observations |
| **Mean $\pm$ 2 SD** | **95.45%** (approx 95%) | **Normal Limits** (Clinical Normality) |
| **Mean $\pm$ 3 SD** | **99.73%** (approx 99.7%) | Covers almost the entire range |

*   Values outside **Mean $\pm$ 2 SD** are considered **rare** (only 5% chance).
*   Values outside **Mean $\pm$ 3 SD** are considered **very rare** (<1% chance) and likely pathological.

#### 5. Uses of Standard Deviation
1.  **Summarizes Deviations:** It provides a single unit of variation for a large distribution.
2.  **Defines Normality:** It helps determine the normal range of biological characteristics (e.g., Height, BP).
3.  **Basis for Tests of Significance:** It is essential for calculating [[Standard Error]] (SE) and determining if differences between means are real or due to chance.
4.  **Sample Size Calculation:** It helps in finding the suitable size of a sample for valid conclusions.
5.  **Comparison:** It is used to calculate the [[Coefficient of Variation]] to compare variability between two different units of measurement.

---
### Clinical Relevance
**"Normal Range" in Medicine:**
When a lab report says the normal range for Hemoglobin is 12–16 g/dL, this range is usually statistically derived as **Mean $\pm$ 2 SD**. This covers 95% of the healthy population. The remaining 5% of healthy people might statistically fall outside this range without actually being sick.

---
### Mnemonic: The 68-95-99 Rule
To remember the area coverage under the normal curve:
*   **1** SD covers **68%** (One - Six - Eight)
*   **2** SD covers **95%** (Two - Nine - Five)
*   **3** SD covers **99.7%** (Three - Nine - Nine)

---
**Previous:** [[Uses of standard deviation]]  **Next:** [[Community Medicine/Jignotes/HEALTH INFORMATION & BASIC MEDICAL STATISTICS/Measures of dispersion]]