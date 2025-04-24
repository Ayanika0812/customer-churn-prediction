# customer-churn-prediction

## Project Overview
The objective of this project is to predict whether a customer will discontinue a subscription-based service (i.e., churn). Using historical customer data, we analyze various factors such as usage patterns, demographic details, and subscription duration to build a predictive model. The goal is to develop a machine learning model that effectively identifies customers likely to churn and provides insights into the key factors contributing to churn.

## Task Objectives
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
- **Model Training**: Implementing multiple machine learning algorithms, including Logistic Regression, Random Forest, Gradient Boosting, and XGBoost to predict customer churn.
- **Model Evaluation**: Evaluating model performance using accuracy, ROC AUC score, and classification metrics.
- **Insights**: Analyzing feature importance to understand which factors contribute most to customer churn.

## Dataset
The dataset used for this project is `Churn_Modelling.csv`, which contains customer data with various features like demographics, account information, and usage details.

### Data Features
- `Geography`: Customer's location (encoded as a categorical variable).
- `Gender`: Customer's gender (encoded as a binary variable).
- `Age`: Age of the customer.
- `Tenure`: Number of years the customer has been with the service.
- `Balance`: Customer's account balance.
- `NumOfProducts`: Number of products the customer is using.
- `HasCrCard`: Whether the customer has a credit card (binary).
- `IsActiveMember`: Whether the customer is an active member (binary).
- `EstimatedSalary`: Estimated annual salary of the customer.
- `Exited`: Target variable, indicating whether the customer churned (1) or stayed (0).

## Steps to Run the Project

### 1. **Clone the Repository**
   To clone this repository to your local machine, run:
   ```bash
   git clone https://github.com/Ayanika0812/customer-churn-prediction.git
