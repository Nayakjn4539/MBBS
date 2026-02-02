---
status: pending
tags: [biostatistics, central_tendency, mean, median, mode, normal_distribution, skewed_distribution, data_analysis, public_health]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 379
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Measure of central tendency

# Measures of Central Tendency

A **[[Measure of Central Tendency]]** (or Statistical Average) provides a single value that describes the characteristic of an entire mass of data. It is a value around which other observations tend to cluster. It condenses a large set of data into a single representative figure.

The three most common measures are:
1.  **Mean** (Arithmetic Mean)
2.  **Median**
3.  **Mode**

---

### 1. [[Arithmetic Mean]] ($\bar{X}$)
This is the "mathematical average" and is the most widely used measure in medical statistics.

*   **Calculation:** It is obtained by summing up all the observations and dividing the total by the number of observations.
    *   Formula: $$\bar{X} = \frac{\sum X}{n}$$
    *   *(Where $\sum X$ = sum of all values, $n$ = number of observations)*

*   **Key Characteristics:**
    *   It utilizes **all** the observations in the data set.
    *   It is the center of gravity of the data.
    *   **Disadvantage:** It is unduly influenced by **[[extreme values]]** (outliers). A single very high or very low value can distort the mean significantly.

*   **Clinical Relevance:** Used for normally distributed biological variables like specific [[blood pressure]], height, weight, or hemoglobin levels.

### 2. [[Median]]
This is the "positional average." It is the **middle value** when the data is arranged in an ascending or descending order of magnitude.

*   **Calculation:**
    *   **Odd number of observations ($n$):** The value of the $(\frac{n+1}{2})^{th}$ item.
    *   **Even number of observations ($n$):** The average of the $(\frac{n}{2})^{th}$ and $(\frac{n}{2} + 1)^{th}$ items.

*   **Key Characteristics:**
    *   It divides the distribution into two equal halves (50% of observations lie above it, 50% below it).
    *   It is **NOT** affected by extreme values (outliers).
    *   It is a better indicator than the mean when data is skewed (asymmetrical).

*   **Clinical Relevance:**
    *   **[[Survival time]]** in cancer studies (because a few patients surviving a very long time would skew the mean).
    *   **Incubation period** of infectious diseases.
    *   Duration of hospital stay.

### 3. [[Mode]]
This is the "most fashionable" or most frequent value. It is the value that occurs **most frequently** in a distribution.

*   **Key Characteristics:**
    *   It is easy to understand.
    *   It is not affected by extreme values.
    *   **Disadvantage:** It is often ill-defined. A series can be **bimodal** (two peaks) or multimodal. It is rarely used in medical statistical analysis compared to mean and median.

*   **Clinical Relevance:**
    *   Used to identify the peak incidence in an **[[epidemic curve]]**.
    *   Commonest size of shoe or ready-made garments required for a population.

---

### Comparison of Measures

| Feature | [[Mean]] | [[Median]] | [[Mode]] |
| :--- | :--- | :--- | :--- |
| **Definition** | Mathematical Average | Positional Average (Middle) | Most Frequent Value |
| **Based on** | All observations | Position in ordered series | Frequency of occurrence |
| **Effect of Outliers** | **Highly affected** | **Not affected** | **Not affected** |
| **Use** | Normal (Gaussian) Data | Skewed Data (Asymmetrical) | Determining "Popular" value |
| **Uniqueness** | Always unique | Always unique | Can have >1 mode or no mode |

---

### Relationship Between Mean, Median, and Mode

The relationship depends on the distribution of data:

1.  **[[Normal Distribution]] (Gaussian Curve):**
    *   **Mean = Median = Mode**
    *   They all coincide at the center of the bell-shaped curve.

2.  **[[Skewed Distribution]] (Asymmetrical):**
    *   **Positive (Right) Skew:** Mean > Median > Mode (Tail is to the right).
    *   **Negative (Left) Skew:** Mean < Median < Mode (Tail is to the left).

> **Empirical Relationship Formula:**
> **[[Mode]] = 3 Median – 2 Mean**

> [!warning] Diagram Alert
> Draw a Normal Distribution curve showing Mean, Median, and Mode coinciding at the peak. Draw a Skewed curve showing Mean pulled toward the tail, Mode at the peak, and Median in between.

---

### 💡 Mnemonic
*   **Mean** is **Mean**: It's "mean" because it makes you do math (add and divide) and gets easily distracted by outliers (extremes).
*   **Med**ian is the **Med**ium strip: It stays right in the middle of the road, ignoring the crazy drivers (outliers) on the edges.
*   **Mo**de is **Mo**st: The value that appears the **Mo**st often.

---
**Previous:** [[Statistical averages]]  **Next:** [[Uses of standard deviation]]