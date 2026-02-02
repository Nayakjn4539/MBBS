---
status: pending
tags: [sampling_error, biostatistics, standard_error, research_methodology, epidemiology]
subject: Community Medicine
topic: HEALTH INFORMATION & BASIC MEDICAL STATISTICS
up: 386
---

# [[HEALTH INFORMATION & BASIC MEDICAL STATISTICS]] > Sampling error

### **Sampling Error**

**Definition**
[[Sampling error]] refers to the difference or divergence between a sample statistic (e.g., sample mean) and the true population parameter (e.g., population mean) that occurs solely due to **chance**.
*   It arises because data is collected from a *part* (sample) rather than the *whole* (population/universe).
*   It represents a lack of **precision** in measurement.

**Key Characteristics**
1.  **Inevitable:** It is natural and occurs even in the best-designed studies because samples fluctuate.
2.  **Random:** It is a **random error**, *not* a systematic error (bias) or a mistake.
3.  **Variable:** If repeated samples are taken from the same population, the results will differ slightly from one another; this variation is the sampling error,.

**Factors Influencing Sampling Error**
The magnitude of sampling error is governed by two main factors,:

1.  **Size of the Sample ($n$):**
    *   There is an **inverse relationship**.
    *   As the [[sample size]] **increases**, the sampling error **decreases**.
    *   *Reasoning:* A larger sample is more representative of the total population.
2.  **Natural Variability (Dispersion):**
    *   There is a **direct relationship**.
    *   The greater the variation (dispersion) of individual readings within the population, the greater the sampling error.

**Measurement: The Standard Error (SE)**
The sampling error is measured/quantified by a statistic called the **[[Standard Error]] (SE)**.
*   **Formula:** $SE = \frac{\sigma}{\sqrt{n}}$
    *   Where $\sigma$ = Standard Deviation (Variability)
    *   $n$ = Sample Size
*   **Interpretation:** Because sample means generally follow a [[Normal Distribution]] around the true population mean, we can estimate that **95%** of sample means will lie within **$\pm$ 2 SE** of the true population mean.

**Difference from Non-Sampling Errors**
It is crucial to distinguish sampling errors from **non-sampling errors**, which are often more serious.

| Feature | **Sampling Error** | **Non-Sampling Error** |
| :--- | :--- | :--- |
| **Cause** | Due to studying a *part* of the population (Chance) | Due to flaws in design, conduct, or recording (Systematic/Human) |
| **Examples** | Natural variation between samples | [[Observer error]], Instrumental error, Incomplete coverage |
| **Prevention** | Cannot be eliminated; reduced by increasing $n$ | Can be eliminated by calibration, training, and protocols |

**Clinical & Research Relevance**
*   **Precision vs. Accuracy:** Sampling error affects **precision** (reliability/reproducibility), whereas bias affects **accuracy** (validity).
*   **Hypothesis Testing:** Researchers calculate the [[Standard Error]] to determine if an observed difference (e.g., effect of a drug) is real or just due to sampling error (chance).

**Mnemonic: "S.S. Minimizes"**
To remember how to reduce Sampling Error:
*   **S** - **S**ize of Sample (Increase it!)
*   **S** - **S**pread of data (Decrease variability!)

> [!warning] Diagram Alert
> Normal distribution curve showing the distribution of sample means around the population mean, illustrating how 95% of samples fall within 2 Standard Errors

---
**Previous:** [[Enlist the probability sampling methods. Elaborate on any 2 methods]]  **Next:** [[Test of significances]]