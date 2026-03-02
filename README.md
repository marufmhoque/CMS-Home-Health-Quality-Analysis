# CMS Home Health Quality Analysis

## 1. Project Motivation
The goal of this project is to analyze the factors that define "quality" in Home Health Care Agencies. As the population ages, understanding what makes an agency "high quality" is vital for patient choice and policy making. This project uses data from the Centers for Medicare & Medicaid Services (CMS) to separate industry "vibes" from clinical reality.

## 2. Business Questions
This project follows the CRISP-DM process to answer the following:
*   **Ownership Impact:** Does the type of ownership (Non-Profit vs. For-Profit) significantly impact the average Star Rating?
*   **Cost Efficiency:** Does higher quality care result in higher costs for Medicare?
*   **Predictive Modeling:** Which clinical metrics are the strongest predictors of an agency's Star Rating?
*   **Scenario Analysis:** Can we predict the impact of a 10% improvement in patient mobility on an agency's rating?

## 3. File Descriptions
*   **CMS_Home_Health_Analysis.ipynb:** The main Jupyter Notebook containing data cleaning, exploratory analysis, visualizations, and the Random Forest model.
*   **HH_Provider_Jan2026.csv:** The raw dataset used for this analysis, sourced from the CMS Provider Data portal.
*   **README.md:** Project documentation and a summary of findings.

## 4. Installation
To run this project, you will need the following Python libraries installed:
*   Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn.

You can install these via pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

medium article: https://medium.com/@marufisonfire/identifying-success-factors-in-home-health-agencies-1f3d233bba3d?postPublishedType=repub
