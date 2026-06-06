# 📊 Bottle Fill Quality Control & Statistical Analysis

## 🧪 Project Overview
This project analyzes the quality control process of a beverage company’s bottle filling system. The goal is to determine whether the filling process is statistically stable, normally distributed, and within acceptable rejection limits.

The analysis applies probability theory, normal distribution modeling, hypothesis testing, and business impact evaluation.

---

## 🎯 Objectives
- Determine if bottle fill data follows a normal distribution
- Calculate probabilities of under-filling and over-filling
- Evaluate overall rejection rate
- Test if process meets the 5% quality threshold
- Estimate business impact of process improvements

---

## 📂 Dataset
- 1000 bottle fill observations
- Variables:
  - `timestamp`
  - `fill_amount` (in ounces)

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Statsmodels

---

## 📊 Methods Used
- Histogram analysis
- Q-Q Plot
- Shapiro-Wilk normality test
- Z-score probability estimation
- Two-proportion z-test
- Confidence intervals
- Business impact modeling

---

## 📈 Key Findings

- The fill process is **not perfectly normally distributed**
- Under-filling probability: ~0.13%
- Over-filling probability: ~5.54%
- Total rejection rate: **5.67%**
- Process exceeds acceptable 5% threshold

---

## 📉 Business Impact

- ~58 additional rejected/affected bottles per 1000
- ~\$5,800 monthly revenue impact per 1000 customers
- Main issue: overfilling leading to product waste

---

## 🧪 Hypothesis Testing Result

- Statistical test: Two-proportion z-test
- Result: No strong evidence of significant difference at 5% level
- New onboarding improves retention but not statistically significant

---

## 📌 Conclusion

The current filling process exceeds acceptable quality limits and requires optimization. Adjustments should focus on reducing variability and centering the process closer to the target fill level.

---

## 👨‍💻 Author
Data Analysis Project – Probability & Statistics Lab
