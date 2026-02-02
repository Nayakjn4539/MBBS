---
status: pending
tags: [Biostatistics, SamplingTechniques, ResearchMethodology, CommunityMedicine, ClusterSampling]
subject: Community medicine - kpark
topic: Health Information And Basic Medical Statistics
up: 174
---

# [[Health Information And Basic Medical Statistics]] > Sampling Techniques

### **Sampling Techniques**

**Definition**
[[Sampling]] is the process of selecting a part of the population (sample) to represent the whole population (universe). It is easier, more economical, and less time-consuming than studying the entire population (Census).

*   **Population (Universe):** The entire group of people or items under study (e.g., all TB patients in India).
*   **Sample:** A subset of the population used to estimate the characteristics of the whole.
*   **Sampling Frame:** A complete list of all units in the population from which the sample is drawn.

> [!warning] Diagram Alert
> Flowchart showing the classification of Sampling Methods into Probability (Random) and Non-Probability (Non-Random)

---

### **A. Probability (Random) Sampling**
In this method, every unit of the population has a **known and equal chance** of being selected. This eliminates [[Selection Bias]].

**Mnemonic:** **S**imple **S**ystems **S**tart **M**any **M**assive **C**lusters
(Simple, Systematic, Stratified, Multistage, Multiphase, Cluster)

#### **1. Simple Random Sampling**
*   **Principle:** Every unit has an equal chance of selection.
*   **Method:**
    *   **Lottery Method:** Numbering units on cards, shuffling, and drawing them.
    *   **Random Number Tables:** Using standard tables (e.g., Tippett’s) to select numbers blindly.
    *   **Computer Software:** Generating random lists.
*   **Advantage:** Most representative if the population is small and homogeneous.
*   **Clinical Relevance:** Used in **Randomized Controlled Trials (RCTs)** to assign patients to study groups.

#### **2. Systematic Random Sampling**
*   **Principle:** Selecting every $k^{th}$ unit from a list.
*   **Method:**
    1.  Calculate **Sampling Interval (k)** = Total Population / Desired Sample Size.
    2.  Select the *first* number randomly between 1 and $k$.
    3.  Select every subsequent $k^{th}$ unit.
*   **Example:** In a hospital OPD with 1000 patients, to select 100 patients ($k=10$), pick the 5th, 15th, 25th... patient.
*   **Advantage:** Simple and convenient.

#### **3. Stratified Random Sampling**
*   **Principle:** Used when the population is **heterogeneous**. The population is divided into homogeneous groups called **Strata** (e.g., by age, sex, religion, or SES).
*   **Method:** A random sample is drawn from *each* stratum, often proportional to its size.
*   **Advantage:** Ensures all sub-groups are represented; gives greater precision.

#### **4. Multistage Sampling**
*   **Principle:** Sampling is done in stages, moving from larger units to smaller units.
*   **Method:** Country $\rightarrow$ State $\rightarrow$ District $\rightarrow$ Village $\rightarrow$ Household.
*   **Advantage:** Introduces flexibility; useful for large country-wide surveys.

#### **5. Cluster Sampling**
*   **Principle:** Used when the population forms natural groups or **Clusters** (e.g., villages, wards, slums, schools).
*   **Key Feature:** Clusters are **heterogeneous within** themselves but **homogeneous with respect to each other**.
*   **Method:** Randomly select a few clusters and survey *everyone* (or a sample) within those clusters.
*   **Clinical Relevance:** **[[30 x 7 Cluster Sampling]]**
    *   Used by WHO/India for evaluation of **[[Immunization Coverage]]**.
    *   30 clusters are selected; 7 children (12–23 months) are surveyed in each.
    *   Total sample = 210 children.
*   **Disadvantage:** Higher standard error compared to simple random sampling; clusters cannot be compared with each other.

#### **6. Multiphase Sampling**
*   **Principle:** Part of the information is collected from the whole sample, and detailed information is collected from a sub-sample.
*   **Example:** **[[Tuberculosis]]** survey:
    *   Phase 1: Mantoux test (All subjects).
    *   Phase 2: X-ray (Only Mantoux positives).
    *   Phase 3: Sputum Exam (Only X-ray positives).

---

### **B. Non-Probability (Non-Random) Sampling**
The probability of selection is unknown. This method is prone to bias but is useful when random sampling is not feasible.

#### **1. Convenience Sampling**
*   **Method:** Selecting subjects based on ease of access/availability (e.g., patients sitting in a clinic, shoppers in a mall).
*   **Disadvantage:** High selection bias; not representative of the general population.

#### **2. Quota Sampling**
*   **Method:** The population is segmented into mutually exclusive subgroups (quotas) like stratified sampling, but the selection within the group is **not random** (based on interviewer's preference).

#### **3. Snowball Sampling**
*   **Method:** The investigator finds one subject, who then recruits others from their acquaintances (like a rolling snowball).
*   **Clinical Relevance:** Used for **Hidden Populations** or groups with social stigma (e.g., **Drug abusers**, Commercial Sex Workers, HIV high-risk groups).

---

### **Sampling Errors**

| Type of Error | Description | Relation to Sample Size |
| :--- | :--- | :--- |
| **[[Sampling Error]]** | The difference between the sample statistic (e.g., sample mean) and the true population parameter due to chance. | Inversely proportional. **Larger sample size = Smaller Sampling Error**. |
| **Non-Sampling Error** | Errors due to faulty instruments, observer bias, incomplete coverage, or defective sampling frame. | Does not necessarily decrease with sample size; depends on methodology quality. |

> [!warning] Diagram Alert
> Draw a graph showing the Normal Distribution Curve of sample means to illustrate Standard Error

---
**Previous:** [[Measures of Dispersion]]  **Next:** [[Tests of Significance]]