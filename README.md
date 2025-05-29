# Vehicle-Insurance-Claim-Fraud-Detection-Dashboard
This repository contains a Power BI dashboard project that analyzes and detects fraudulent vehicle insurance claims. Using historical claim data, it provides insights into fraud patterns based on customer demographics, vehicle type, policy details, and more.

- Dashboard Overview
The Power BI report enables stakeholders to:

Understand the distribution of fraudulent claims

Identify fraud-prone demographics and vehicle types

Monitor fraud rates across policies and age groups

Use slicers to filter by sex, marital status, vehicle age, and more

- Dataset Details
File Name: fraud_oracle.csv

Total Records: ~15,000 insurance claims

Target Variable: FraudFound_P (1 = Fraud, 0 = Not Fraud)

Key Features:

Customer: Sex, Age, Marital Status

Vehicle: VehicleCategory, VehiclePrice, AgeOfVehicle

Policy: PolicyType, AgeOfPolicyHolder

Claim Information: Make, Claim Amount

- Key Metrics
Metric	Value
Total Claims	15,000
Fraudulent Claims	923
Overall Fraud Rate	5.99%

-> Visual Highlights
- Fraud Analysis by Category
Fraud by Gender:

Male: 88.62% of frauds

Female: 11.38%

Fraud by Marital Status:

Highest fraud rate seen in Divorced and Single individuals

Fraud by Age Group:

Age 31 to 35 has the highest fraud count (360 cases)

- Vehicle & Policy Insights
Top 5 Fraud-Prone Vehicle Makes:

Ford, Toyota, Honda, etc.

Fraud by Policy Type:

Highest: Sport - Collision (13.79%)

Lowest: Sedan - Liability (6.88%)

Fraud by Vehicle Age & Price:

Newer and lower-priced vehicles show higher fraud densities

- Insights
Males in the 31–35 age bracket commit more fraud

Sport and utility vehicles are more fraud-prone than sedans

Collision policies have a higher fraud rate than liability or all-perils

Cheaper and newer vehicles tend to be involved in more fraud cases

- Tools & Technologies
Power BI Desktop for dashboard design

CSV (fraud_oracle.csv) for data source

DAX for measures like fraud rate and custom filters

Interactive slicers for real-time segmentation

- How to Use
Clone/download the repository

Open the Power BI .pbix file (if provided)

Load the dataset fraud_oracle.csv

Interact with filters: Sex, Age Group, Vehicle Price, etc.

- Use Cases
Insurance fraud analytics

Policy risk assessment

Customer segmentation for investigation

Fraud detection model development (future extension)
