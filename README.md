# Insurance Claims Exploratory Data Analysis

An end-to-end Exploratory Data Analysis (EDA) project investigating the impact of demographic, lifestyle, and health-related factors on insurance claim amounts using Python, Pandas, Matplotlib, and Seaborn.

## Dataset

This project uses the **Insurance Claim Analysis: Demographic and Health Factors** dataset available on Kaggle.

🔗 Dataset Link: https://www.kaggle.com/datasets/thedevastator/insurance-claim-analysis-demographic-and-health

The dataset contains demographic, lifestyle, and health-related information such as age, gender, BMI, blood pressure, smoking status, diabetic status, region, number of children, and insurance claim amounts.

---

## Project Objectives

- Understand the distribution of insurance claims.
- Identify factors associated with higher claim amounts.
- Perform univariate, bivariate, and trivariate analysis.
- Generate actionable insights from the dataset.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Analysis Performed

### Univariate Analysis
- Histograms
- KDE Plots
- Boxplots
- Violin Plots

### Bivariate Analysis
- Correlation Analysis
- Scatter Plots
- Regression Plots
- Boxplots across categorical variables

### Feature Engineering

Created custom groups for:

- BMI Categories
- Blood Pressure Categories
- Family Size Categories

### Trivariate Analysis

Analyzed the combined effect of:

- Smoking Status + BMI Group + Claim Amount
- Smoking Status + Blood Pressure Group + Claim Amount

---

## Key Findings

- Smoking status emerged as the strongest factor associated with higher insurance claims.
- Obesity amplifies the effect of smoking on claim amounts.
- Individuals with very high blood pressure tend to have higher claims.
- Family size, gender, diabetic status, and region show comparatively weaker relationships with claim amount.
- Variables that appeared weak during bivariate analysis revealed stronger patterns when analyzed alongside smoking status.

---

## Repository Structure

```text
├── insurance_data.csv
├── EDA NOTEBOOK ON INSURANCE DATASET.ipynb
├── README.md
```

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Correlation Analysis
- Multivariate Analysis
- Statistical Interpretation
- Business Insight Generation

---

## Author

**Ronit Roy**
