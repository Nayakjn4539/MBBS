---
status: pending
tags: [Correlation, Regression, Biostatistics, Scatter_Diagram, Pearson_Coefficient, Regression_Equation, Health_Statistics]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 391
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Correlation and regression

### **Correlation**

**Definition**
Correlation denotes the relationship or association between two **quantitative** (continuous) variables. It measures the degree/strength and direction of the linear relationship between these variables.
*   It answers the question: *"Are these two variables related, and how strongly?"*
*   It does **not** necessarily prove causation (e.g., height and weight are correlated, but height doesn't *cause* weight).

**Visualization**
The relationship is best depicted visually using a [[Scatter Diagram]] (Dot diagram).
*   **X-axis:** Independent variable (e.g., Height).
*   **Y-axis:** Dependent variable (e.g., Weight).
*   > [!warning] Diagram Alert
> Scatter diagrams showing Perfect Positive (r=+1), Perfect Negative (r=-1), and No Correlation (r=0)

**Correlation Coefficient (r)**
The extent or degree of relationship is measured by the **Correlation Coefficient**, denoted by the symbol **'r'** (Pearson’s coefficient).

*   **Range:** The value of *r* always lies between **–1 and +1**.
*   **Interpretation of 'r':**

| Value of 'r' | Interpretation | Example |
| :--- | :--- | :--- |
| **+1** | **Perfect Positive Correlation** | As X increases, Y increases proportionately (e.g., Height and Weight in growing children). |
| **–1** | **Perfect Negative Correlation** | As X increases, Y decreases proportionately (e.g., Pressure and Volume of gas). |
| **0** | **No Correlation** | Variables are independent (e.g., Height and Pulse rate). |
| **0 < r < 1** | **Moderate Positive** | Variables increase together but not perfectly (e.g., Age and Height). |
| **–1 < r < 0** | **Moderate Negative** | One increases, other decreases (e.g., Age and Vital Capacity in elderly). |

**Types of Correlation Coefficients**
1.  **Pearson’s Correlation Coefficient (r):** Used for **ungrouped series** where variables follow a [[Normal Distribution]].
2.  **Spearman’s Rank Correlation Coefficient (rho/ρ):** Used for **grouped series** or when variables are **not** normally distributed (non-parametric).

**Coefficient of Determination ($r^2$)**
*   It is the square of the correlation coefficient ($r^2$).
*   It indicates the **percentage of variation** in one variable that is explained by the other variable.
*   *Example:* If $r = 0.9$, then $r^2 = 0.81$. This means 81% of the variation in blood pressure can be explained by the variation in serum cholesterol.

---

### **Regression**

**Definition**
Regression is the statistical method used to **predict** or estimate the value of one variable (Dependent variable, $Y$) corresponding to a given value of another variable (Independent variable, $X$).
*   It describes the **change** in measurements of a variable on the positive or negative side beyond the mean.
*   While correlation describes the *degree* of relationship, regression describes the *nature/structure* of the relationship.

**Regression Equation**
The relationship is expressed as a straight-line equation (Simple Linear Regression):

> **$$Y = a + bX$$**

*   **Y:** Dependent variable (the outcome we want to predict).
*   **X:** Independent variable (the predictor).
*   **a:** Constant (Interception point on Y-axis).
*   **b:** [[Regression Coefficient]] (Slope of the line).

**Regression Coefficient (b)**
*   It measures the change in the dependent variable ($Y$) for **one unit change** in the independent variable ($X$).
*   *Example:* If the regression coefficient of weight ($Y$) on height ($X$) is 0.5 kg/cm, it means for every 1 cm increase in height, weight increases by 0.5 kg.

**Types of Regression**
1.  **Simple Linear:** One dependent and one independent variable ($y = a + bx$).
2.  **Multiple Linear:** One dependent variable and **more than one** independent variable ($y = a + b_1x_1 + b_2x_2...$).
3.  **Logistic Regression:** Used when the outcome (dependent variable) is **qualitative/dichotomous** (e.g., Disease Present/Absent).

**Standard Error of Estimate**
Used to measure the variability or scatter of the observed values around the regression line.

---

### **Difference between Correlation and Regression**

| Feature | Correlation | Regression |
| :--- | :--- | :--- |
| **Purpose** | Measures **degree/strength** of association. | **Predicts** the value of one variable based on another. |
| **Variables** | Both X and Y are random variables; no distinction between dependent/independent. | Distinguishes between **Dependent (Y)** and **Independent (X)** variables. |
| **Coefficient** | Correlation Coefficient (**r**). | Regression Coefficient (**b**). |
| **Range** | **–1 to +1**. | Can take **any value**. |
| **Causation** | Does **not** imply cause and effect. | Indicates a functional relationship (cause-effect structure). |

---

### **Mnemonic**

**"C-R-P"**
*   **C**orrelation = **R**elationship (How strong?)
*   **R**egression = **P**rediction (What will be the value?)

**"The r-Line"**
*   **+1:** Best Friends (Go up together)
*   **-1:** Enemies (One up, one down)
*   **0:** Strangers (Don't care about each other)

---

### **Clinical Relevance**
1.  **Pediatrics:** Using **Regression**, pediatricians can predict the expected weight of a child based on their height or age to assess for malnutrition.
2.  **Pharmacology:** **Dose-Response** relationships are analyzed using regression to predict the therapeutic effect (Y) based on the drug dosage (X).
3.  **Epidemiology:** **Correlation** is used to study ecological relationships, such as the link between salt intake and hypertension prevalence in a community.
4.  **Prediction:** Calculating the risk of cardiovascular events ($Y$) based on multiple risk factors like age, cholesterol, and BP ($X_1, X_2, X_3$) using **Multiple Logistic Regression**.

---
**Previous:** [[Describe the steps of chi square test with example]]  **Next:** [[Define census]]