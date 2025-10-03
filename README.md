# telecom_cleaned
1.The TotalCharges column has been converted to numeric values and rows with missing values were checked and removed.

2.The customerID column was dropped as it does not provide predictive value.

3.All Yes/No columns ( Partner, Dependents, PaperlessBilling) were encoded into 1 (Yes) and 0 (No).

4.Columns such as Contract, PaymentMethod, and InternetService were transformed using one-hot encoding to create separate numeric columns for each category.

5.The target variable Churn was encoded as 0 = No and 1 = Yes.
