---
status: pending
tags: [chi_square_test, biostatistics, hypothesis_testing, medical_research, data_analysis]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 390
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Describe the steps of chi square test with example

### [[Chi-Square Test]] ($\chi^2$)

The [[Chi-Square Test]] is a **non-parametric test** of significance used to compare proportions or to test the association between two categorical (qualitative) variables. It determines whether the **Observed frequencies (O)** in a sample differ significantly from the **Expected frequencies (E)**.

### Prerequisites for Application
1.  **Random Sample:** The data must be collected randomly.
2.  **Qualitative Data:** The data must be in frequencies/counts (not percentages or measurements like height).
3.  **Expected Frequency:** The lowest expected frequency in any cell of the contingency table should **not be less than 5**.

---

### Steps of Chi-Square Test

**1. Formulation of Hypothesis**
*   **Null Hypothesis ($H_0$):** Assume there is **no difference** between the groups or no association between the variables (e.g., "Vaccine A is equally effective as Vaccine B").
*   **Alternate Hypothesis ($H_1$):** There is a significant difference or association.

**2. Construction of Contingency Table**
*   Create a table with the **Observed Frequencies ($O$)**.
*   This is typically a $2 \times 2$ table (Four-fold table) or larger ($r \times c$).

**3. Calculation of Expected Frequencies ($E$)**
*   Calculate the expected number for each cell based on the row and column totals using the formula:
    $$E = \frac{\text{Row Total} \times \text{Column Total}}{\text{Grand Total}}$$

**4. Application of Chi-Square Formula**
*   Calculate the difference between Observed and Expected values $(O - E)$.
*   Square the difference $(O - E)^2$ to remove negative signs.
*   Divide by the Expected value for that cell.
*   Sum these values for all cells.
    $$\chi^2 = \sum \frac{(O - E)^2}{E}$$

**5. Determine Degrees of Freedom ($df$)**
*   The degrees of freedom depend on the number of columns ($c$) and rows ($r$) in the table.
    $$df = (c - 1)(r - 1)$$
    *(For a standard $2 \times 2$ table, $df = 1$)*.

**6. Interpretation (Probability Table)**
*   Compare the calculated $\chi^2$ value with the critical value in the standard [[Probability Table]] (Appendix IV) at the calculated degrees of freedom and desired probability level (usually $P = 0.05$).
*   **If Calculated Value > Table Value:** Reject $H_0$ (Difference is Significant).
*   **If Calculated Value < Table Value:** Accept $H_0$ (Difference is due to chance).

---

### Illustrative Example: Vaccine Efficacy Trial

**Scenario:** A trial was conducted to compare the efficacy of two vaccines (Vaccine A and Vaccine B) against Whooping Cough. We want to know if Vaccine A is significantly better than Vaccine B.

**Step 1: Null Hypothesis ($H_0$)**
There is no difference in the attack rates between Vaccine A and Vaccine B.

**Step 2: Contingency Table (Observed Values - O)**

| Group | Attacked | Not Attacked | Total |
| :--- | :---: | :---: | :---: |
| **Vaccine A** | 22 | 68 | 90 |
| **Vaccine B** | 14 | 72 | 86 |
| **Total** | **36** | **140** | **176** |

**Step 3: Calculate Expected Frequencies ($E$)**
*   **E for Vaccine A (Attacked):** $\frac{36 \text{ (Col Total)} \times 90 \text{ (Row Total)}}{176 \text{ (Grand Total)}} = 18.4$
*   **E for Vaccine A (Not Attacked):** $\frac{140 \times 90}{176} = 71.6$
*   **E for Vaccine B (Attacked):** $\frac{36 \times 86}{176} = 17.6$
*   **E for Vaccine B (Not Attacked):** $\frac{140 \times 86}{176} = 68.4$

**Step 4: Apply Formula**

| Cell | $O$ | $E$ | $O - E$ | $(O - E)^2$ | $\frac{(O - E)^2}{E}$ |
| :--- | :---: | :---: | :---: | :---: | :---: |
| Vacc A (Attacked) | 22 | 18.4 | +3.6 | 12.96 | **0.70** |
| Vacc A (Not Attacked) | 68 | 71.6 | -3.6 | 12.96 | **0.18** |
| Vacc B (Attacked) | 14 | 17.6 | -3.6 | 12.96 | **0.73** |
| Vacc B (Not Attacked) | 72 | 68.4 | +3.6 | 12.96 | **0.19** |

**$\sum \chi^2 = 0.70 + 0.18 + 0.73 + 0.19 = 1.80$**

**Step 5: Degrees of Freedom**
$df = (2 - 1) \times (2 - 1) = 1$

**Step 6: Interpretation**
*   Refer to the Chi-square table for $df = 1$ at $P = 0.05$. The critical table value is **3.84**.
*   **Result:** Our calculated value (**1.80**) is **less than** the table value (**3.84**).
*   **Conclusion:** We accept the [[Null Hypothesis]]. The difference between the two vaccines is **not statistically significant** and is likely due to chance.

> [!warning] Diagram Alert
> flow chart showing the decision tree for Chi-square: Calculate -> Compare with Table -> Significant/Not Significant

---

### Mnemonic for Steps
**"O**ld **E**lephants **S**quare **D**ance"
*   **O**bserved (Make table)
*   **E**xpected (Calculate expected)
*   **S**quare the difference $(O - E)^2$
*   **D**ivide by expected (and Sum)

### Clinical Relevance
*   **Drug Trials:** Comparing the cure rate of a new drug versus a placebo.
*   **Genetics:** Determining if the inheritance of traits follows Mendelian ratios (Goodness of Fit).
*   **Epidemiology:** Checking if there is an association between a risk factor (e.g., smoking) and a disease (e.g., cancer).

---
**Previous:** [[Criteria for selection of sampling and methods & registration systems in India]]  **Next:** [[Correlation and regression]]