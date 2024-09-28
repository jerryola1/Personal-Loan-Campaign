# Personal Loan Campaign Project

## Description

AllLife Bank, a US-based bank with a growing customer base, aims to expand its loan business by converting liability customers (depositors) into personal loan customers. This project involves building a predictive model to identify potential customers with a higher probability of purchasing personal loans.

## Background and Context

- AllLife Bank has a large base of liability customers with varying deposit sizes.
- The bank wants to increase its loan business and earn more through interest on loans.
- A previous campaign showed a 9% success rate, encouraging the marketing department to improve target marketing.

## Objective

1. Predict whether a liability customer will buy a personal loan or not.
2. Identify the most significant variables influencing loan purchases.
3. Determine which customer segments should be targeted more.

## Project Overview

This project uses machine learning techniques to analyze customer data and build predictive models. The main steps include:

1. Data Exploration and Preprocessing
2. Feature Engineering
3. Model Building and Evaluation
   - Decision Tree
   - Random Forest
   - Gradient Boosting
4. Hyperparameter Tuning
5. Feature Importance Analysis

## Key Findings

- The most important features for predicting personal loan purchases are:
  - Income
  - Education
  - Family size
  - Average credit card spending (CCAvg)

- The Gradient Boosting model, after hyperparameter tuning, achieved the best performance with:
  - 96.7% accuracy
  - 100% precision in identifying potential loan customers

## Recommendations

1. Focus marketing efforts on customers with higher income levels.
2. Consider educational background when targeting potential loan customers.
3. Analyze family size and average credit card spending as additional indicators of loan propensity.
4. Utilize the Gradient Boosting model for predicting potential loan customers, as it showed the highest precision.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## How to Use

1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook "Personal Loan Campaign Projects.ipynb"`

## Contributors

Abayomi Olagunju

## License

MIT License
