# Loan Interest Rates Prediction

Predicting personalized loan interest rates using data-driven insights from the Bondora P2P Loans dataset.


## Background

In the rapidly evolving fintech sector, efficient risk assessment and personalized loan offerings are crucial for enhancing customer satisfaction and maintaining profitability. This project entails analyzing peer-to-peer (P2P) loan data to identify the factors influencing loan interest rates and developing predictive models to inform loan term personalization.


## Objectives

1. **Import & preprocess** the Bondora P2P Loans dataset.
2. **Perform exploratory data analysis (EDA)** to uncover key customer and loan patterns.
3. **Visualize insights** to support decision-making and risk profiling.
4. **Develop predictive models** to estimate loan interest rates based on borrower characteristics using both simple and multiple linear regression models.


## Data

- **Source:** Bondora P2P Loans dataset (Kaggle): https://www.kaggle.com/datasets/marcobeyer/bondora-p2p-loans?select=LoanData.csv
- **Features:**
  | Feature                               | Description                                      |
  |---------------------------------------|--------------------------------------------------|
  | VerificationType                      | Loan application data verification method        |
  | Age                                   | Borrower's age in years                          |
  | AppliedAmount                         | Requested loan amount                            |
  | Amount                                | Approved loan amount                             |
  | Interest                              | Actual interest rate                             |
  | LoanDuration                          | Loan term duration                               |
  | Education                             | Education level                                  |
  | EmploymentDurationCurrentEmployer     | Duration with current employer                   |
  | HomeOwnershipType                     | Homeownership status                             |
  | IncomeTotal                           | Total borrower income                            |
  | ExistingLiabilities                   | Number of existing liabilities                   |
  | RefinanceLiabilities                  | Total liabilities post-refinancing               |
  | Rating                                | Bondora's internal borrower rating               |
  | NoOfPreviousLoansBeforeLoan           | Number of prior loans                            |
  | AmountOfPreviousLoansBeforeLoan       | Value of previous loans                          |


## Environment Setup

To reproduce this project locally:

```bash
git clone https://github.com/shahab-ghafoor/Loan-Interest-Rates.git
cd Loan-Interest-Rates
