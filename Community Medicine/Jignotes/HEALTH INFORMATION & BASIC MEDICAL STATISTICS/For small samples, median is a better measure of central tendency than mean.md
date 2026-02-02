---
status: pending
tags: [Biostatistics, CentralTendency, MedianVsMean, DataAnalysis, MedicalStatistics]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 411
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > For small samples, median is a better measure of central tendency than mean

### **Why Median is Superior to Mean in Small Samples**

In the field of [[Biostatistics]], choosing the correct measure of **Central Tendency** is crucial for accurate data interpretation. For small samples, the **Median** is often preferred over the **Mean** for the following reasons:

#### **1. Resistance to Outliers (Extreme Values)**
*   The **Arithmetic Mean** is highly sensitive to extreme values. In a small sample size, even a single [[Outlier]] (a value unusually high or low compared to others) can drastically pull the mean towards itself, distorting the result.
*   The **Median** is a **positional average**. It depends on the *rank order* of the data, not the magnitude of the extreme values. Therefore, it remains stable even if the extreme values change significantly.

#### **2. Representation of Reality**
*   In small samples, the distribution is rarely perfectly symmetrical (Normal).
*   When data is **Skewed** (asymmetrical), the Mean loses its ability to represent the "typical" value of the group. The Median remains the central point, dividing the distribution into two equal halves (50% above, 50% below) regardless of the skew.
*   *Source Insight:* The mean can sometimes look ridiculous or impossible in reality (e.g., "4.76 children born to a woman"), whereas the median always represents a real position within the distribution.

---

### **Illustrative Example**
To prove why the mean can be misleading in small samples, consider this example from the sources regarding the income of 7 people:

**Data Set:** 5, 5, 5, 7, 10, 20, **102** ($n=7$)

| Measure | Calculation | Result | Interpretation |
| :--- | :--- | :--- | :--- |
| **Mean** | $\frac{5+5+5+7+10+20+102}{7}$ | **22** | **Misleading.** The value 22 is higher than 6 out of 7 people's income. It is inflated by the single outlier (102). |
| **Median** | The middle value (4th item) | **7** | **Representative.** The value 7 is much closer to the majority of the group (who earn 5, 7, or 10). |

**Conclusion:** In this example, the Median (7) is "nearer to the truth" and more representative of the group than the Mean (22).

---

### **Comparison: Mean vs. Median**

| Feature | **Mean** ($\bar{x}$) | **Median** |
| :--- | :--- | :--- |
| **Calculation** | Uses **every** value in the data set. | Uses the **position** (middle value). |
| **Effect of Outliers** | **Highly affected.** | **Not affected** (Robust). |
| **Suitability** | Best for [[Normal Distribution]] (Symmetrical data). | Best for **Skewed Distribution** or Small Samples. |
| **Usefulness** | Essential for further statistical tests (e.g., SD, SE). | Good for descriptive statistics (e.g., survival time). |

---

### **Clinical Relevance**
In medical practice, the Median is the preferred measure for:
1.  **Incubation Periods:** Because some cases may have very long incubation periods (outliers), the [[Median Incubation Period]] is used to describe the typical time for symptom onset.
2.  **Survival Time:** In cancer studies, "Mean Survival Time" can be skewed by one patient living for 20 years while others live for months. "Median Survival Time" accurately reflects when 50% of the patients are still alive.
3.  **Length of Hospital Stay:** A few patients with complications may stay for months, skewing the mean. The median gives a better estimate for bed planning.

> [!warning] Diagram Alert
> A frequency distribution curve showing a positive skew (tail to the right). Mark the Mode at the peak, the Median slightly to the right, and the Mean pulled furthest to the right by the tail/outliers to demonstrate why Mean > Median in positive skew.

### **Mnemonic**
**"The Mean is MEAN (nasty) because it gets pulled around by bullies (outliers). The Median is the MEDIATOR—it stays calm in the middle."**

---
**Previous:** [[Graphical representation of statistical data]]  **Next:** [[The census is an important tool of health information]]