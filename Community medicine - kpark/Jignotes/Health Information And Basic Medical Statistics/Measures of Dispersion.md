---
status: pending
tags: [Biostatistics, MeasuresOfDispersion, StandardDeviation, NormalDistribution, HealthInformation]
subject: Community medicine - kpark
topic: Health Information And Basic Medical Statistics
up: 173
---

# [[Health Information And Basic Medical Statistics]] > Measures of Dispersion

### **Measures of Dispersion (Variability)**

In medical statistics, an average (Mean, Median, Mode) alone is insufficient to describe a set of data. We must know how the values are scattered or dispersed around that average. This is known as **Dispersion** or **Variability**.

Biological data is inherently variable (e.g., Blood pressure varies from person to person). Measures of dispersion help quantify this [[Biological Variability]].

The commonly used measures of dispersion are:
1.  **Range**
2.  **Mean Deviation**
3.  **Standard Deviation (SD)**
4.  **Coefficient of Variation (CV)**

---

### **1. The Range**
It is the simplest measure of dispersion.
*   **Definition:** It is the difference between the **highest** and the **lowest** values in a given set of data.
*   **Formula:** $Range = Highest\ Value - Lowest\ Value$
*   **Characteristics:**
    *   It is based only on two extreme values.
    *   It ignores the distribution of all other observations within the extremes.
    *   It is not a satisfactory measure for detailed statistical analysis but gives a rough idea of the spread.
*   **Interquartile Range (IQR):** A more robust version, defined as the difference between the 75th percentile ($Q3$) and the 25th percentile ($Q1$). It covers the middle 50% of the data.

---

### **2. Mean Deviation**
*   It is the average of the deviations from the arithmetic mean.
*   It is calculated by taking the sum of deviations from the mean (ignoring the positive or negative signs) and dividing by the total number of observations.
*   **Drawback:** It is mathematically less valid because it ignores the algebraic signs (+/-), hence it is rarely used in medical statistics.

---

### **3. Standard Deviation (SD)**
This is the **most frequently used** and most important measure of dispersion.

*   **Definition:** It is the **Root-Mean-Square Deviation**. It is the square root of the arithmetic average of the squares of the deviations measured from the mean.
*   **Symbol:** Denoted by the Greek letter **Sigma ($\sigma$)** for population or **'s'** for sample.
*   **Calculation Steps:**
    1.  Calculate the Mean ($\bar{x}$).
    2.  Find the deviation of each value from the mean ($x - \bar{x}$).
    3.  Square each deviation $(x - \bar{x})^2$.
    4.  Sum the squared deviations ($\Sigma(x - \bar{x})^2$).
    5.  Divide by the number of observations minus one ($n-1$) to get **Variance**.
    6.  Take the square root of the Variance to get [[Standard Deviation]].

$$SD = \sqrt{\frac{\sum (x - \bar{x})^2}{n - 1}}$$

*   **Interpretation:**
    *   **Large SD:** Data points are widely spread (high variability).
    *   **Small SD:** Data points are clustered closely around the mean (low variability).

**Clinical Relevance:**
SD helps define the **"Normal Limits"** of a biological characteristic (e.g., Height, BP). Values lying outside `Mean ± 2SD` are generally considered abnormal.

---

### **4. Coefficient of Variation (CV)**
*   **Definition:** It is a measure of relative variability. It is the Standard Deviation expressed as a percentage of the Mean.
*   **Formula:**
    $$CV = \frac{SD}{Mean} \times 100$$
*   **Use:** It is used to compare the variability of two different entities with different units (e.g., comparing the variation in **Height** in cm vs **Weight** in kg).

---

### **5. Normal Distribution (Gaussian Distribution)**
Most biological variables (e.g., Height, Weight, BP, IQ) follow a pattern where most values cluster around the center, and fewer values are found at the extremes. This pattern forms a **Normal Curve**.

**Characteristics of a Normal Curve:**
1.  **Shape:** [[Bell-shaped curve]].
2.  **Symmetry:** Bilaterally symmetrical. The left side is a mirror image of the right.
3.  **Central Tendency:** **Mean = Median = Mode**. They all coincide at the center peak.
4.  **Area:** The total area under the curve is 1 (or 100%).
5.  **Touch:** The curve approaches the baseline but **never touches** it (asymptotic).

> [!warning] Diagram Alert
> Normal Distribution Curve showing the bell shape with vertical lines marking Mean, +1SD, +2SD, +3SD and -1SD, -2SD, -3SD

**Distribution of Values (The 68-95-99 Rule):**
In a normal distribution, the data is distributed around the mean in a specific ratio:

| Range (Limits) | Coverage of Observations | Interpretation |
| :--- | :--- | :--- |
| **Mean $\pm$ 1 SD** | **68%** (approx 68.3%) | 68% of normal people fall in this range. |
| **Mean $\pm$ 2 SD** | **95%** (approx 95.4%) | **Clinical Norm:** This defines the "Normal Range". Only 5% of values lie outside this. |
| **Mean $\pm$ 3 SD** | **99.7%** (approx 99.73%) | Almost all observations are included. Values outside this are extremely rare. |

**Standard Normal Deviate (Z-Score):**
It indicates how many Standard Deviations an observation ($x$) is away from the Mean ($\bar{x}$).
*   **Formula:** $Z = \frac{x - \bar{x}}{SD}$
*   If $Z = 2$, the value is 2 SDs above the mean.

---

### **Mnemonic Corner**

**Remembering Normal Distribution Properties:**
**"S.S. Bell Mean-Mode-Med"**
*   **S** - **S**ymmetrical
*   **S** - **S**tandard Deviation determines width
*   **Bell** - **Bell** Shaped
*   **Mean-Mode-Med** - All 3 coincide at the center.

**Remembering the Coverage Rule:**
**"1-2-3 gives 68-95-99"**
*   **1** SD = **68**%
*   **2** SD = **95**%
*   **3** SD = **99**%

---

### **Key Summary for Exams**

*   **Range:** Quick but rough estimate (Max - Min).
*   **SD:** Best measure of dispersion; square root of variance.
*   **CV:** Used to compare variability between different units.
*   **Normal Curve:** Mean=Median=Mode; 95% of values lie within Mean $\pm$ 2SD (Concept of "Normalcy").

---
**Previous:** [[Measures of Central Tendency]]  **Next:** [[Sampling Techniques]]