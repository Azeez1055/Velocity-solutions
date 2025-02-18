# Churn Analysis Project for Velocity Retail Solutions

## 1. Project Overview

This project analyzes customer churn data for Velocity Retail Solutions, a provider of data analytics services to retailers. The objective is to identify the key drivers of churn and develop actionable recommendations to improve customer retention. The analysis utilizes machine learning and Explainable AI (XAI) techniques to provide data-driven insights and recommendations for improving customer retention.

## 2. Problem Statement

Customer churn is a significant challenge for Velocity Retail Solutions. A recent increase in churn (8% in the last quarter, costing an estimated \$500,000 annually) has prompted the need to understand the factors driving customer attrition and develop effective retention strategies.

## 3. Methodology

This project follows these key steps:

1.  **Data Acquisition:** The dataset used in this project contains historical customer data from Velocity Retail Solutions. Key data elements include retailer demographics, contract information, platform usage, support interactions, data integration issues, and churn status.

2.  **Data Cleaning and Preprocessing (Python):**
    *   Handled missing values using median imputation.
    *   Encoded categorical variables using one-hot encoding.
    *   Scaled numerical variables using standardization.

3.  **Exploratory Data Analysis (EDA) (Python):**
    *   Performed univariate analysis to understand the distribution of individual variables.
    *   Conducted bivariate analysis to explore relationships between variables, especially the relationship between each variable and customer churn.
    *   Analyzed the correlation between numerical features.

4.  **Model Selection and Training (Python):**
    *   Selected a Logistic Regression model due to its balance of accuracy, interpretability, and efficiency.
    *   Split the data into training (80%) and testing (20%) sets.
    *   Trained the Logistic Regression model on the training data.

5.  **Model Evaluation (Python):**
    *   Evaluated the model's performance on the test data using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.

6.  **Explainable AI (XAI) with SHAP (Python):**
    *   Utilized SHAP (Shapley Additive explanations) values to understand the contribution of each feature to individual churn predictions.
    *   Created SHAP summary plots to visualize feature importance and impact.

7.  **Power BI Integration (Dashboard):**
    *   Created an interactive Power BI dashboard to visualize churn rates, key drivers of churn, and at-risk customers.
    *   Implemented slicers for filtering and drill-down capabilities.

## 4. Key Findings and Insights

*   **Low platform usage hours** are a strong predictor of churn. Retailers who use the Velocity Retail Solutions platform less frequently are more likely to churn.
*   **Data integration issues** are a significant churn driver. Retailers who experience more data integration issues are at higher risk of churning.
*   **Shorter contract tenures** are associated with higher churn rates. Retailers with shorter contracts are more likely to churn.
*   **Certain customer segments** (e.g., specific industries, retailers with a small number of stores) exhibit higher churn rates.

## 5. Actionable Recommendations

Based on the analysis, the following actions are recommended to reduce customer churn at Velocity Retail Solutions:

1.  **Proactive Engagement Program:** Implement a proactive engagement program targeting retailers with low platform usage hours. Provide personalized training, dedicated support, and regular check-in calls.

2.  **Streamlined Data Integration:** Improve the data integration process to minimize issues for new and existing customers. Develop more intuitive documentation, provide dedicated onboarding support, and implement automated data quality checks.

3.  **Targeted Retention Campaigns:** Develop targeted retention campaigns for customers with contracts nearing expiration. Offer special promotions, discounts, or customized service packages to incentivize renewal.

4.  **Enhanced Customer Support:** Invest in training and resources to enhance customer support capabilities. Focus on resolving data integration issues promptly and providing proactive assistance to help retailers get the most out of the platform.

## 6. Code and Data

*   **Python Code:** The Python code for data cleaning, analysis, modeling, and XAI is located in the `churn_analysis.py` file.

*   **Data:** The dataset used in this project is available [the data is available in CSV format.]. The dataset includes [customer_id,retailer_name,retailer_industry,num_stores,avg_monthly_revenue,contract_value,contract_tenure_months,platform_usage_hours,support_tickets_opened,data_integration_issues,churn
].

## 7. How to View the Analysis Results (Python Visualizations)

To view the analysis results, including the generated plots, follow these steps:

1.  **Install GitHub to Colab extension:** Go to the chrome extension store and select the following chrome extension to install the github to colab: [Github to Colab](https://chrome.google.com/webstore/detail/githubtocolab/amgpgjjokjmgbamipkognjkndhaandck?hl=en).

2.  **Clone the Repository** After installing Github to Colab, clone this repository to your local machine.

3.  **Open in Google Colab:**
    *   Launch Google Colab: [https://colab.research.google.com/](https://colab.research.google.com/)
    *   Click “Upload”
    *   Choose the `churn_analysis.py` file from your local machine.
    * Run all cells.
    * Google Colab will automatically detect that plots must be displayed.

4.  **Install Required Libraries:** If you encounter any missing library errors, run the following commands in a Colab cell to install the required libraries:

    ```bash
    !pip install pandas matplotlib seaborn scikit-learn shap
    ```

5.  **Run the Code:** Execute the Python code in the Colab notebook. The code will generate the plots and display them in the notebook output.

## 8. Power BI Dashboard

An interactive Power BI dashboard showcasing churn rates, key drivers of churn, and at-risk customers has been created.



**Note:** Due to data privacy restrictions, the actual Power BI data model cannot be shared. However, you can recreate the dashboard using the provided dataset and the insights from this analysis.

## 9. License

This project is licensed under the terms that all rights are reserved for Azeez at inspireanalytics865@gmail.com

## 10. Contact

Azeez
inspireanalytics865@gmail.com

