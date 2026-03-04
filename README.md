# Customer Churn Intelligence System

### Customer Churn Prediction & Retention Intelligence System
End-to-End Machine Learning with Business Impact Analysis

### 1. About the Project 
This project presents an end-to-end Customer Churn Intelligence System developed to predict telecom customer churn and generate actionable business insights. Customer churn directly affects company revenue, making early identification of at-risk customers essential for sustainable growth.

The system combines exploratory data analysis, feature engineering, multiple machine learning models, and financial impact simulation to not only predict churn but also translate technical outputs into strategic retention recommendations. The objective is to demonstrate how machine learning can support real-world business decision-making.


---


### 2. Tech Stack and Skills Used 

The system was developed using the following technologies:

- **Python** – Core programming and analysis
- **Pandas & NumPy** – Data manipulation and numerical analysis
- **Matplotlib & Seaborn** – Data visualization and trend analysis
- **Scikit-learn** – Model building, evaluation, and preprocessing
- **XGBoost** – Gradient boosting model for improved performance
- **Feature Engineering** – Behavioral and financial feature creation
- **Model Evaluation Metrics** – Accuracy, Precision, Recall, ROC-AUC
- **Business Analytics** – Revenue impact simulation and retention strategy modeling


---


### 3. Data Source 
The dataset is based on a publicly available Telecom Customer Churn dataset commonly used for predictive analytics tasks.

**It includes customer-level information such as :**
'CustomerID', 'Gender', 'Tenure', 'Contract Type', 'Payment Method', 'Internet Service', 'Monthly Charges', 'Total Charges' and 'Churn Status'.

The dataset enables behavioral, financial, and demographic analysis for churn prediction 
modeling.


---


### 4. Highlights of the Project
- Conducted comprehensive exploratory data analysis to identify churn patterns.
- Engineered additional features such as service usage count and tenure segmentation.
- Built and compared multiple models including Logistic Regression, Random Forest, and XGBoost.
- Evaluated models using cross-validation and ROC-AUC metrics.
- Identified top churn drivers influencing customer exit behavior.
- Simulated financial impact of retention campaigns using projected revenue loss estimates.
- Structured the project as a complete end-to-end ML workflow from raw data to business strategy.



---


### 5. Key Insights of the Project
- Customers on month-to-month contracts showed significantly higher churn rates.
- Lower tenure customers were more likely to churn.
- Higher monthly charges increased churn probability.
- Customers using fewer services demonstrated higher churn risk.
- Contract duration and engagement level were strong predictive indicators.

Best Model : Random Forest / XGBoost  
Accuracy : 84%  
Precision & Recall optimized for business retention strategy.


---


### 6. Business Impact
- Enabled early identification of high-risk customers for targeted retention campaigns.
- Estimated potential revenue savings through proactive retention strategies.
- Provided actionable recommendations for contract restructuring and loyalty incentives.
- Demonstrated how predictive analytics can reduce churn-related financial loss.


---


### 7. Screenshots

INSIGHT TO SOME OF THE PROJECT OUTPUTS WE ACHIEVED :

## Count




![Count](https://github.com/sinharitamvaraa/customer-churn-intelligence-system/blob/main/count.jpg.jpeg)


## Churn Distribution & Monthly Charges Analysis
This visualization highlights the distribution of churned vs retained customers and compares monthly charge patterns across both groups.

- The dataset shows class imbalance, with more retained customers than churned customers.
- Customers who churn exhibit a higher median monthly charge.
- Higher billing amounts are associated with increased churn probability, indicating potential price sensitivity.

High-paying customers represent elevated revenue risk. Pricing optimization and value-added incentives may reduce churn within this segment.

![Churn vs Monthly Charges](https://github.com/sinharitamvaraa/customer-churn-intelligence-system/blob/main/monthlycharges.jpg.jpeg)

## Tenure vs Churn Behavior Analysis
This boxplot compares customer tenure between churned and retained users to understand lifecycle-based churn behavior.

- Customers with low tenure are significantly more likely to churn.
- Long-term customers demonstrate strong retention stability.
- Early customer lifecycle stages are the most vulnerable period.

Retention strategies should focus heavily on onboarding and early engagement programs to prevent initial drop-off.

![Retention by Tenure Segment](https://github.com/sinharitamvaraa/customer-churn-intelligence-system/blob/main/tenure.jpg.jpeg)

## ROC Curve 
The ROC Curve evaluates the classification performance of the Random Forest model across different probability thresholds.

- The curve demonstrates strong separation from the baseline (random classifier).
- High true positive rate across thresholds indicates reliable churn detection.
- The model effectively balances sensitivity and specificity.

The model can confidently identify high-risk customers, enabling targeted retention efforts with optimized precision–recall trade-offs.

![Model Performance Evaluation](https://github.com/sinharitamvaraa/customer-churn-intelligence-system/blob/main/roc.jpg.jpeg)

## SHAP



![Shap](https://github.com/sinharitamvaraa/customer-churn-intelligence-system/blob/main/shap.jpg.jpeg)



This project demonstrates both technical ML capability and business decision-making intelligence.
