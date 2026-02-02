---
status: pending
tags: [Biostatistics, CentralTendency, MeanMedianMode, DataDispersion, PublicHealth]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 405
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Describe measures of central tendency with examples. Explain why median is a better measure of central tendency in a widely dispersed data.

### Measures of Central Tendency

An [[Average]] or a measure of central tendency is a value in a distribution around which other values are distributed. It provides a mental picture of the central value of a set of data.

There are three commonly used measures of central tendency:

#### 1. The Arithmetic Mean (Mean)
This is the most widely used measure in statistical calculations. It is calculated by summing all individual observations and dividing by the total number of observations.

*   **Formula:** $\bar{X} = \frac{\sum X}{n}$
    *   $\bar{X}$ = Mean
    *   $\sum$ = Summation
    *   $X$ = Individual observations
    *   $n$ = Number of observations

*   **Characteristics:**
    *   It utilizes **all** the observations in the data.
    *   It is mathematically operative and essential for calculating [[Standard Deviation]] and tests of significance.
    *   **Disadvantage:** It is unduly influenced by extreme values (outliers).

*   **Example:**
    *   Diastolic Blood Pressure of 10 individuals: 83, 75, 81, 79, 71, 95, 75, 77, 84, 90.
    *   Sum ($\sum X$) = 810
    *   Number ($n$) = 10
    *   **Mean** = 810 / 10 = **81.0**

#### 2. The Median
The median is the **middle value** of a distribution when the data is arranged in an ascending or descending order of magnitude. It divides the distribution into two equal halves.

*   **Calculation:**
    *   **Odd number of observations:** The middle value is the median [Formula: $(n+1)/2$ th item].
    *   **Even number of observations:** The average of the two middle values is the median.

*   **Characteristics:**
    *   It depends on the **position** of the value, not the magnitude of all values.
    *   It is **not** affected by extreme values (outliers).
    *   It is often nearer to the truth in skewed distributions.

*   **Example (Odd number):**
    *   Data: 71, 75, 75, 77, **79**, 81, 83, 84, 95.
    *   **Median** = **79** (The 5th value).

*   **Example (Even number):**
    *   Data: 71, 75, 75, 77, **79**, **81**, 83, 84, 90, 95.
    *   Middle values are 79 and 81.
    *   **Median** = (79 + 81) / 2 = **80**.

#### 3. The Mode
The mode is the most frequently occurring value in a series of observations. It is the "fashionable" value.

*   **Characteristics:**
    *   Easy to understand.
    *   Not affected by extreme items.
    *   **Disadvantage:** It is often ill-defined or uncertain (there can be more than one mode or no mode). It is rarely used in medical statistics.

*   **Example:**
    *   Data: 85, **75**, 81, 79, 71, 95, **75**, 77, **75**, 90.
    *   **Mode** = **75** (Occurs most frequently).

**Clinical Relevance:**
*   **Mean:** Used for parameters like height, weight, and blood pressure in normal populations.
*   **Median:** Used for [[Survival Time]] in cancer studies or incubation periods, which are often skewed.
*   **Mode:** Used to describe the most common symptom or the peak of an epidemic curve.

---

### Comparison of Measures

| Feature | Mean | Median | Mode |
| :--- | :--- | :--- | :--- |
| **Definition** | Mathematical Average | Positional Average (Middle) | Most Frequent |
| **Calculation** | $\sum X / n$ | Sort data $\rightarrow$ Find middle | Count frequencies |
| **Uses all data?** | Yes | No (only position) | No |
| **Effect of Outliers** | Highly Affected | **Not Affected** | Not Affected |
| **Best for** | Normal Distribution | Skewed/Dispersed Data | Qualitative data |

***

### Why Median is a Better Measure in Widely Dispersed Data

In a data set that is **widely dispersed** or **skewed** (contains extreme values or outliers), the **Median** is considered the most appropriate measure of central tendency compared to the Mean.

**Reasoning:**
1.  **Resistance to Outliers:** The Arithmetic Mean is sensitive to every value in the dataset. A single extremely high or low value can pull the mean toward it, resulting in a value that may not represent the "center" or "typical" value of the majority.
2.  **Positional Stability:** The Median depends only on the rank order of observations. An extreme value at the end of the distribution does not change the position of the middle value.
3.  **Representative Nature:** In skewed data (e.g., income, incubation periods), the mean gives a distorted picture, whereas the median remains nearer to the truth.

**Illustrative Example (Income):**
Imagine the daily income (in Rupees) of 7 people:
Data: 5, 5, 5, 7, 10, 20, **102**

*   **Calculating the Mean:**
    *   Sum = 154
    *   Mean = 154 / 7 = **22**
    *   *Interpretation:* The mean (22) suggests the average income is high, but 6 out of 7 people earn significantly less than 22. The outlier (102) has distorted the mean.

*   **Calculating the Median:**
    *   Arranged data: 5, 5, 5, **7**, 10, 20, 102
    *   **Median** = **7**
    *   *Interpretation:* The median (7) is much closer to what the majority of the group actually earns.

**Conclusion:** In this example, the Median (7) is a far better representative of the central tendency than the Mean (22). This principle applies to medical data like **hospital stay duration** (where one patient staying 100 days skews the mean) or **incubation periods**.

> [!warning] Diagram Alert
> create a frequency distribution curve showing a positive skew where Mode < Median < Mean to visually demonstrate how Mean is pulled to the right by outliers

---
**Mnemonic for Central Tendency:**
**The 3 M's**
*   **M**ean = **M**athematical Average (Add & Divide)
*   **M**edian = **M**iddle Value
*   **M**ode = **M**ost Popular

---

---
**Previous:** [[Feasibility of record linkage as a source of Health information]]  **Next:** [[What is sampling What are the different types of sampling Describe them briefly with their advantage]]