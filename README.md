# Customer Churn Analysis with Survival Models

## Overview
This project applies survival analysis models to predict customer churn in the telecom industry. Using customer-level data, we explore factors affecting churn and estimate the probability of customers leaving the company. Key models used include the **Kaplan-Meier survival model** and the **Cox proportional hazards model**.

## Dataset
The dataset includes various customer characteristics:

- **customerID**: Unique customer identifier
- **gender**: Customer's gender
- **SeniorCitizen**: Whether the customer is a senior citizen
- **Partner**: Whether the customer has a partner
- **Dependents**: Whether the customer has dependents
- **tenure**: Duration the customer has been with the company
- **PhoneService**: Whether the customer has phone service
- **MultipleLines**: Whether the customer has multiple lines
- **InternetService**: Type of internet service (DSL, fiber optic, none)
- **OnlineSecurity**: Whether the customer uses online security
- **OnlineBackup**: Whether the customer uses online backup
- **DeviceProtection**: Whether the customer has device protection
- **TechSupport**: Whether the customer uses tech support
- **StreamingTV**: Whether the customer streams TV
- **StreamingMovies**: Whether the customer streams movies
- **Contract**: Type of contract (month-to-month, one-year, two-year)
- **PaperlessBilling**: Whether the customer uses paperless billing
- **PaymentMethod**: Payment method for services
- **MonthlyCharges**: Monthly charge
- **TotalCharges**: Total charge for the quarter
- **Churn**: Whether the customer has left the company

## Methodology
In this analysis, we use survival analysis to model customer churn:

- **Kaplan-Meier Survival Model**: Estimates the probability of survival (remaining with the company) over time.
- **Cox Proportional Hazards Model**: Assesses the relationship between customer features and the likelihood of churn, accounting for the effects of different variables on the risk of leaving.

## Installation & Usage
1. Download the data.
2. Clone this repository to your local machine.
3. Load the dataset and run the analysis using R.
4. Interpret the results from the Kaplan-Meier and Cox models.

## Tools & Libraries
- **R**: Used for statistical analysis and model implementation.
- **survival**: R package for survival analysis.

## Results
The models provide insights into factors affecting customer churn, including tenure, contract type, and monthly charges. Key survival curves and hazard ratios are presented for further interpretation.

## License
This project is open-source under the [MIT License](LICENSE).
