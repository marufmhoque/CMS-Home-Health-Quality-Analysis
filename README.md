# CMS-Home-Health-Quality-Analysis


Analysis of CMS Home Health Agency Quality Metrics
1. Project Motivation
The goal of this project is to analyze the quality of care provided by Home Health Agencies (HHAs) across the United States using data from the Centers for Medicare & Medicaid Services (CMS). As the population ages, understanding what makes an agency "high quality" becomes vital for patient choice and policy making.
This project follows the CRISP-DM process to answer three business questions:
Ownership Impact: Does the type of ownership (For-Profit vs. Non-Profit) significantly impact the average Star Rating of an agency?
Geographic Trends: Which states demonstrate the highest average patient improvement in mobility (ambulation)?
Predictive Modeling: Can clinical performance metrics, such as the timeliness of care initiation, be used to accurately predict if an agency will receive a "High" (4 or 5 star) rating?
2. File Descriptions
Home_Health_Analysis.ipynb: The main Jupyter Notebook containing the data cleaning, exploratory data analysis, visualizations, and the machine learning model.
HH_Quality_of_Patient_Care_Star_Ratings.csv: The raw dataset used for this analysis, sourced from the CMS Provider Data portal.
README.md: This file, providing project documentation and a summary of findings.
3. Installation
To run this project, you will need the following Python libraries installed:
Pandas (Data manipulation)
NumPy (Numerical computation)
Matplotlib / Seaborn (Data visualization)
Scikit-Learn (Machine learning)
You can install these via pip:
code
Bash
pip install pandas numpy matplotlib seaborn scikit-learn
4. Results Summary
The key findings from this analysis include:
Ownership: Non-profit agencies generally achieved higher average Star Ratings compared to their For-profit counterparts.
Geography: Top performing states for patient mobility improvement included [Insert the top states from your chart here].
Machine Learning: Using a Random Forest Classifier, I was able to predict whether an agency would be "High Rated" with approximately 65% accuracy based on clinical performance metrics. The analysis revealed that [Insert Top Feature from Importance Chart] was the strongest predictor of a high rating.
