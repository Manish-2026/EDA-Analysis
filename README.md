# 📉 Telecom Customer Churn Analysis

This repository contains an end-to-end customer churn analysis project for a telecom company. The objective is to identify patterns and key factors contributing to customer churn, with the goal of formulating effective retention strategies.

---

## 📊 Project Overview

The project analyzes customer demographics, contract types, service features, and payment methods using exploratory data analysis (EDA) and visualization techniques. Insights derived from the analysis are then summarized into actionable business recommendations.

---

## 🔍 Key Insights

- **Churn Rate**: 26.5% (1,869 out of 7,043 customers)
- **High Churn Risk**:
  - Senior citizens
  - Month-to-month contract users (~43% churn)
  - Customers with <12 months tenure
  - Fiber optic users (~42% churn)
  - Electronic check users (~45% churn)
- **Low Churn Risk**:
  - Long-term contracts (2-year: ~3% churn)
  - Auto-pay users (15–20% churn)
  - Users with OnlineSecurity/TechSupport

---

## 📈 Visualizations Used

- **Pie Charts**: Churn distribution, senior citizen share
- **Count Plots**: Churn by contract type, payment method, add-on services
- **Histogram**: Churn vs. tenure duration

---

## 📁 Project Structure

```bash
📦 Telecom-Churn-Analysis
├── Churn analysis.ipynb                 # Full Jupyter notebook analysis
├── telecome data.csv                    # Original dataset
├── 📄 Executive Summary and Recommendation.pdf
├── Key insight of the churned analysis.pdf
└── README.md                            # Project documentation
```

---

## 📌 Recommendations

- Offer **long-term contracts** with discounts
- **Upsell** value-added services (TechSupport, OnlineSecurity)
- Focus retention efforts on **first 3 months** of new customers
- Promote **auto-payment** options over manual methods

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis

---

## 📬 Contact
For questions, feedback, or collaboration, feel free to reach out via [GitHub Issues](https://github.com/) or email.

---

> 🔐 This project does not include any personal or sensitive customer information.


