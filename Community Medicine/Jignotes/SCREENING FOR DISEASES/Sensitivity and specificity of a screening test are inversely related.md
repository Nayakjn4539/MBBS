---
status: pending
tags: [Sensitivity, Specificity, Screening_of_Disease, Cut_off_point, Epidemiology, Biostatistics]
subject: Community Medicine
topic: SCREENING FOR DISEASES
up: 56
---

# [[SCREENING FOR DISEASES]] > Sensitivity and specificity of a screening test are inversely related

### The Inverse Relationship Between Sensitivity and Specificity

In the context of [[screening for diseases]], **sensitivity** and **specificity** are inherent properties of a test. They are **inversely related**, meaning that as one increases, the other generally decreases. This relationship is primarily dictated by the selection of the **[[cut-off point]]** (threshold) used to distinguish between "diseased" and "non-diseased" individuals.

#### 1. The Concept of Overlap
In most biological variables (e.g., blood pressure, blood sugar, intraocular pressure), the values are continuously distributed. There is rarely a sharp dividing line between the "normal" and "diseased" populations. Instead, there is often an **overlap** in the distribution curves of healthy and diseased persons.
*   **Unimodal Distribution:** Physiological variables usually form a single curve where the "borderline" group comprises a mixture of persons with and without the disease.

> [!warning] Diagram Alert
> Two bell-shaped curves (Normal Distribution) overlapping in the middle. The left curve represents the 'Healthy' population and the right curve represents the 'Diseased' population. A vertical line represents the 'Cut-off point' moving left or right within the overlap area.

#### 2. The Role of the Cut-off Point
Because of this overlap, a decision must be made regarding where to set the **[[cut-off point]]** or criterion level to classify an individual as abnormal. Moving this cut-off point shifts the balance between [[Sensitivity]] (catching all cases) and [[Specificity]] (excluding all normals).

**Example: Screening for Diabetes (Blood Glucose)**
If we screen a population for diabetes using blood glucose levels:

*   **Scenario A: Lowering the Cut-off (e.g., to 120 mg/dl)**
    *   **Effect:** We cast a "wider net." We catch almost everyone with the disease.
    *   **Result:** [[Sensitivity]] increases (we miss very few cases).
    *   **Consequence:** [[Specificity]] decreases. Many healthy people with naturally higher sugar (borderline) are wrongly labeled as diabetic ([[False Positives]]).

*   **Scenario B: Raising the Cut-off (e.g., to 180 mg/dl)**
    *   **Effect:** We make the criteria "stricter." We only label those with very high sugar as diseased.
    *   **Result:** [[Specificity]] increases (we correctly identify healthy people).
    *   **Consequence:** [[Sensitivity]] decreases. We miss mild cases of diabetes who have sugar levels below 180 ([[False Negatives]]).

#### 3. Summary of the Trade-off

| Action on Cut-off Point | Sensitivity (True Positive Rate) | Specificity (True Negative Rate) | False Positives | False Negatives |
| :--- | :--- | :--- | :--- | :--- |
| **Lowered** (More inclusive) | **Increases** | **Decreases** | Increases | Decreases |
| **Raised** (More strict) | **Decreases** | **Increases** | Decreases | Increases |

*Source: Derived from,*

#### 4. Clinical Relevance: Choosing the Right Cut-off
Since no test is perfect (100% sensitive *and* 100% specific), the choice of the cut-off depends on the nature of the disease:

*   **High Sensitivity Needed:** For lethal diseases where early detection saves lives (e.g., [[Cervical Cancer]], Phenylketonuria). We can tolerate False Positives, but we cannot afford to miss a case (False Negatives are dangerous).
*   **High Specificity Needed:** For diseases where treatment is risky, expensive, or stigmatizing, or where the disease is not immediately fatal (e.g., [[Diabetes]]). We want to be sure a person has the disease before labeling them to avoid burdening the health system with False Positives.

---
### Mnemonic: The **"S"** Slide
Imagine a slider bar for the cut-off point:
*   Slide to the **L**eft $\rightarrow$ **L**ots of cases caught (**High Sensitivity**) but **L**ow Specificity.
*   Slide to the **R**ight $\rightarrow$ **R**eally specific (**High Specificity**) but **R**isk missing cases (Low Sensitivity).

**Funny Memory Hook:**
*"If you are too **Sensitive** (low cut-off), you cry at everything (lots of **False Positives**). If you are too **Specific** (high cut-off), you don't even cry at a funeral (lots of **False Negatives**)."*

---
**Previous:** [[Screening and diagnostic test differ]]  **Next:** [[Sentinel surveillance of disease is better than periodic mass screening]]