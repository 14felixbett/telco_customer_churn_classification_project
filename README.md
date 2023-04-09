# Classification Project: Predicting Customer Churn in Telco Company

This is a classification project in which we aim to predict whether a customer will churn or not for a telecommunications company. We will be using the `Telco-customer-churn.csv` dataset that contains information about customers of the company, such as demographics, usage patterns, and account information.

## Dataset
The dataset contains 7043 rows and 21 columns. Each row represents a unique customer and each column contains customer attributes such as:

- **customerID:** unique identifier for the customer
- **gender:** customer gender (male/female)
- **SeniorCitizen:** binary value indicating if the customer is a senior citizen or not (1/0)
- **Partner:** binary value indicating if the customer has a partner or not (Yes/No)
- **Dependents:** binary value indicating if the customer has dependents or not (Yes/No)
- **tenure:** number of months the customer has stayed with the company
- **PhoneService:** binary value indicating if the customer has a phone service or not (Yes/No)
- **MultipleLines:** binary value indicating if the customer has multiple lines or not (Yes/No)
- **InternetService:** customer's internet service provider (DSL/Fiber optic/No)
- **OnlineSecurity:** binary value indicating if the customer has online security or not (Yes/No)
- **OnlineBackup:** binary value indicating if the customer has online backup or not (Yes/No)
- **DeviceProtection:** binary value indicating if the customer has device protection or not (Yes/No)
- **TechSupport:** binary value indicating if the customer has tech support or not (Yes/No)
- **StreamingTV:** binary value indicating if the customer has streaming TV or not (Yes/No)
- **StreamingMovies:** binary value indicating if the customer has streaming movies or not (Yes/No)
- **Contract:** customer's contract type (Month-to-month/One year/Two year)
- **PaperlessBilling:** binary value indicating if the customer has paperless billing or not (Yes/No)
- **PaymentMethod:** customer's payment method (Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic))
- **MonthlyCharges:** amount charged to the customer monthly
- **TotalCharges:** total amount charged to the customer

### Goal

Our goal is to build a classification model to predict customer churn. The target variable Churn is binary (Yes/No) and indicates if the customer has churned or not.

### Approach

We will follow the standard data science workflow, including:

1. Exploratory data analysis (EDA) to gain insights into the dataset and identify any patterns or relationships between variables.
2. Preprocessing the data by handling missing values, encoding categorical variables, and scaling numerical variables.
3. Splitting the dataset into training and testing sets.
4. Training various classification models and selecting the best performing model.
5. Evaluating the performance of the selected model on the test set.

### Dependencies

We will be using the following Python libraries for this project:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### Files
- `telco_customer_churn_classification.ipynb`: Jupyter notebook containing the code for the project.
- `Telco-customer-churn.csv`: Dataset used in the project.

## Conclusion
By the end of this project, we aim to have a well-performing classification model that can predict customer churn accurately. This model can then be used by the company to identify customers who are at risk of churning and take appropriate actions to retain them.
