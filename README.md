# Streamify Churn Analysis: "Mailed Check" Payments are the Highest Risk
## Project Overview
This end-to-end data analytics project analyzes customer churn for Streamify, a fictional streaming service. The project involved data cleaning, exploratory data analysis (EDA), and predictive modeling in Python, culminating in an interactive dashboard in Power BI.

## Data Source
The original dataset was sourced from Kaggle. You can find it here: [Subscription Churn Dataset](https://www.kaggle.com/datasets/sameerhussain007/subscription-churn-dataset?resource=download)

## Key Findings & Dashboard
A brief video of the Power BI dashboard can be found in the `/dashboard_assets/` folder.
<img width="1482" height="832" alt="image" src="https://github.com/user-attachments/assets/fb41a553-0c5b-4556-97e0-e442d059d962" />


- **Basic Plan, Highest Churn:** The most affordable plan exhibits the highest churn rate, suggesting a potential mismatch between price and value perception for that segment.
- **Payment Method Risk:** Customers paying by 'Mailed check' are the most likely to churn, indicating a need to modernize payment options.
- **Price Sensitivity:** High monthly charges are a primary driver of churn, particularly for new customers who are more sensitive to initial costs.

## Methodology
1.  **Data Cleaning:** Addressed missing values and inconsistencies in the raw dataset to prepare it for analysis.
2.  **Exploratory Data Analysis (EDA):** Visualized data distributions and relationships to uncover initial insights and guide feature engineering.
3.  **Predictive Modeling:** Developed a Random Forest classifier combined with SMOTE to address class imbalance, improving recall from 17% to 33%.
4.  **Model Interpretation:** Used SHAP (SHapley Additive exPlanations) to interpret the model's predictions and confirm the key drivers of churn.

## Tools Used
- **Python:** Pandas, Scikit-learn, SHAP
- **Power BI:** For creating the interactive dashboard
- **Git:** For version control

## File Structure
- `/data`: Contains the cleaned CSV file.
- `/notebooks`: Holds the Jupyter Notebook with the Python code for analysis and modeling.
- `/dashboard_assets`: Contains the dashboard video.
