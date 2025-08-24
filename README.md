📉 Telecom Customer Churn Prediction

This data science project focuses on predicting customer churn in a telecommunications company based on customer demographics, services subscribed, tenure, and billing details. By identifying factors that drive customer churn, the company can implement proactive retention strategies, reducing customer loss and improving long-term profitability.

📌 Project Overview

Churn refers to customers discontinuing the company’s services.

The goal of this project is to analyze patterns in customer behavior and build predictive models to classify whether a customer is likely to churn.

Insights derived from this analysis can guide targeted interventions, such as offering incentives or revising contract structures to retain high-risk customers.

🔎 Key Insights from EDA

Senior citizens have a lower churn rate compared to younger customers.

Customers who are single or without dependents tend to churn more.

Streaming services are linked with higher customer satisfaction and lower churn compared to online backup or device protection.

Tenure is inversely related to churn: customers with <5 months tenure are most likely to churn.

Contract type matters: Month-to-month customers churn more, while longer contracts reduce churn risk.

Customers with higher monthly charges but lower total charges are more likely to churn.

Most important features: Tenure, Contract type, Monthly charges, Total charges.

🤖 Machine Learning Models

The following models were tested:

Decision Tree Classifier 🌳

Random Forest Classifier 🌲

K Nearest Neighbors (KNN) 🤝

Best Model:

Random Forest Classifier

Accuracy: 82%

High F1 Score

Lowest Mean Squared Error (MSE) and Mean Absolute Error (MAE)

✅ Recommended model for churn prediction

⚙️ Tech Stack

Programming Language: Python 🐍

Libraries:

pandas, numpy → Data manipulation

matplotlib, seaborn → Data visualization

scikit-learn → Machine learning models & evaluation

imbalanced-learn → Handling class imbalance

📌 Future Enhancements

Deploy the churn prediction model using Streamlit/Flask/Django for real-time use.

Implement deep learning models (ANNs) to improve prediction accuracy.

Build a customer segmentation dashboard for better visualization and decision-making.

🙌 Acknowledgements

Dataset: Telecom Customer Churn Dataset

Inspiration: Reducing churn is one of the biggest challenges for subscription-based businesses.

📝 License

This project is licensed under the MIT License - see the LICENSE
 file for details.# Telecom-Customer-Churn-Prediction
