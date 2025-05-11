# 📊 Superstore Sales - Canonical Correlation Analysis (CCA) Project

## 🧾 Overview

This analysis is based on the **Superstore Sales** dataset, which includes various sales transactions from a retail store.

The dataset contains key features such as:
- Product categories
- Sales amounts
- Profits
- Discounts
- Quantities
- Shipping modes
- Regions

> 🎯 **Goal:** Extract meaningful statistical insights to help improve business performance, with a particular focus on increasing **sales** and **profits**.

---

## 🔬 Statistical Methods Applied

As part of this multivariate analysis project, the following statistical and inferential methods were applied:

1. **Measures of Central Tendency**
   - Mean, Median, Mode of key variables (e.g., Sales, Profit, Discount)
  
2. **Covariance Matrix**
   - To explore relationships and variability between numerical features

3. **Correlation Matrix**
   - To analyze linear relationships and strength/direction between variables

4. **One Variance Test** *(Sales)*
   - To test the homogeneity of variance for sales across a defined group

5. **Two Variances Test** *(Regions)*
   - To compare variance in sales or profit between different regional groups

6. **Multivariate Normality Test**
   - To assess if the dataset meets assumptions for multivariate analysis

7. **Canonical Correlation Analysis (CCA)**
   - To explore relationships between two sets of variables (e.g., Sales metrics vs. Regional attributes)

8. **Canonical Correspondence Analysis**
   - An extension used to visualize the association between categorical and continuous variables in context

---

## 📁 Project Structure

| File/Folder | Description |
|-------------|-------------|
| [`cca_analysis.ipynb`](https://github.com/OmarAhmedWahby/CanonicalCorrelationAnalysis/blob/main/CCA-Project.ipynb) | Main Jupyter Notebook with full analysis |
| [`superstore_sales.csv`](https://github.com/OmarAhmedWahby/CanonicalCorrelationAnalysis/blob/main/SampleSuperstore.csv) | Dataset used for analysis |
| [`presentation.pdf`](https://github.com/OmarAhmedWahby/CanonicalCorrelationAnalysis/blob/main/Statistical%20analysis%20For%20SuperStore%20Sales%20.pdf) | Summary presentation slides |
| [`plots/`](https://github.com/OmarAhmedWahby/CanonicalCorrelationAnalysis/tree/main/visualizations%20and%20graphs) | Folder containing all visualizations and graphs |

---

## 📌 Notes

- The dataset was cleaned and prepared using basic data wrangling.
- All tests and visualizations were run inside Jupyter Notebook using Python.
- Libraries used include: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`, and `sklearn`.

---

## 🤝 Contact

For inquiries or collaborations, feel free to reach out via [Omar Ahmed](https://www.linkedin.com/in/omarwahby/).
