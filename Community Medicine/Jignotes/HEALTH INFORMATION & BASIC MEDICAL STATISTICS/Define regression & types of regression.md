---
status: pending
tags: [Regression, Biostatistics, Regression_Coefficient, Logistic_Regression, ANOVA, Linear_Regression]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 402
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Define regression & types of regression

# Regression

### 1. Definition
**[[Regression]]** is a statistical method used to estimate or predict the value of one variable (character) from the knowledge of another variable when the two are linearly correlated. It provides the **structure of the relationship** between two quantitative variables.

*   **Literal Meaning:** "Regression" means change in the measurements of a variable character, on the positive or negative side, beyond the mean.
*   **Function:** It allows the calculation of the unknown value of a **[[Dependent Variable]]** ($Y$) when the value of the **[[Independent Variable]]** ($X$) is known.

> [!warning] Diagram Alert
> A scatter diagram showing a Regression Line (Line of Best Fit) passing through data points with X-axis as Independent Variable and Y-axis as Dependent Variable

### 2. Key Components
*   **Independent Variable ($X$):** The variable which is known or controlled.
*   **Dependent Variable ($Y$):** The variable to be estimated or predicted.
*   **[[Regression Coefficient]] ($b$):** It is a measure of the change in the dependent variable ($Y$) corresponding to one unit change in the independent variable ($X$).
    *   It indicates the **slope** of the regression line.
*   **Intercept ($a$):** The value of $Y$ when $X$ is zero.

**The Basic Regression Equation:**
$$Y_c = a + bX$$
*   $Y_c$ = Calculated/Expected value of $Y$
*   $a$ = Constant (Intercept)
*   $b$ = Regression coefficient (Slope)
*   $X$ = Observed value of independent variable

### 3. Types of Regression
Regression analysis is classified based on the number of independent variables and the nature of the relationship (linear vs. curve).

#### A. Based on Number of Variables and Linearity

| Type of Regression | Description | Equation Structure |
| :--- | :--- | :--- |
| **[[Simple Linear Regression]]** | Involves **one** dependent variable and **one** independent variable. | $y = a + b(x)$ |
| **[[Multiple Linear Regression]]** | Involves **one** dependent variable and **more than one** independent variables. | $y = a + b(x_1) + c(x_2) + d(x_3)$ |
| **Simple Curvilinear Regression** | One dependent and one independent variable, but with some **power** of the independent variable (non-linear). | $y = a + b(x)^6$ |
| **Multiple Curvilinear Regression**| One dependent and multiple independent variables, with powers. | $y = a + b(x_1)^2 + c(x_2)^4...$ |

#### B. Based on the Nature of Variables (Qualitative/Quantitative)

| Type of Regression | Dependent Variable (Target) | Independent Variable (Predictor) |
| :--- | :--- | :--- |
| **[[Logistic Regression]]** | **Qualitative/ Dichotomous** (e.g., Disease Present/Absent) | Qualitative / Quantitative / Mixed |
| **[[ANOVA]]** (Analysis of Variance) | Quantitative | Qualitative |
| **[[ANCOVA]]** (Analysis of Covariance)| Quantitative | Qualitative + Quantitative |
| **Multivariate Logistic Regression**| Set of Qualitative variables | Qualitative / Quantitative |

### 4. Clinical Relevance
*   **Prediction:** Estimating a patient's **[[Systolic Blood Pressure]]** (Dependent) based on their **Age** (Independent).
*   **Risk Estimation:** Predicting the risk of **[[Coronary Heart Disease]]** based on serum cholesterol levels and smoking status (Multiple Regression).
*   **Growth Monitoring:** Predicting the expected height or weight of a child based on age.

---
### Mnemonics
**To remember the Linear Regression Equation ($Y = a + bX$):**
"**Y**ou **A**re **b**ecoming **X**-traordinary"
*   **Y** = Dependent
*   **a** = Constant
*   **b** = Coefficient
*   **X** = Independent

**To remember the types of Regression variables:**
"**I**ndependent is **I**n **C**ontrol, **D**ependent **D**epends on it."

---
**Previous:** [[Describe stratified sampling and its purpose]]  **Next:** [[Time within which births and deaths have to be registered as per the Birth and Death Registration Ac]]