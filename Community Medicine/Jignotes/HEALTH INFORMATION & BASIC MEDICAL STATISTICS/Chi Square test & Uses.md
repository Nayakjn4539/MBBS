---
status: pending
tags: [chi_square_test, biostatistics, medical_statistics, hypothesis_testing, epidemiology, data_analysis, null_hypothesis]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 370
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Chi Square test & Uses

### **Chi-Square Test ($\chi^2$ Test)**

The [[Chi-Square Test]] is a statistical method used to determine if there is a significant difference between the expected frequencies and the observed frequencies in one or more categories. It was developed by **Karl Pearson**.

Unlike the t-test or Z-test, this is a **non-parametric test**, meaning it makes no assumptions about the population distribution (e.g., it does not require a normal distribution).

---

### **Key Characteristics**
1.  **Nature of Data:** It is used for **qualitative (discrete)** data expressed as frequencies, counts, or proportions (e.g., Male/Female, Cured/Not Cured, Vaccinated/Not Vaccinated).
2.  **Comparison:** It compares **Observed (O)** results with **Expected (E)** results.
3.  **Null Hypothesis ($H_0$):** The test always starts with the assumption that there is **no difference** or **no association** between the groups.

---

### **Uses of Chi-Square Test**

The Chi-Square test has three primary applications in medical statistics:

| **Use** | **Description** | **Example** |
| :--- | :--- | :--- |
| **1. Test of Proportions** | Used as an alternate to the Z-test to compare differences between two or more proportions. It can compare more than 2 groups. | Comparing the cure rates of Drug A vs. Drug B vs. Placebo. |
| **2. Test of Association** | **Most important application.** It measures the probability of association between two discrete attributes. | Is there an association between **Smoking** and **Lung Cancer**?. |
| **3. Test of Goodness of Fit** | Determines if the observed frequency distribution fits a theoretical or expected distribution. | Do the blood groups in a sample follow the expected genetic distribution (Mendelian ratio)?. |

---

### **Essential Requirements (Prerequisites)**
For the test to be valid, the following criteria must be met:
1.  **Random Sampling:** The sample must be selected randomly from the population.
2.  **Qualitative Data:** The data must be in the form of frequencies or counts, not measurements (like height/weight).
3.  **Sample Size:** The sample size should be sufficiently large.
4.  **Cell Frequency:** The **Expected frequency** in any cell of the contingency table should **not be less than 5**.
    *   *Correction:* If the expected frequency is < 5, **Fisher’s Exact Test** is used instead, or categories are pooled.

---

### **The Formula**

The Chi-Square statistic is calculated as:

$$ \chi^2 = \sum \frac{(O - E)^2}{E} $$

*   **O** = Observed Frequency
*   **E** = Expected Frequency

#### **Calculation of Expected Frequency (E)**
In a contingency table, the expected value for any cell is calculated as:
$$ E = \frac{\text{Row Total} \times \text{Column Total}}{\text{Grand Total}} $$

---

### **Steps to Perform the Test**

1.  **Set Null Hypothesis ($H_0$):** Assume there is no difference between the groups (e.g., "Vaccine A is not superior to Vaccine B").
2.  **Construct Contingency Table:** Arrange observed data in a table ($2 \times 2$ or larger).
    > [!warning] Diagram Alert
> 2x2 Contingency Table showing rows (Exposure) and columns (Disease/Outcome) with cells a, b, c, d
3.  **Calculate Expected Values:** Apply the formula for $E$ for each cell.
4.  **Apply $\chi^2$ Formula:** Calculate the value.
5.  **Determine Degrees of Freedom ($df$):**
    *   For a contingency table: $$ df = (c - 1)(r - 1) $$
    *   Where $c$ = number of columns and $r$ = number of rows.
6.  **Interpretation:** Compare the calculated value with the table value at a specific probability level (usually $P=0.05$).
    *   If **Calculated Value > Table Value**, $P < 0.05$: Reject Null Hypothesis (Result is **Significant**).
    *   If **Calculated Value < Table Value**, $P > 0.05$: Accept Null Hypothesis (Result is due to **Chance**).

---

### **Yates' Correction (Continuity Correction)**
In a **$2 \times 2$ table**, if the expected frequency in any cell is small (traditionally **< 5**), the standard Chi-square formula gives a biased result. To correct this, **[[Yates' Correction]]** is applied.

**Formula with Yates' Correction:**
$$ \chi^2 = \sum \frac{(|O - E| - 0.5)^2}{E} $$
(Subtract 0.5 from the absolute difference between Observed and Expected values before squaring).

---

### **Clinical Relevance**
*   **Vaccine Trials:** Determining if the incidence of disease is significantly lower in the vaccinated group compared to the unvaccinated group.
*   **Epidemiology:** Investigating outbreaks to see if eating a specific food item (Exposure) is associated with getting food poisoning (Outcome).
*   **Genetics:** Checking if the inheritance of traits follows standard genetic laws (Goodness of fit).

---

### **Mnemonic for Uses**
To remember the uses of Chi-Square: **"GAP"**
*   **G** - **G**oodness of Fit
*   **A** - **A**ssociation (Test of association between two variables)
*   **P** - **P**roportions (Test of difference between proportions)

---
**Previous:** [[What is sampling Random sampling methods with suitable examples]]  **Next:** [[Sources & uses of statistical health information]]