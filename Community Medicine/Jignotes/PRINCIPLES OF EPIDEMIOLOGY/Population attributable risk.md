---
status: pending
tags: [epidemiology, population_attributable_risk, public_health, biostatistics, preventive_medicine, risk_assessment]
subject: Community Medicine
topic: PRINCIPLES OF EPIDEMIOLOGY
up: 36
---

# [[PRINCIPLES OF EPIDEMIOLOGY]] > Population attributable risk

# [[Population Attributable Risk]] (PAR)

**Population Attributable Risk (PAR)** is a crucial epidemiological measure used to estimate the magnitude of a health problem in the community caused by a specific exposure.

### 1. Definition
PAR represents the incidence of a disease (or death) in the **total population** minus the incidence of the disease among those who were **not exposed** to the suspected causal factor. 
It answers the question: *"How much of the disease in the total population can be attributed to this specific risk factor?"*,

### 2. The Formula
To calculate PAR (often expressed as a percentage), you need the incidence in the total population and the incidence in the non-exposed group.

**Formula:**
$$PAR = \frac{\text{Incidence in Total Population} - \text{Incidence in Non-Exposed}}{\text{Incidence in Total Population}} \times 100$$

OR

$$PAR = \frac{I_{total} - I_{non-exposed}}{I_{total}} \times 100$$

*Note: $I_{total}$ refers to the incidence in the whole community (both exposed and non-exposed).*,,

### 3. Interpretation (What does it mean?)
If a risk factor is modified or eliminated, the PAR tells us the percentage reduction in the incidence of the disease in the **given population**.
*   **Example:** If the PAR for smoking and lung cancer is 86%, it implies that if smoking were eliminated from the entire population, the incidence of lung cancer in that population would drop by 86%.,

### 4. Importance and Application
*   **Public Health Perspective:** While [[Relative Risk]] (RR) is important for clinicians and researchers to establish etiology (strength of association), **PAR** is of prime importance to **Public Health Programme Managers** and **Epidemiologists**.,
*   **Policy Making:** It helps determine priorities for health action. A risk factor with a high PAR indicates that controlling it will yield a significant reduction in the disease burden for the community.
*   **Community Impact:** REDUCING the risk factor $\rightarrow$ REDUCES disease load in the [[Community]].

> [!warning] Diagram Alert
> Pie chart showing the total burden of disease, with a slice highlighted representing the portion attributable to a specific risk factor (PAR), and the remaining slice representing background risk

### 5. Differences: RR vs AR vs PAR
This is a high-yield exam topic. Do not confuse these three indices.

| Feature | [[Relative Risk]] (RR) | [[Attributable Risk]] (AR) | [[Population Attributable Risk]] (PAR) |
| :--- | :--- | :--- | :--- |
| **Focus** | **Etiology** (Causation) | **Individual** (Clinical) | **Community** (Public Health) |
| **Question** | How *strong* is the association? | How much risk in the *exposed* is due to exposure? | How much risk in the *total population* is due to exposure? |
| **Formula** | $\frac{I_{exposed}}{I_{non-exposed}}$ | $\frac{I_{exposed} - I_{non-exposed}}{I_{exposed}}$ | $\frac{I_{total} - I_{non-exposed}}{I_{total}}$ |
| **Utility** | Strength of association | Impact on exposed group | Impact on total population |
| **User** | Researcher | Clinician | Public Health Planner |,,

### 6. Clinical Scenario Example
**Scenario:** A [[Cohort Study]] assesses the risk of lung cancer in a city.
*   Incidence of lung cancer in Total Population ($I_{total}$) = 11 per 1000
*   Incidence of lung cancer in Non-Smokers ($I_{non-exposed}$) = 1 per 1000

**Calculation:**
$$PAR = \frac{11 - 1}{11} \times 100$$
$$PAR = \frac{10}{11} \times 100 = \mathbf{90.9\%}$$

**Conclusion:** Roughly 91% of lung cancer cases in this city can be attributed to smoking. If smoking is eliminated, the lung cancer rate in the city will drop by ~91%.

### 7. Mnemonic for Exam
To remember the formula for PAR compared to AR:

*   **A**ttributable Risk starts with **A**, it is for the **A**ffected (Exposed) only.
    *   Denominator is **Exposed**.
*   **P**opulation Attributable Risk starts with **P**, it is for the **P**opulation (Whole).
    *   Denominator is **Total Population**.

> *“**P**AR is for the **P**ublic (Total Population)”*

---
**Previous:** [[Importance of incubation period]]  **Next:** [[Triple blinding in epidemiological studies]]