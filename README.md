# AB Testing – Impact of Background Color on Average Session Duration

## 📌 Description
This project focuses on running an **AB test** to analyze whether a **UI design change** (background color palette) impacts **user engagement** on a machine learning blog website.  

The **key metric** used for evaluation is the **Average Session Duration** — the average time users spend on the website.  
We designed an experiment, split users into **control** and **variation** groups, analyzed the collected data, and applied **statistical hypothesis testing** to make a data-driven decision.

---

## 🎯 Objective
Determine whether **changing the background color** leads to a **statistically significant increase** in the **average session duration**.

---

## 🧩 Problem Setup
- **Business Goal:** Improve user engagement on the website.
- **Proposed Change:** Update the background color palette.
- **Metric of Interest:** Average Session Duration (in minutes).
- **Current Baseline:** 30.87 minutes.
- **Experiment Duration:** 20 days.
- **User Segmentation:**
  - **Control Group:** Sees the original design.
  - **Variation Group:** Sees the new background colors.

---

## 📊 Statistical Approach
We applied **AB testing** using a **t-test** for a **continuous metric** (session duration).

### **Hypotheses**
- **Null Hypothesis (H₀):**  
  The new background colors **do not affect** the average session duration.  
  \[
    \mu_{variation} = \mu_{control}
  \]
- **Alternative Hypothesis (H₁):**  
  The new background colors **increase** the average session duration.  
  \[
    \mu_{variation} > \mu_{control}
  \]

### **Significance Level**
\[
\alpha = 0.05
\]

### **Decision Rule**
- If **p-value < α** → **Reject H₀** → The new design **significantly improves engagement**.
- If **p-value ≥ α** → **Fail to Reject H₀** → No significant effect observed.

---

## 📂 Repository Structure
