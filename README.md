# Credit Risk Assessment System
This project develops a machine learning model to predict the likelihood of loan default using applicant financial and demographic data. The goal is to support data-driven loan approval decisions and reduce financial risk.

## Business Problem

Financial institutions face significant losses due to loan defaults. Identifying high-risk applicants before loan approval is critical to minimizing risk and improving portfolio performance.

## Dataset

The dataset contains information on loan applicants, including:
- Demographics (Gender, Dependents, Education)
- Financial details (Income, Loan Amount)
- Credit history

Target variable:
- Loan_Status (Approved / Rejected)

## Methodology

1. Data Cleaning
   - Handled missing values using mode and median imputation

2. Feature Engineering
   - Converted categorical variables into numerical format
   - Created consistent numerical representations

3. Exploratory Data Analysis
   - Identified key relationships between features and loan approval
   - Found credit history to be the strongest predictor

4. Model Building
   - Trained Logistic Regression and Random Forest models

5. Model Evaluation
   - Used precision, recall, and F1-score
   - Addressed class imbalance using class weighting

## Results

- Logistic Regression (with class balancing) performed better in identifying high-risk applicants
- Credit History showed the strongest influence on loan approval decisions
- Income had a moderate impact but was less significant than credit behavior

## Key Insights

- Applicants with poor credit history are significantly more likely to be rejected
- Credit behavior is more important than income in determining loan approval
- Models without class balancing tend to favor approving applicants, increasing financial risk

## Business Impact

This model can help financial institutions reduce loan default risk by:
- Identifying high-risk applicants early
- Supporting data-driven loan approval decisions
- Improving overall loan portfolio quality

## Tools & Technologies

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib / Seaborn

