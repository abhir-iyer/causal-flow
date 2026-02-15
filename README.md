# Causal-Flow  
### Experimentation & Causal Intelligence Framework for Product Optimization

Causal-Flow is a product-focused experimentation platform that evaluates the true incremental impact of marketing campaigns and feature rollouts using causal inference techniques.

It is designed to go beyond naive A/B test comparisons and provide bias-corrected lift estimates, segment-level treatment effects, and executive-ready ROI recommendations.

---

## 🎯 Business Problem

A subscriber perks campaign appears to increase 30-day retention.

Naive analysis suggests strong lift — but high-engagement users are more likely to receive perks, introducing selection bias.

Causal-Flow answers:

- Did the perk truly cause retention improvement?
- How much incremental lift exists after bias correction?
- Which user segments benefit most?
- Is the campaign financially viable?

---

## 📊 Key Results (Simulated Dataset)

- **Naive Retention Lift:** 0.17%
- **Bias-Corrected Lift (PSM):** 0.14%
- **Overestimation from Bias:** ~20%
- **Segment Variation:** 3x difference in treatment response
- **Targeted Rollout ROI:** +142%
- **Broad Rollout ROI:** Negative

Conclusion: Targeted deployment is significantly more profitable than blanket rollout.

---

## 🔬 Causal Methods Implemented

### 1. Difference-in-Differences (DiD)
Controls for time-based trends and isolates incremental treatment impact.

### 2. Propensity Score Matching (PSM)
Balances covariates to correct for selection bias in observational data.

### 3. Uplift Modeling (CATE)
Estimates heterogeneous treatment effects across user segments.

### 4. Business Impact Translation
Converts incremental retention lift into projected revenue and ROI.

---

## 📈 Validation & Diagnostics

- Covariate balance verified before and after matching
- 95% confidence intervals reported for lift estimates
- Parallel trends assumption assessed for DiD validity
- Sensitivity analysis conducted on cost and lift assumptions

---

## 🧠 Executive Decision Support

The platform does not stop at statistical significance.

It provides:

- Clear recommendation (scale / segment / halt)
- Projected incremental revenue
- ROI comparison across strategies
- Segment-level targeting guidance

This mirrors real-world product experimentation workflows.

---

## 🏗️ Architecture

**Frontend**
- Static HTML/CSS dashboard
- Executive summary + experimentation metrics

**Backend Logic (Engine Repository)**
- Python (statsmodels, scikit-learn)
- Difference-in-Differences modeling
- Propensity score matching
- Uplift estimation

The frontend presents results from the causal engine in a product-ready interface.

---

## 🛠 Tech Stack

- Python  
- statsmodels  
- scikit-learn  
- Pandas  
- HTML / CSS  
- Vercel deployment  

---

## 📌 What This Project Demonstrates

- End-to-end causal analysis ownership
- Ability to detect and correct observational bias
- Product-facing experimentation design
- Translation of statistical results into business decisions
- Clean presentation for cross-functional stakeholders

---

## 👤 Author

Abhir Iyer  
MS Data Science  
Product Analytics • Causal Inference • Experimentation Systems