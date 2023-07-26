# Data_Science_Post

The loan approval dataset is a collection of financial records and associated information used to determine the eligibility of individuals or organizations for obtaining loans from a lending institution. it contains serveral parameters such as cibil score, income, employment status, loan term, loan amount, assets value, and loan status.


Many libraries have been used  such as matplotlib, seaborn, pandas, and scikit-learn for data visualization, data preprocessing, and model training. 


# Dataset Description

    loan_id: A unique identifier for each loan application.
    no_of_dependents: The number of dependents of the applicant.
    education: The education level of the applicant (Graduate / Not Graduate).
    self_employed: Whether the applicant is self-employed or not.
    income_annum: The annual income of the applicant.
    loan_amount: The amount of loan applied for.
    loan_term: The term of the loan in months.
    cibil_score: The CIBIL score of the applicant (a measure of creditworthiness in India).
    residential_assets_value: The value of the applicant's residential assets.
    commercial_assets_value: The value of the applicant's commercial assets.
    luxury_assets_value: The value of the applicant's luxury assets.
    bank_asset_value: The value of the applicant's assets held in banks.
    loan_status: The status of the loan application (Approved / Rejected).
    

# Question 
Using this dataset we try to answer to get some insigth 
1. How education level contribute to get approved for loan
   The number of graduates is slightly higher than the number of non-graduates among the loan applicants. The loan approval rate seems to be slightly higher for graduates than for non-graduates.
2. How CIBIL Score
   Most of the applicants have very poor credit CIBIL score. It appears that loans are more likely to be approved for applicants with higher CIBIL scores. The distribution of rejected loans tends to skew towards lower CIBIL scores, while the distribution of approved loans is more evenly spread and has a slight skew towards higher CIBIL scores.
3. Do people with higher income have better CIBIL score and more likely to get approved for loan ?
 Income alone cannot predict loan approval. The median income of approved loans seems to be slightly higher than the median income of rejected loans.

The goal is to predict loan approval status using different classifiers and evaluate their performance using accuracy and classification reports

# Summary of the result 
https://medium.com/@francoismertil/exploring-loan-approval-predictions-cd89b81176fe


# Acknowledgements
This data has been downloaded from Kaggle
https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset
