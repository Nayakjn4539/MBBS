---
status: pending
tags: [screening, epidemiology, biostatistics, validity, sensitivity, specificity, public_health]
subject: Community medicine - kpark
topic: Screening For Disease
up: 34
---

# [[Screening For Disease]] > Sensitivity and Specificity

### Sensitivity and Specificity

[[Sensitivity]] and [[Specificity]] are inherent properties of a screening test that determine its **Validity** (Accuracy). They measure the ability of a test to distinguish between those who have the disease and those who do not.

#### 1. The 2x2 Contingency Table
To calculate these values, we use a standard 2x2 table comparing the Screening Test results against a **Gold Standard** (Diagnostic Test).

> [!warning] Diagram Alert
> 2x2 table showing Disease Status (Diseased/Not Diseased) in columns and Test Result (Positive/Negative) in rows, labeling cells a (True Positive), b (False Positive), c (False Negative), and d (True Negative)

| **Test Result** | **Disease Present** | **Disease Absent** | **Total** |
| :--- | :---: | :---: | :---: |
| **Positive** | **a** (True Positive) | **b** (False Positive) | $a + b$ |
| **Negative** | **c** (False Negative) | **d** (True Negative) | $c + d$ |
| **Total** | $a + c$ (Total Diseased) | $b + d$ (Total Healthy) | $N$ |

---

#### 2. Sensitivity (True Positive Rate)
**Definition:** The ability of a test to identify correctly all those who **have** the disease. It is the probability of a positive test in people with the disease.

*   **Formula:**
    $$Sensitivity = \frac{\text{True Positives (a)}}{\text{Total Diseased (a + c)}} \times 100$$

*   **Interpretation:**
    *   A 90% sensitivity means the test picks up 90% of diseased people.
    *   The remaining 10% are **False Negatives** (Missed cases).
    *   High sensitivity = Low False Negative Rate.

*   **Clinical Relevance:**
    *   Used for **Screening**.
    *   Essential for diseases where early detection is critical (e.g., [[Phenylketonuria]], [[Hypothyroidism]]).
    *   Required for diseases that are fatal if missed (e.g., [[HIV]]).
    *   **Statistical Link:** Power of a test = Sensitivity ($1 - \beta$).

> **Mnemonic:** **SN-OUT**
> **S**e**N**sitive test, when **N**egative, rules **OUT** the disease. (Because false negatives are rare).

---

#### 3. Specificity (True Negative Rate)
**Definition:** The ability of a test to identify correctly all those who **do not** have the disease. It is the probability of a negative test in people without the disease.

*   **Formula:**
    $$Specificity = \frac{\text{True Negatives (d)}}{\text{Total Healthy (b + d)}} \times 100$$

*   **Interpretation:**
    *   A 90% specificity means the test correctly identifies 90% of healthy people as negative.
    *   The remaining 10% are **False Positives** (Healthy people wrongly labeled as sick).
    *   High specificity = Low False Positive Rate.

*   **Clinical Relevance:**
    *   Used for **Confirmation/Diagnosis**.
    *   Essential when the treatment is toxic, invasive, or expensive (e.g., [[Chemotherapy]] for Cancer).
    *   High specificity avoids labeling healthy people as diseased (prevents stigmatization).
    *   **Statistical Link:** Type I Error ($\alpha$) = $1 - \text{Specificity}$.

> **Mnemonic:** **SP-IN**
> **SP**ecific test, when **P**ositive, rules **IN** the disease. (Because false positives are rare).

---

#### 4. Relationship Between Sensitivity and Specificity
They are **inversely proportional**. You cannot increase one without decreasing the other (unless you change the test entirely).

*   **Cut-off Points:**
    *   **Lowering the cut-off** (making criteria "looser"): Increases Sensitivity (catches more cases) but decreases Specificity (more false positives).
    *   **Raising the cut-off** (making criteria "stricter"): Increases Specificity (fewer false positives) but decreases Sensitivity (misses more cases).

> [!warning] Diagram Alert
> Two overlapping bell curves representing 'Healthy' and 'Diseased' populations with a vertical line moving left or right to show changing cut-off points

*   **[[ROC Curve]] (Receiver Operating Characteristic):**
    *   A graphical plot of **Sensitivity (y-axis)** vs **1 – Specificity (x-axis)**.
    *   Used to determine the optimal cut-off point.
    *   The larger the area under the curve (AUC), the better the test.

---

#### 5. Combination of Tests
Sometimes multiple tests are used to improve accuracy.

| Mode | Procedure | Effect on Sensitivity | Effect on Specificity | Example |
| :--- | :--- | :--- | :--- | :--- |
| **Series** | Test A is done; if positive, Test B is done. | **Decreases** | **Increases** | HIV Testing: [[ELISA]] (Screening) followed by [[Western Blot]] (Confirmatory). |
| **Parallel**| Test A and Test B are done simultaneously. | **Increases** | **Decreases** | Rapid assessment in emergency triage. |

---

#### 6. Summary Comparison Table

| Feature | Sensitivity | Specificity |
| :--- | :--- | :--- |
| **Focus** | Diseased Population | Healthy Population |
| **Identifies** | True Positives | True Negatives |
| **Formula** | $TP / (TP + FN)$ | $TN / (TN + FP)$ |
| **Errors** | Relates to **False Negatives** | Relates to **False Positives** |
| **Utility** | Rule **OUT** disease (Screening) | Rule **IN** disease (Confirmation) |
| **Statistical** | Power ($1 - \beta$) | $1 - \alpha$ (Type I error) |,,,,,,

---
**Previous:** [[Concept and Criteria for Screening]]  **Next:** [[Predictive Values]]