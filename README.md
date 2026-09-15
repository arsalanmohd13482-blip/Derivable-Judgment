# 🩺 Derivable Judgement — Statistical Decision-Making Model

> **A statistical decision-making framework for identifying and evaluating factors associated with disease occurrence.**

## 📌 Project Overview

**Derivable Judgement** applies statistical methods to simulated health records to investigate relationships between **lifestyle factors, demographic characteristics, health measurements, and chronic diseases**.

The project is designed from the perspective of a **public health data analyst**, using hypothesis testing and statistical relationships to convert health data into evidence-based judgements.

The dataset contains **100 simulated health records** covering age, BMI, smoking status, exercise frequency, blood pressure, cholesterol, glucose, diabetes, and hypertension.

---

## 🎯 Objectives

- Test whether smoking status is associated with diabetes prevalence
- Compare BMI between individuals with and without hypertension
- Estimate population parameters using **95% confidence intervals**
- Determine whether cholesterol levels differ across age groups
- Measure relationships between important continuous health variables
- Use statistical evidence to support data-driven conclusions

---

# 🔬 Statistical Analysis

## 1️⃣ Hypothesis Testing — Chi-Square Test

### Research Question

> Does smoking status have a significant association with diabetes prevalence?

**H₀:** Smoking status has no effect on diabetes prevalence.

**H₁:** Smoking status significantly affects diabetes prevalence.

A **Chi-Square Test of Independence** is applied using a contingency table of smoking status versus diabetes outcome.

This evaluates whether the two categorical variables are statistically associated.

---

## 2️⃣ Hypothesis Testing — Welch's T-Test

### Research Question

> Do individuals with hypertension have a higher mean BMI than individuals without hypertension?

**H₀:** There is no difference in mean BMI between the two groups.

**H₁:** Individuals with hypertension have a significantly higher mean BMI.

A **one-tailed Welch's independent t-test** is used because the analysis compares the mean BMI of two groups without assuming equal variances.

---

## 3️⃣ Confidence Intervals

The project calculates **95% confidence intervals** for:

- Age
- Weight
- BMI

For each variable, the analysis estimates:

**Mean → Lower Confidence Bound → Upper Confidence Bound**

This provides an estimated range for the corresponding population mean based on the simulated sample.

---

## 4️⃣ ANOVA — Comparing Multiple Groups

### Research Question

> Do cholesterol levels significantly differ across different age groups?

Age is divided into:

- **Young**
- **Middle-aged**
- **Older**

A **One-Way ANOVA** is then performed on cholesterol levels.

**H₀:** All age-group means are equal.

**H₁:** At least one group mean is different.

ANOVA is useful here because the analysis compares a numerical variable across **three independent groups**.

---

## 5️⃣ Covariance & Correlation Analysis

The project investigates relationships between continuous health variables.

### Covariance

Covariance is calculated for:

- **Age vs BMI**
- **Blood Pressure vs Glucose Level**

It helps identify the **direction of how two variables vary together**.

### Pearson Correlation

Measures the strength of a **linear relationship** between:

- Age
- BMI
- Blood Pressure
- Glucose Level

### Spearman Correlation

Measures the strength of a **monotonic relationship** and provides a useful comparison with Pearson correlation.

---

# 📊 Statistical Methods Summary

| Method | Variables / Purpose |
|---|---|
| **Chi-Square Test** | Smoking Status → Diabetes |
| **Welch's T-Test** | BMI → Hypertension Groups |
| **Confidence Interval** | Age, Weight & BMI |
| **One-Way ANOVA** | Age Groups → Cholesterol |
| **Covariance** | Age vs BMI, Blood Pressure vs Glucose |
| **Pearson Correlation** | Linear relationships |
| **Spearman Correlation** | Monotonic relationships |

---

# 💡 Analytical Value

This project demonstrates how different statistical methods can answer different types of public-health questions:

- **Chi-Square** → Is there an association?
- **T-Test** → Are two group means different?
- **Confidence Interval** → What is the plausible range of a population mean?
- **ANOVA** → Do multiple groups differ?
- **Correlation** → How strongly are numerical variables related?
- **Covariance** → In which direction do variables vary together?

The key principle is to **select the statistical method based on the question and type of variables**, rather than applying the same test to every problem.

---

# 🛠️ Tools & Technologies

- Python
- NumPy
- Pandas
- SciPy
- Statistical Hypothesis Testing
- Data Analysis

---

# 📁 Project Structure

```text
Derivable-Judgement/
│
├── derivable_judgement.py
├── Medical_data
└── README.md
````

---

# 🚀 Skills Demonstrated

**Statistical Analysis • Hypothesis Testing • Chi-Square Test • Welch's T-Test • Confidence Intervals • ANOVA • Covariance • Pearson Correlation • Spearman Correlation • Python • NumPy • Pandas • SciPy • Analytical Thinking**

---

## 📌 Final Takeaway

**Derivable Judgement demonstrates how statistical testing can transform health data into structured evidence for decision-making.**

The project connects:

**Health Data → Statistical Test → Evidence → Interpretation → Decision Support**

This provides a practical foundation for using statistics in **public health research and data-driven analysis**.
