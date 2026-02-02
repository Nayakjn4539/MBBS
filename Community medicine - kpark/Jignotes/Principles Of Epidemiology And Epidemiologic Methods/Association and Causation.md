---
status: pending
tags: [epidemiology, causality, association, Hillscriteria, biostatistics, publichealth, researchmethodology]
subject: Community medicine - kpark
topic: Principles Of Epidemiology And Epidemiologic Methods
up: 30
---

# [[Principles Of Epidemiology And Epidemiologic Methods]] > Association and Causation

# Association and Causation

In epidemiology, understanding the relationship between an exposure (risk factor) and an outcome (disease) is fundamental. However, simply observing that two events occur together does not prove that one caused the other.

## I. Concept of Association
[[Association]] is defined as the concurrence of two variables more often than would be expected by chance. It means events occur together more frequently than random probability.
*   **Correlation:** Indicates the degree of association between two characteristics (ranges from -1 to +1).
*   **Causation:** Implies that a change in one variable produces a change in the other.
*   **Rule of Thumb:** *Correlation does not imply Causation, but Causation implies Correlation*.

## II. Types of Association
Association is broadly grouped into three categories:

### 1. Spurious Association
This is an observed association that is **not real**. It usually arises due to [[Bias]] (systematic error), particularly selection bias.
*   **Example:** A study showing higher perinatal mortality in hospitals compared to home births. This suggests hospitals are unsafe.
*   **Reality:** Hospitals attract high-risk cases and complicated deliveries, while normal deliveries often happen at home. The association is an artifact of selection, not inferior quality of care.

### 2. Indirect Association
This is a statistical association between a characteristic and a disease due to the presence of a third factor, known as a **Confounding Variable** (Common Factor).
*   **Mechanism:** The confounder is related to both the disease and the characteristic.
*   **Example:** [[Endemic Goitre]] is associated with High Altitude.
    *   *Observation:* Goitre is common in Himalayan regions.
    *   *Reality:* Altitude does not cause goitre. **Iodine deficiency** (the confounder) is common in high-altitude soil/water. Iodine deficiency causes goitre, not the height itself.

> [!warning] Diagram Alert
> Draw a triangle showing Factor A (Altitude) and Factor B (Goitre) at the base, with a Confounding Factor C (Iodine Deficiency) at the apex connected to both A and B, explaining the indirect link

### 3. Direct (Causal) Association
This implies a true cause-and-effect relationship.
*   **A. One-to-One Causal Relationship:**
    *   Based on **Koch's Postulates** (Germ Theory).
    *   Suggests that Agent A is *Necessary* and *Sufficient* to cause Disease B,.
    *   *Limitation:* Rare in biological phenomena and non-communicable diseases. Even in TB, the bacillus is necessary but not sufficient (host immunity matters).
*   **B. Multifactorial Causation:**
    *   Used for non-communicable diseases (e.g., CHD, Cancer).
    *   Multiple factors act cumulatively or synergistically to produce disease,.
    *   Concept: [[Web of Causation]] (MacMahon and Pugh).

---

## III. Criteria for Judging Causality (Hill's Criteria)
Since direct experimentation on humans is often unethical or impossible, epidemiologists use specific criteria (Bradford Hill's Criteria/Surgeon General's Report) to determine if an association is causal,.

**Mnemonic: "Dr. SCAB is Temporarily Strong"**
*(**D**ose, **R**eversibility, **S**pecificity, **C**onsistency, **A**nalogy/Study Design, **B**iological plausibility, **T**emporality, **S**trength)*

### 1. Temporal Association (Temporality)
*   **Definition:** The cause must **precede** the effect.
*   **Importance:** This is the **most important** and essential criterion,.
*   **Example:** Asbestos exposure must occur years before the development of lung mesothelioma.
*   **Best Study Design:** [[Cohort Study]] (Concurrent).

### 2. Strength of Association
*   **Definition:** Determined by the magnitude of [[Relative Risk]] (RR) or [[Odds Ratio]] (OR).
*   **Interpretation:** The larger the RR, the more likely the association is causal.
*   **Example:** Smokers have a 10x greater risk of lung cancer (High RR) compared to non-smokers,.

### 3. Specificity of Association
*   **Definition:** One cause leads to one specific effect.
*   **Limitation:** This is the **weakest criterion** because one agent can cause multiple diseases (e.g., Smoking causes Lung Ca, CHD, COPD) and one disease can have multiple causes,.
*   **Note:** Specificity supports causality, but lack of specificity does not negate it.

### 4. Consistency of Association
*   **Definition:** Results are replicated in different settings, by different methods, and different investigators.
*   **Example:** Over 50 retrospective and 9 prospective studies globally confirmed the link between smoking and lung cancer.

### 5. Biological Plausibility
*   **Definition:** The association agrees with current biological knowledge (anatomy, physiology, pathology).
*   **Example:** Inhalation of carcinogens in smoke damaging bronchial epithelium is biologically biologically consistent with lung cancer pathology.

### 6. Coherence of Association
*   **Definition:** The cause-and-effect interpretation should not conflict with known facts of the natural history and biology of the disease.
*   **Example:** Historical rise in tobacco consumption correlates with the historical rise in lung cancer rates.

### 7. Dose-Response Relationship (Biological Gradient)
*   **Definition:** Increased exposure to the risk factor leads to increased incidence of the disease.
*   **Example:** Heavy smokers have higher cancer rates than light smokers.

### 8. Reversibility (Cessation of Exposure)
*   **Definition:** Removal of the cause results in a reduction of disease risk.
*   **Example:** Ex-smokers have a lower risk of lung cancer compared to current smokers.

### 9. Study Design
*   Evidence from **Randomized Controlled Trials (RCTs)** provides the strongest proof of causality, followed by Cohort studies.

---

## IV. Association vs. Causation Summary Table

| Feature | Association | Causation |
| :--- | :--- | :--- |
| **Definition** | Simultaneous existence of two variables | One variable produces the other |
| **Relationship** | Statistical dependence | Cause and Effect |
| **Direction** | Non-directional (A with B) | Directional (A causes B) |
| **Validation** | P-value (Significance) | Hill's Criteria |
| **Study Design** | Case-Control, Cross-sectional | Cohort, RCT |

---

### Clinical Relevance
Understanding the difference between association and causation prevents "Ecological Fallacy" and helps doctors avoid making treatment decisions based on spurious data. For example, while coffee drinking might be *associated* with pancreatic cancer in some data, further causal analysis often reveals smoking (a confounder common in coffee drinkers) is the true cause.

---
**Previous:** [[Bias in epidemiologic Studies]]  **Next:** [[Investigation of an Epidemic]]