---
status: pending
tags: [Biostatistics, CentralTendency, Mean, Median, Mode, NormalDistribution, Skewness]
subject: Community medicine - kpark
topic: Health Information And Basic Medical Statistics
up: 172
---

# [[Health Information And Basic Medical Statistics]] > Measures of Central Tendency

### **Measures of Central Tendency**

In [[Biostatistics]], a measure of central tendency is a single value that attempts to describe a set of data by identifying the central position within that set of data. It summarizes the data into a single figure that is representative of the whole distribution.

The three most common measures are the **Mean**, **Median**, and **Mode**.

---

### **1. The Arithmetic Mean (Average)**
This is the most widely used measure in statistical analysis. It is the "mathematical average" of the data.

*   **Definition:** The sum of all observations divided by the total number of observations.
*   **Formula:** 
    *   $\text{Mean} (\bar{x}) = \frac{\sum x}{n}$
    *   Where $\sum x$ = Sum of all values, and $n$ = Number of observations.

#### **Types of Mean**
1.  **Simple Arithmetic Mean:** Used for ungrouped data (individual observations).
2.  **Weighted Mean:** Used for grouped data (frequency tables). It takes into account the "weight" or frequency of each group.
    *   Formula: $\frac{\sum fx}{n}$ (where $f$ = frequency, $x$ = mid-point of group).

#### **Merits and Demerits**
| **Merits** | **Demerits** |
| :--- | :--- |
| Easy to calculate and understand. | **Highly sensitive to outliers:** Unduly influenced by extreme values (e.g., one billionaire in a poor village skews the mean income). |
| Utilizes **all** the observations in the data. | Can produce a value that does not exist in reality (e.g., 4.76 children per woman). |
| Useful for further statistical analysis (e.g., [[Standard Deviation]], Tests of Significance). | Not suitable for skewed distributions. |

---

### **2. The Median**
The median is a **positional average**. It represents the middle value of a series when the data is arranged in an ordered sequence.

*   **Definition:** The value that divides the distribution into two equal halves (50% of observations lie above it, and 50% lie below it).
*   **Calculation Steps:**
    1.  **Arrange** data in ascending or descending order.
    2.  **If 'n' is Odd:** Median is the $\frac{(n+1)}{2}^{th}$ observation.
    3.  **If 'n' is Even:** Median is the average of the $\frac{n}{2}^{th}$ and $(\frac{n}{2} + 1)^{th}$ observations.

#### **Merits and Demerits**
| **Merits** | **Demerits** |
| :--- | :--- |
| **Robust against outliers:** Not affected by extreme values. | Does not utilize all observations (ignores the magnitude of values at the extremes). |
| Better indicator for skewed data (e.g., [[Incubation Period]], Duration of hospital stay, Income). | Not suitable for further algebraic/statistical treatment. |
| Can be located graphically using an **Ogive** (Cumulative frequency diagram). | Requiring arrangement of data can be tedious for large datasets. |

---

### **3. The Mode**
*   **Definition:** The most frequently occurring value in a dataset. It is the most "fashionable" or common value.
*   **Calculation:** Simply identify the value with the highest frequency.
*   **Bimodal Distribution:** If a series has two distinct peaks (two values with high frequency), it is called bimodal. This often suggests the sample is heterogeneous (e.g., mixing two different populations).

#### **Merits and Demerits**
| **Merits** | **Demerits** |
| :--- | :--- |
| Easy to understand; not affected by extremes. | Often ill-defined or uncertain (multiple modes may exist). |
| Useful for nominal/qualitative data. | Rarely used in medical statistics. |

---

### **Relationship Between Mean, Median, and Mode**

The relationship depends on the **distribution** of the data (See diagram alert below).

#### **1. Normal Distribution ([[Gaussian Distribution]])**
*   The curve is bilaterally symmetrical and bell-shaped.
*   **Mean = Median = Mode** (They all coincide at the center).

#### **2. Skewed Distribution (Asymmetrical)**
When data is not symmetrical, the measures pull apart.
*   **Positively Skewed (Right Skew):** The tail is on the right (higher values).
    *   **Mean > Median > Mode**.
    *   *Example:* Income distribution.
*   **Negatively Skewed (Left Skew):** The tail is on the left (lower values).
    *   **Mean < Median < Mode**.

**Empirical Formula for Skewed Distributions:**
$$Mode = 3(Median) - 2(Mean)$$.

> > [!warning] Diagram Alert
> Draw three curves. 1. A Bell-shaped curve where a single vertical line represents Mean, Median, and Mode. 2. A Right-skewed curve (tail to right) showing Mode at the peak, Median in the middle, and Mean pulled toward the tail. 3. A Left-skewed curve (tail to left) showing Mean pulled left, Median middle, Mode at peak.

---

### **Clinical Relevance: Which One to Choose?**

| **Scenario** | **Preferred Measure** | **Reason** |
| :--- | :--- | :--- |
| **Normal Data** (e.g., Height, BP of large population) | **Mean** | Uses all data; basis for SD and SE. |
| **Skewed Data** (e.g., Survival time, Incubation period) | **Median** | Extreme values (outliers) do not distort the result. |
| **Qualitative Data** (e.g., Most common blood group) | **Mode** | Identifies the most frequent category. |
| **Rates/Ratios** (e.g., Geometric progression) | **Geometric Mean** | Useful for titres or exponential growth. |

---

### **Mnemonics for Recall**

*   **The "Mean" One:** The Mean is **mean** (nasty) because it lets the outliers (the weirdos) mess up the average!
*   **The "Median" Strip:** Just like the concrete strip in the **middle** of the highway, the Median is always in the middle.
*   **Mode is "Most":** **MO**de = **MO**st frequent.

---
**Previous:** [[Presentation of Data]]  **Next:** [[Measures of Dispersion]]