---
status: pending
tags: [Biostatistics, StandardDeviation, NormalDistribution, MeasuresOfDispersion, CoefficientOfVariation, PublicHealth]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 382
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Measures of dispersion

### **Definition**
**[[Community Medicine/Jignotes/HEALTH INFORMATION & BASIC MEDICAL STATISTICS/Measures of dispersion]]** (also known as measures of variation or scatter) describe how individual observations are dispersed or spread around the central value (Mean). While the [[Mean]] gives the central point of a dataset, measures of dispersion indicate the **extent of variability** within that data.

> **Clinical Concept:** In medicine, no two measurements are exactly equal (e.g., blood pressure, pulse). Dispersion helps determine if a variation is **Biological** (due to chance/nature) or **Real** (due to external factors/pathology).

---

### **Classification of Measures of Variability**

| **For Individual Observations** | **For Samples** |
| :--- | :--- |
| 1. [[Range]] | 1. [[Standard Error of Mean]] |
| 2. [[Inter-quartile range]] | 2. SE of difference between two means |
| 3. [[Mean Deviation]] | 3. [[Standard Error of Proportion]] |
| 4. [[Standard Deviation]] (**Most Important**) | 4. SE of difference between two proportions |
| 5. [[Coefficient of Variation]] | 5. SE of correlation coefficient |

---

### **1. Range**
*   **Definition:** The difference between the highest and lowest values in a given set of data.
*   **Formula:** Range = Highest Value – Lowest Value.
*   **Characteristics:**
    *   It is the **simplest** measure of dispersion.
    *   It is **not satisfactory** because it is based only on two extreme values and ignores the distribution of all other observations in between.
*   **Clinical Relevance:** Used to define **"Normal Limits"** in biological characteristics (e.g., Systolic BP: 100–140 mmHg; Cholesterol: 150–250 mg/dl).

### **2. Mean Deviation**
*   **Definition:** The average of the deviations from the arithmetic mean, ignoring the positive or negative signs.
*   **Formula:** $\frac{\sum |X - \bar{X}|}{n}$
*   **Status:** Rarely used in medical statistics as it is mathematically less significant than Standard Deviation.

### **3. Inter-quartile Range**
*   **Definition:** The range between the **Upper Quartile ($Q_3$)** and the **Lower Quartile ($Q_1$)**.
*   **Calculation:**
    *   $Q_1$ (Lower Quartile): The point below which 25% of observations lie.
    *   $Q_3$ (Upper Quartile): The point below which 75% of observations lie.
    *   **Interquartile Range** = $Q_3 - Q_1$.
    *   **Semi-interquartile Range** = $(Q_3 - Q_1) / 2$.
*   **Significance:** It covers the **middle 50%** of observations and is better than the range as it excludes extremes.

### **4. Standard Deviation (SD)**
*   **Definition:** It is the **root-mean-square deviation**. It measures the spread of data around the mean.
*   **Status:** It is the **most frequently used** and generally the most appropriate measure of dispersion.
*   **Formula:** 
    $SD = \sqrt{\frac{\sum (x - \bar{x})^2}{n}}$ 
    *(Note: For small samples, use $n-1$ in the denominator)*.
*   **Interpretation:**
    *   **Large SD:** Values are widely scattered (wide curve).
    *   **Small SD:** Values are clustered closely around the mean (narrow curve).

**[[Normal Distribution]] and SD:**
In a normal curve, the SD defines the limits of normality:
*   **Mean $\pm$ 1 SD** covers **68%** of values.
*   **Mean $\pm$ 2 SD** covers **95%** of values (**Clinical "Normal" Limits**).
*   **Mean $\pm$ 3 SD** covers **99.7%** of values.

> **Mnemonic for Normal Curve Coverage:**
> **"1-2-3 rule corresponds to 68-95-99"**
> *   1 SD = 68%
> *   2 SD = 95%
> *   3 SD = 99.7%

> [!warning] Diagram Alert
> Normal distribution curve showing the bell shape, the central mean, and vertical lines representing -1SD, -2SD, -3SD and +1SD, +2SD, +3SD with the corresponding percentages (68%, 95%, 99.7%) indicated.

### **5. Coefficient of Variation (CV)**
*   **Definition:** A measure used to compare **relative variability**.
*   **Formula:** 
    $CV = (\frac{Standard Deviation}{Mean}) \times 100$
*   **Use:** It is a **unit-free** measure. It is used to compare the variability of:
    1.  Two different characters (e.g., Height in cm vs. Weight in kg).
    2.  Two groups with different magnitudes (e.g., Pulse rate in adults vs. children).

---

### **Clinical Relevance**
1.  **Defining Normality:** In medical practice, "Normal" usually covers the observations falling within **95% confidence limits** (Mean $\pm$ 2 SD). Values outside this range are often investigated for pathology.
2.  **Assessment of Prognosis:** Large deviations from the mean may have unfavorable prognostic value.
3.  **Quality Control:** SD is used to monitor laboratory equipment accuracy (Levy Jennings chart).

---
**Previous:** [[Standard deviation]]  **Next:** [[Normal curve vs normal distribution]]