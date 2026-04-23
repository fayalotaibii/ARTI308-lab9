# ARTI308-lab9

# Lending Club Loan Default Prediction 

This machine learning project predicts whether a borrower will pay back their loan in full using historical financial data (2007-2010) from LendingClub.com. It compares the predictive performance of a single **Decision Tree** against an ensemble **Random Forest** classifier.

## Tech Stack
* **Python** (Pandas, NumPy)
* **Scikit-Learn** (Modeling & Evaluation)
* **Matplotlib & Seaborn** (Data Visualization)

## Results
The Random Forest model (`n_estimators=600`) outperformed the single Decision Tree, providing a more balanced and robust performance when predicting the minority class (loan defaults) without overfitting.

