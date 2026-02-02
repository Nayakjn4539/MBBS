---
status: pending
tags: [Biostatistics, MeasuresOfCentralTendency, MeanMedianMode, NormalDistribution, PublicHealthStatistics]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 378
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Statistical averages

# STATISTICAL AVERAGES (MEASURES OF CENTRAL TENDENCY)

The term **"Average"** implies a value in the distribution around which the other values are distributed. It provides a mental picture of the central value of a set of data. In [[Biostatistics]], these are known as **Measures of Central Tendency**.

The three commonly used statistical averages are:
1.  **Mean** (Arithmetic Mean)
2.  **Median**
3.  **Mode**

---

### 1. The Mean (Arithmetic Mean)
This is the most widely used measure in statistical calculations. It is the "mathematical average."

*   **Definition:** It is obtained by summing up all the observations and dividing the total by the number of observations.
*   **Formula:**
    $$ \bar{X} = \frac{\sum X}{n} $$
    *(Where $\bar{X}$ = Mean, $\sum X$ = Sum of all values, $n$ = Number of observations)*

*   **Key Characteristics:**
    *   It utilizes **all** the observations in the data set.
    *   It is the most suitable measure for further statistical analysis (e.g., calculating [[Standard Deviation]]).
*   **Disadvantage:** It is unduly influenced by **extreme values (outliers)**. A single very high or very low value can distort the mean, making it less representative.
    *   *Example:* If the income of 7 people is 5, 5, 5, 7, 10, 20, and **102**, the mean is 22. This is much higher than the majority, misleading the observer.

### 2. The Median
The median is a **positional average**. It represents the middle value of a distribution.

*   **Definition:** When data is arranged in an **ascending or descending order**, the middle observation is the median.
*   **Calculation:**
    *   If $n$ is **Odd**: The middle value is the median [$(n+1)/2$ th item].
    *   If $n$ is **Even**: The average of the **two middle values** is the median.
*   **Key Characteristics:**
    *   It divides the distribution into two equal halves (50% values above, 50% below).
    *   It is **NOT** affected by extreme values (outliers).
    *   It is the **best measure** for skewed data (e.g., Income, incubation periods, duration of hospital stay).

### 3. The Mode
The mode is the **most frequent** value.

*   **Definition:** The value that occurs most frequently in a series of observations.
*   **Key Characteristics:**
    *   It is the "fashionable" value (Mode = French for Fashion).
    *   A distribution can have one mode (Unimodal), two modes (Bimodal), or multiple modes.
    *   It is rarely used in medical statistics because it is often ill-defined and uncertain.
*   **Relationship:** In asymmetrical (skewed) distributions, the relationship between the three is:
    $$ \text{Mode} = 3(\text{Median}) - 2(\text{Mean}) $$,

---

### Comparison of Statistical Averages

| Feature | Mean | Median | Mode |
| :--- | :--- | :--- | :--- |
| **Type** | Mathematical Average | Positional Average | Frequency Average |
| **Calculation** | $\sum X / n$ | Middle value (sorted) | Most frequent value |
| **Effect of Outliers** | **Highly Affected** | **Not Affected** | Not Affected |
| **Best Used For** | Normal Distribution (Symmetrical) | Skewed Distribution (Asymmetrical) | Nominal data / Quick estimate |
| **Uses All Data?** | **Yes** | No (only position) | No (only frequency) |
| **Example** | Height, Weight, BP | Incubation period, Survival time | Most common blood group |,,

---

### Distribution Patterns

The relationship between Mean, Median, and Mode determines the shape of the frequency distribution curve:

1.  **[[Normal Distribution]] (Gaussian):**
    *   **Mean = Median = Mode**
    *   They all coincide at the center of the bell-shaped curve.

2.  **Skewed Distribution (Asymmetrical):**
    *   **Right (Positive) Skew:** Mean > Median > Mode (Tail is on the right).
    *   **Left (Negative) Skew:** Mean < Median < Mode (Tail is on the left).

> [!warning] Diagram Alert
> Draw a Normal Distribution curve showing Mean, Median, and Mode coinciding in the center. Next to it, draw a Positively Skewed curve (tail right) with Mean > Median > Mode, and a Negatively Skewed curve (tail left) with Mean < Median < Mode

---

### Clinical Relevance
*   **Mean:** Used for physiological parameters like **Blood Pressure**, Pulse rate, and Hemoglobin levels in a population.
*   **Median:** Preferred for **Health Expenses** (as few rich people skew the mean) or **Survival Time** in cancer (because a few long-term survivors would falsely inflate the mean survival time).
*   **Mode:** Useful for determining the peak of an **epidemic curve** (most common time of onset) or the most common admission diagnosis in a hospital.

---

### 💡 Mnemonic to Remember

*   **Mean**: **Mean** people take **everything** (uses all values, easily affected/manipulated by outliers).
*   **Median**: **Med**ian is the **Mid**dle of the road (divides data in half, ignores the crazy drivers on the edges/outliers).
*   **Mode**: **Mo**de is **Mo**st Popular (most frequent).

---
**Previous:** [[Histogram]]  **Next:** [[Measure of central tendency]]