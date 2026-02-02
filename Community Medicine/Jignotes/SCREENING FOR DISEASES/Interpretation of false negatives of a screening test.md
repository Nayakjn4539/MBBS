---
status: pending
tags: [False_Negative, Screening, Sensitivity, Type_II_Error, Community_Medicine, Epidemiology, Biostatistics]
subject: Community Medicine
topic: SCREENING FOR DISEASES
up: 49
---

# [[SCREENING FOR DISEASES]] > Interpretation of false negatives of a screening test

### Interpretation of False Negatives in a Screening Test

A **[[False Negative]]** result implies that patients who **actually have the disease** are told that they **do not have the disease**. This classification error is critical in clinical medicine and public health because it labels a diseased individual as "healthy."

#### 1. Statistical Definition and Calculation
In a standard 2x2 contingency table for screening:
*   **Notation:** Represented by the letter **'c'** (or **FN**),.
*   **Calculation:**
    $$Percentage\ of\ False\ Negatives = \frac{c}{a + c} \times 100$$
    *Where 'a' is True Positive and 'c' is False Negative.*,
*   **Relation to Sensitivity:** The [[Sensitivity]] of a test is its ability to identify true positives. Therefore, a test which is very **sensitive** has **few** false negatives,.
    *   **Formula:** $False\ Negative\ Error\ Rate = 1 - Sensitivity$,.
*   **Statistical Error:** It corresponds to a **Type II Error** (Beta error), where the null hypothesis is false (disease is present), but it is accepted (test says negative),.

> [!warning] Diagram Alert
> 2x2 Contingency Table showing Disease Status vs. Test Result, highlighting cell 'c' as False Negatives

#### 2. Clinical and Public Health Interpretation
The presence of false negatives is often considered more dangerous than false positives in the context of lethal or communicable diseases.

*   **False Reassurance:** The most immediate consequence is giving the patient a "false reassurance" regarding their health status.
*   **Delayed Diagnosis:** The patient, believing they are healthy, might ignore the development of early signs and symptoms.
*   **Prognostic Impact:** Treatment is postponed. This can be **detrimental** if the disease is serious (e.g., cancer) and the screening test is not scheduled to be repeated for a long time,.
*   **Epidemiological Danger:** In communicable diseases (like Tuberculosis), a false negative case (e.g., missed sputum smear) remains in the community and continues to spread the infection to others.

#### 3. Causes of False Negatives
False negatives can arise due to various factors, often illustrated by **[[Sputum Smear Microscopy]]** for TB:
*   **Collection Errors:** Inadequate sample provided by the patient or inappropriate container used.
*   **Processing Errors:** Faulty sampling, smear preparation, or staining.
*   **Interpretation Errors:** Inadequate time spent examining the slide or low concentration of organisms (below the threshold of the test),.
*   **Biological Variation:** Overlapping distributions of healthy and diseased populations where the "cut-off" point is set too high to improve specificity,.

#### 4. The Trade-off: Specificity vs. Sensitivity
*   The lower the [[Sensitivity]], the larger the number of false negatives.
*   If a cut-off point for a test (e.g., blood sugar) is raised to increase **[[Specificity]]** (avoiding false alarms), the **Sensitivity** decreases, causing more cases to be missed (more false negatives).
*   **High Specificity** is desirable when false positives are a burden, but **High Sensitivity** is required when false negatives (missing a case) are intolerable.

### Clinical Relevance
*   **Tuberculosis:** A false negative sputum smear means a patient is denied early treatment and remains a source of infection.
*   **Cervical Cancer:** If a Pap smear or VIA has low sensitivity, a woman with early-stage dysplasia may be sent home as "normal," losing the window for curative intervention.

---
### Mnemonic: "MISS"
To remember the dangers of a **False Negative**, think of a **MISS**:

*   **M** - **M**issed Diagnosis (Disease is present but not found)
*   **I** - **I**gnored Symptoms (Patient feels safe, ignores warning signs)
*   **S** - **S**pread of Infection (In communicable diseases)
*   **S** - **S**ensitivity is Low (Low sensitivity = High False Negatives)

---
**Previous:** [[AEFI include events beyond side effects of vaccines]]  **Next:** [[Multiphasic screening]]