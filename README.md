# Statute Barred Status Predictor
## Project Overview
The "Statute Barred Status Predictor" project aims to develop a sophisticated machine-learning model to predict the probability of successfully collecting debts by examining the statute-barred status of each account. Using a dataset with various attributes related to debt accounts, the model will help identify accounts that may be statute-barred and thus potentially unrecoverable.
## Problem Statement
In debt collection, determining which accounts are statute-barred—and thus potentially unrecoverable—is crucial. This project focuses on creating a predictive model to identify such accounts using the IsStatBarred field as the target variable.
## Data Dictionary:
* EntityID: Unique identifier for each entry.
* OriginalCreditor[Redacted]: Name of the original creditor, with sensitive information redacted.
* AccountID: Unique identifier for the account.
* CurrentBalance: The current balance of the account.
* DebtLoadPrincipal: The principal amount of the debt load.
* BalanceAtDebtLoad: The balance at the time of debt load.
* PurchasePrice: The price at which the debt was purchased.
* ProductOrDebtType: Type of product or debt.
* CollectionStatus: Status of the debt collection.
* IsStatBarred: Indicates if the debt is statute-barred (target variable).
* CloseDate: The date when the account was closed.
* ClosureReason: Reason for closing the account.
* InBankruptcy: Indicates if the account is involved in bankruptcy.
* AccountInsolvencyType: Type of insolvency related to the account.
* CustomerInsolvencyType: Type of insolvency related to the customer.
* IsLegal: Indicates if legal action has been taken.
* InterestRate: Interest rate associated with the debt.
* LastPaymentAmount: Amount of the last payment made.
* LastPaymentMethod: Method used for the last payment.
* NumLiableParties: Number of liable parties associated with the account.
* CustomerAge: Age of the customer.
* NumPhones: Number of phone contacts associated with the customer.
* NumEmails: Number of email contacts associated with the customer.
* NumAddresses: Number of addresses associated with the customer.
## Data Structure
* Rows: 406,424
* Columns: 24
## Data Preparation
* Clean the Data: Handle missing values and ensure data is in a usable format for analysis.
* Verify Data Types: Ensure each attribute has the correct data type.
## Feature Selection
* Review attributes and select the most relevant ones.
* Create new features by converting categorical variables into numerical representations using techniques like One-Hot Encoding.
## Data Splitting
* Training Set: 80% of the data (325,138 rows).
* Testing Set: 20% of the data (81,285 rows).
