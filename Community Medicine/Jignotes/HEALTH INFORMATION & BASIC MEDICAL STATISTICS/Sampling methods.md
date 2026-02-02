---
status: pending
tags: [Sampling_Methods, Biostatistics, Research_Methodology, Cluster_Sampling, Random_Sampling, Epidemiology, Community_Medicine]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 388
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Sampling methods

# Sampling Methods

**Sampling** is the process of selecting a representative segment of the population (a sample) to estimate the characteristics of the whole [[Population/Universe]]. It is a crucial step in research methodology as studying an entire population (Census) is often expensive, time-consuming, and operationally impossible.

> [!warning] Diagram Alert
> Flowchart showing the classification of sampling methods into Probability and Non-Probability types

### I. Probability (Random) Sampling
In this method, every unit of the population has a **known and equal chance** of being selected. This eliminates [[Selection Bias]] and allows for the calculation of sampling error.

**1. [[Simple Random Sampling]] (SRS)**
*   **Principle:** Every unit has an equal and independent chance of selection.
*   **Method:**
    *   **Lottery Method:** Numbering units on cards, shuffling, and drawing.
    *   **Random Number Tables:** Using standard tables (e.g., Fisher’s) to select units without bias.
*   **Applicability:** Best for small, homogeneous, and readily available populations (e.g., clinical trials).

**2. [[Systematic Random Sampling]]**
*   **Principle:** Selecting every $k^{th}$ unit from a list.
*   **Method:**
    1.  Calculate **Sampling Interval ($k$)** = $\frac{\text{Total Population (N)}}{\text{Desired Sample Size (n)}}$.
    2.  Select the first unit randomly between 1 and $k$.
    3.  Select every subsequent $k^{th}$ unit (e.g., 5th, 15th, 25th...).
*   **Applicability:** Large, non-homogeneous populations where a complete list (sampling frame) is available.

**3. [[Stratified Random Sampling]]**
*   **Principle:** Used when the population is **heterogeneous**.
*   **Method:**
    1.  Divide the population into homogeneous groups called **Strata** (e.g., by age, sex, socio-economic status).
    2.  Draw a random sample from *each* stratum, often proportional to its size.
*   **Benefit:** Ensures all subgroups are represented; increases [[Precision]].

**4. [[Multistage Sampling]]**
*   **Principle:** Sampling is done in successive stages, moving from larger to smaller units.
*   **Example:** Country $\rightarrow$ States $\rightarrow$ Districts $\rightarrow$ Villages $\rightarrow$ Households.
*   **Benefit:** Introduces flexibility; useful for large country-wide surveys where a complete list of all households is not initially available.

**5. [[Cluster Sampling]]**
*   **Principle:** The sampling units are natural groups or **clusters** (e.g., villages, wards, schools, factories).
*   **Method:** Randomly select clusters, then survey *all* or a random sample of units within those clusters.
*   **Clinical Relevance:**
    *   Used in the **Evaluation of Immunization Coverage** (Universal Immunization Program).
    *   **WHO Technique:** [[30 x 7 Cluster Sampling]] (Total 210 children; 30 clusters, 7 children per cluster).
*   **Note:** Clusters are heterogeneous within themselves but homogeneous with respect to each other.

**6. [[Multiphase Sampling]]**
*   **Principle:** Information is collected in successive phases.
*   **Example (TB Survey):**
    *   **Phase I:** [[Mantoux Test]] on all subjects.
    *   **Phase II:** Chest X-ray for Mantoux positives.
    *   **Phase III:** Sputum examination for X-ray positives.
*   **Benefit:** Cost-effective and purposeful.

---

### II. Non-Probability (Non-Random) Sampling
In this method, the chance of selection is unknown. It is prone to bias but is useful when random sampling is not feasible.

**1. [[Convenience Sampling]]**
*   Selection based on ease of access (e.g., examining patients attending a specific OPD).
*   High risk of selection bias; results cannot be generalized to the total population.

**2. [[Quota Sampling]]**
*   Similar to stratified sampling but **without** random selection.
*   The interviewer is given a "quota" (e.g., interview 50 males and 50 females) and selects them based on preference until the quota is filled.

**3. [[Snowball Sampling]]**
*   **Principle:** Existing study subjects recruit future subjects from among their acquaintances.
*   **Use:** Best for **Hidden Populations** or those with social stigma (e.g., [[Drug Abusers]], Commercial Sex Workers, HIV patients) where a sampling frame does not exist. The sample grows like a rolling snowball.

**4. [[Purposive Sampling]] (Judgmental)**
*   Deliberate selection of subjects who are thought to be most representative or typical of the population by the investigator.

---

### Comparison of Sampling Methods

| Feature | Probability Sampling | Non-Probability Sampling |
| :--- | :--- | :--- |
| **Selection** | Random (Chance) | Non-Random (Choice/Convenience) |
| **Bias** | Minimal / Eliminated | High (Selection Bias) |
| **Generalizability** | Results applicable to the whole population | Results valid only for the sample |
| **Types** | Simple, Systematic, Stratified, Cluster, Multistage | Convenience, Quota, Snowball, Purposive |
| **Use** | Analytical studies, RCTs | Pilot studies, Qualitative research |

---

### Mnemonics

**To remember Probability Sampling Methods:**
**"S**ome **S**tudents **S**tudy **M**any **M**edical **C**lusters"
*   **S**imple Random
*   **S**ystematic
*   **S**tratified
*   **M**ultistage
*   **M**ultiphase
*   **C**luster

**To remember Non-Probability Methods:**
**"C**ute **Q**ueens **S**now **P**urposely"
*   **C**onvenience
*   **Q**uota
*   **S**nowball
*   **P**urposive

---

### Clinical Relevance
*   **[[Randomized Controlled Trials]] (RCTs):** Require **Simple Random Sampling** to ensure the experimental and control groups are comparable and to remove bias.
*   **Field Surveys:** **Cluster Sampling** (specifically the 30x7 method) is the gold standard for rapid assessment of [[Vaccination Coverage]] in India.
*   **HIV/AIDS Research:** **Snowball Sampling** is crucial for reaching high-risk groups (HRGs) like IDUs (Injecting Drug Users) who are otherwise hidden from the health system.

---
**Previous:** [[Test of significances]]  **Next:** [[Criteria for selection of sampling and methods & registration systems in India]]