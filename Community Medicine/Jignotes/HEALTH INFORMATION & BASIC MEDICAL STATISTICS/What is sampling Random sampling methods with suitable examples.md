---
status: pending
tags: [sampling, biostatistics, research_methodology, epidemiology, random_sampling, cluster_sampling, stratified_sampling]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 369
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > What is sampling Random sampling methods with suitable examples

### **Sampling**

**Definition**
[[Sampling]] is the process of selecting a subset of individuals or units from within a statistical population to estimate the characteristics of the whole population.
*   It is easier, faster, and more economical to study a sample than the entire population (universe).
*   The group of sampling units form a sample, generally selected to be **representative** of the population.

**Prerequisites**
*   **Sampling Frame:** A complete list of all members/units of the universe from which the sample is drawn.
*   **Representative Sample:** It should possess the same characteristics as the population, differing only by chance.

---

### **Random Sampling Methods (Probability Sampling)**

In [[Random Sampling]], every unit of the population has an **equal and known** chance of being selected. This eliminates [[Selection Bias]] and allows for the calculation of sampling error.

#### **1. Simple Random Sampling (Unrestricted Random Sampling)**
*   **Principle:** Every unit has an equal chance of being chosen. The selection of one unit does not affect the selection of another,.
*   **Suitability:** Best for small, homogeneous, and readily available populations,.
*   **Methodology:**
    *   **Lottery Method:** Numbering units on cards, shuffling them, and drawing the required number.
    *   **Table of Random Numbers:** Using standard tables (e.g., Tippett's tables) to select units without bias,.
*   **Example:** To select 10 patients for a clinical trial out of 100 available patients, assign numbers 1–100 and pick 10 numbers using a random number table.

#### **2. Systematic Random Sampling**
*   **Principle:** The sample is selected according to a predetermined periodicity or interval.
*   **Methodology:**
    *   Calculate the **Sampling Interval ($k$)**: $k = \frac{\text{Total Population}}{\text{Sample Size}}$.
    *   The first unit is selected randomly between 1 and $k$.
    *   Subsequent units are chosen by adding $k$ to the previous number (e.g., 5th, 15th, 25th...).
*   **Suitability:** Convenient for large, non-homogeneous populations where a complete list (sampling frame) is available.
*   **Example:** To select a 10% sample from 1,000 patients ($k=10$). If the first random number selected is 6, the sample includes the 6th, 16th, 26th, 36th... patients.

#### **3. Stratified Random Sampling**
*   **Principle:** The population is first divided into **homogeneous** subgroups called **strata** based on a characteristic (e.g., age, sex, socioeconomic status). A random sample is then drawn from *each* stratum, usually proportionate to its size,,.
*   **Logic:** It ensures that all subgroups are adequately represented, making it more accurate than simple random sampling for non-homogeneous populations.
*   **Example:** To study [[Hemoglobin]] levels in a population of 1,000 (700 males, 300 females) requiring a sample of 100:
    *   *Stratum 1 (Males):* Select 70 males randomly.
    *   *Stratum 2 (Females):* Select 30 females randomly.

#### **4. Cluster Random Sampling**
*   **Principle:** The sampling units are natural groups or **clusters** (e.g., villages, wards, schools, factories) rather than individuals,.
*   **Methodology:**
    *   Clusters are selected randomly.
    *   All individuals within the selected clusters are surveyed.
    *   Clusters are usually heterogeneous internally but homogeneous with respect to each other.
*   **Use:** Extensively used in public health, specifically for the **Evaluation of Immunization Coverage** using the **30 $\times$ 7 technique** (30 clusters, 7 children per cluster = 210 children),.
*   **Example:** To assess vaccination status in a district, 30 villages (clusters) are selected randomly, and all eligible children in those villages are surveyed.

#### **5. Multistage Sampling**
*   **Principle:** Sampling is carried out in **successive stages**, using random sampling at each stage,.
*   **Logic:** It introduces flexibility and allows the use of existing administrative divisions.
*   **Example:** In a large country survey:
    *   *Stage 1:* Select random States.
    *   *Stage 2:* Select random Districts within those states.
    *   *Stage 3:* Select random Villages within those districts,.

#### **6. Multiphase Sampling**
*   **Principle:** Part of the information is collected from the whole sample, and detailed information is collected from a sub-sample.
*   **Example:** In a [[Tuberculosis]] survey:
    *   *Phase 1:* Mantoux test for all subjects.
    *   *Phase 2:* X-ray for Mantoux positives.
    *   *Phase 3:* Sputum examination for those with positive X-ray,.

---

### **Summary of Random Sampling Methods**

| Method | Key Feature | Ideal For |
| :--- | :--- | :--- |
| **Simple Random** | Equal chance for all; Lottery method | Small, homogeneous, defined populations. |
| **Systematic** | Every $k^{th}$ unit selected | Large populations with a list (e.g., hospital registers). |
| **Stratified** | Population divided into homogeneous strata | Non-homogeneous populations; ensures representation of subgroups. |
| **Cluster** | Natural groups (villages/wards) selected | Public health surveys (e.g., Immunization coverage). |
| **Multistage** | Sampling in steps (State $\rightarrow$ District) | Large country-wide surveys. |
| **Multiphase** | Screening in phases (Broad $\rightarrow$ Specific) | Disease surveys (e.g., TB) to save cost and labor. |

---

### **Clinical Relevance**
*   **Validity:** Random sampling is crucial in medical research to ensure **External Validity** (Generalizability). If a sample is not random (e.g., hospital-based only), the results cannot be applied to the general community due to **Selection Bias**.
*   **Standard Error:** Random sampling allows the calculation of the [[Standard Error]], which measures the precision of the sample estimate compared to the true population parameter.

---

### **Mnemonic**
To remember the types of Random Sampling: **"S**imple **S**ystem **S**trategy **M**akes **M**ultiple **C**lusters"

*   **S**imple Random
*   **S**ystematic
*   **S**tratified
*   **M**ultistage
*   **M**ultiphase
*   **C**luster

---
**Previous:** [[Statistical data – various methods of presentation]]  **Next:** [[Chi Square test & Uses]]