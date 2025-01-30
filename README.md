# Predicting_Car_Insurance_Claim_Results
Customer data cleaning and logistic regression for car insurance claim prediction.

## Project Description

Machine learning is widely used in the insurance market, which has long been recognized for its data-driven approach.
As part of this project for On the Road car insurance, customer data will be analyzed to identify the feature that produces the most accurate logistic regression model for predicting whether a claim will be made against a policy.

Insurance companies dedicate significant time and money to optimizing their pricing and accurately estimating the likelihood of claims being made by customers. In many countries, car insurance is legally required to drive a vehicle on public roads, making the market very large.

Given this, your services have been requested by On the Road car insurance to build a model for predicting whether a claim will be made during the policy period. As very little expertise and infrastructure exist for deploying and monitoring machine learning models within the company, you have been asked to identify the single feature that results in the best-performing model, measured by accuracy, so that a simple model can be introduced into production.

A CSV file named `car_insurance.csv`, containing customer data, has been provided along with a table detailing the column names and descriptions below.

## The dataset

| Column | Description |
|--------|-------------|
| `id` | Unique client identifier |
| `age` | Client's age: <br> <ul><li>`0`: 16-25</li><li>`1`: 26-39</li><li>`2`: 40-64</li><li>`3`: 65+</li></ul> |
| `gender` | Client's gender: <br> <ul><li>`0`: Female</li><li>`1`: Male</li></ul> |
| `driving_experience` | Years the client has been driving: <br> <ul><li>`0`: 0-9</li><li>`1`: 10-19</li><li>`2`: 20-29</li><li>`3`: 30+</li></ul> |
| `education` | Client's level of education: <br> <ul><li>`0`: No education</li><li>`1`: High school</li><li>`2`: University</li></ul> |
| `income` | Client's income level: <br> <ul><li>`0`: Poverty</li><li>`1`: Working class</li><li>`2`: Middle class</li><li>`3`: Upper class</li></ul> |
| `credit_score` | Client's credit score (between zero and one) |
| `vehicle_ownership` | Client's vehicle ownership status: <br><ul><li>`0`: Does not own their vehilce (paying off finance)</li><li>`1`: Owns their vehicle</li></ul> |
| `vehcile_year` | Year of vehicle registration: <br><ul><li>`0`: Before 2015</li><li>`1`: 2015 or later</li></ul> |
| `married` | Client's marital status: <br><ul><li>`0`: Not married</li><li>`1`: Married</li></ul> |
| `children` | Client's number of children |
| `postal_code` | Client's postal code | 
| `annual_mileage` | Number of miles driven by the client each year |
| `vehicle_type` | Type of car: <br> <ul><li>`0`: Sedan</li><li>`1`: Sports car</li></ul> |
| `speeding_violations` | Total number of speeding violations received by the client | 
| `duis` | Number of times the client has been caught driving under the influence of alcohol |
| `past_accidents` | Total number of previous accidents the client has been involved in |
| `outcome` | Whether the client made a claim on their car insurance (response variable): <br><ul><li>`0`: No claim</li><li>`1`: Made a claim</li></ul> |