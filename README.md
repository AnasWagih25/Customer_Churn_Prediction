# Customer Churn Prediction

## Project Overview
This project implements a **Customer Churn Prediction** model using **Decision Trees, Random Forest, and XGBoost**. It predicts whether a customer will churn based on various features such as contract type, monthly charges, and tenure.

## Dataset
The project uses the **Telco Customer Churn** dataset, which contains customer demographics, account details, and service usage information.

### Dataset Features
- **customerID**: Unique identifier for each customer (removed during preprocessing)
- **gender**: Male/Female
- **SeniorCitizen**: Indicates if the customer is a senior citizen (0 or 1)
- **Partner**: Whether the customer has a partner
- **Dependents**: Whether the customer has dependents
- **tenure**: Number of months the customer has stayed with the company
- **PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, etc.**: Various service features
- **Contract**: Type of contract (Month-to-month, One year, Two year)
- **PaymentMethod**: Billing method (e.g., Electronic check, Bank transfer)
- **MonthlyCharges, TotalCharges**: Charges incurred by the customer
- **Churn**: Target variable (Yes/No) indicating if the customer left

## Installation and Setup
### Prerequisites
Ensure you have **Python 3.8+** and install the required dependencies:
```bash
pip install pandas numpy scikit-learn xgboost
```

### Running the Script
1. Place the **`telco_customer_churn.csv`** dataset in the same directory.
2. Run the script:
```bash
python customer_churn.py
```

## Model Training
The script trains three machine learning models:
1. **Decision Tree Classifier**
2. **Random Forest Classifier**
3. **XGBoost Classifier**

Each model is trained on a processed dataset and evaluated using **accuracy, classification report, and confusion matrix**.

## Predicting Churn for a Specific Customer
The script includes a feature to predict churn for a specific customer. Modify the `customer_data` dictionary in the script to input new customer details, and the model will predict if the customer is likely to churn.
## License
This project is licensed under the MIT License - see the LICENSE file for details.This project is licensed under the MIT License - see the LICENSE file for details.

## License
This project is open-source and available for educational purposes.

