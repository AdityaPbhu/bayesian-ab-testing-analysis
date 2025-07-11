# Bayesian A/B Testing Analysis

## Project Overview

In this project, I conducted an A/B testing analysis using both **frequentist and Bayesian approaches** on a synthetic dataset to demonstrate how Bayesian inference provides **more intuitive, actionable insights** for business decisions.

---

## Objective

**Problem:**  
Traditional A/B testing using p-values often leads to misinterpretation and does not directly communicate business-relevant probabilities.

**Goals:**

- Simulate an A/B test dataset with control and treatment groups
- Analyse conversion rates using a frequentist two-proportion z-test
- Apply Bayesian inference to calculate the probability that treatment outperforms control
- Compare insights and provide probability-based business recommendations

---

## Dataset

- **Synthetic A/B Testing Dataset** generated within the project notebook
  - user_id
  - group (control/treatment)
  - converted (0/1)

**Dataset Summary:**

- **Total Users:** 10,000
- **Control Group Conversion Rate:** 10%
- **Treatment Group Conversion Rate:** 12%

---

## Analysis Steps

1. Generated synthetic dataset with randomised group assignment and simulated conversion outcomes  
2. Verified data integrity and group distributions  
3. Performed **frequentist two-proportion z-test** to assess statistical significance  
4. Applied **Bayesian inference**:
   - Used Beta distributions for posterior estimation
   - Calculated probability that treatment conversion rate is higher than control  
5. Visualised posterior distributions for intuitive business interpretation

---

## Key Results

| Metric | Control | Treatment |
| ------ | ------- | --------- |
| Conversion Rate | 10% | 12% |
| Z-test p-value | 0.0016 | - |
| **Bayesian Probability Treatment > Control** | - | **99.86%** |

---

## Business Recommendations

1. **Implement Treatment Variant**  
   The Bayesian analysis shows a **99.86% probability that treatment outperforms control**, justifying rollout to maximise conversion and revenue.

2. **Adopt Bayesian Analysis for Future A/B Tests**  
   Bayesian inference provides clearer, probability-based insights over p-values, supporting confident decision-making in marketing and product teams.

3. **Monitor Long-Term Performance Post-Implementation**  
   Ensure uplift sustainability and identify further optimisation opportunities through continuous tracking.

---

## Conclusion

This project demonstrates how **Bayesian A/B testing delivers actionable, intuitive insights** compared to traditional frequentist methods, enabling more confident and informed business decisions.

---

## Tools Used

- Python (pandas, numpy)
- matplotlib, seaborn
- scipy.stats

---

## Repository Structure

- `bayesian_ab_testing_analysis.ipynb` – Main analysis notebook
- `images/` – Visualisations and posterior distribution plots

---

## Author

[Aditya Prabhu](https://github.com/AdityaPbhu)

---

**Feel free to connect if you have questions about this project or Bayesian business analytics.**
