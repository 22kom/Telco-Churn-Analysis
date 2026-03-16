# Telco-Churn-Analysis
Exploratory Data Analysis and Churn Prediction for a Telecom dataset using Python and Pandas.
# Customer Segmentation & Churn Prediction Analysis 📊
## Project Overview
This project focuses on analyzing customer behavior in a telecommunications company to identify key factors leading to **churn** (customers leaving the service). By leveraging Exploratory Data Analysis (EDA) and Machine Learning, the project provides actionable insights to improve customer retention.

## Key Business Insights
- **Churn Rate:** The dataset has a **26.5% churn rate**, indicating a significant opportunity for retention strategies.
- **The "Danger Zone":** Most churn occurs within the first **6 months** of joining. If a customer stays past the first year, they are significantly more likely to remain loyal.
- **Contract Impact:** Customers on **Month-to-Month** contracts are the highest risk group, while those on 1 or 2-year contracts show almost zero churn.
- **Service Friction:** **Fiber Optic** users churn more frequently than DSL users, suggesting a need to investigate service stability or pricing in that segment.

## Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Environment:** Jupyter Notebook / Anaconda

## Project Structure
- `data/`: Contains the customer dataset.
- `notebooks/`: Includes the step-by-step analysis from data cleaning to modeling.
- `visualizations/`: PNG files of the most impactful charts.
- `README.md`: Project documentation.

## Machine Learning Model
I implemented a **Random Forest Classifier** to predict at-risk customers.
- **Accuracy:** 79%
- **Top Predictors:** Total Charges, Tenure, Monthly Charges, and Contract Type.
- **Business Value:** The model allows the company to proactively target at-risk customers with specialized offers before they leave.

## Recommendations
1. **Incentivize Long-term Contracts:** Offer discounts to shift month-to-month customers to annual plans.
2. **First-Year Support:** Increase engagement and tech support outreach during the first 6 months of a customer's tenure.
3. **Value-Added Services:** Promote Online Security and Tech Support bundles, as customers with these features show higher loyalty.

**Author:** Komal Jaiswal  
