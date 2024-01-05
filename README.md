## Project Description
We express concerns regarding the potential delay in credit card payments at FinanKu, which could adversely affect our business. To address this situation, we aim to build a predictive model capable of accurately predicting at least 60% of customers who are likely to experience credit card payment delays.

## Available Variables
- **Customer ID:** Unique customer identifier
- **Branch:** Customer's branch location
- **City:** Customer's city location
- **Age:** Customer's age during the observation period
- **Avg. Annual Income/Month:** Average customer income per year
- **Balance (Q1-Q4):** End-of-quarter balance for customers
- **Num of Products (Q1-Q4):** Number of products owned by the customer at the end of each quarter
- **HasCrCard (Q1-Q4):** Status of the customer's credit card ownership at the end of each quarter
- **Active Member (Q1-Q4):** Customer's active status
- **Unpaid Tagging:** Customer's failure-to-pay status

## Experiments
- Review period: Customers are reviewed over the past year or the last 6 months.
- Variable adjustments: Include balance from the average during the time horizon and changes at the end and beginning of the review, number of products from the average, maximum, and minimum during the review period, and customer activity status in months.

## Objectives
Develop a predictive model with a minimum accuracy and recall rate of 60% to identify customers likely to experience credit card payment delays.

## Usage Instructions
1. Clone this repository.
2. Ensure you have all the required dependencies.
3. Run the notebook or script to view results and predictions.
4. Adjust parameters as needed.

## Notes
Be sure to read the documentation and references included in the notebook or script for better understanding. Feel free to provide feedback or report any issues you may encounter. Thank you for your participation!
