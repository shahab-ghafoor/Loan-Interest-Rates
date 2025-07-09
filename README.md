# Loan Interest Rates Prediction

Predicting personalized loan interest rates using data-driven insights from the Bondora P2P Loans dataset.


## Background

In the rapidly evolving fintech sector, efficient risk assessment and personalized loan offerings are essential for enhancing customer satisfaction and maintaining profitability. This project, as part of a capstone exercise, involves analyzing peer-to-peer loan data to understand the factors influencing loan interest rates and building predictive models to guide loan term personalization.


## Objectives

1. **Import & preprocess** the Bondora P2P Loans dataset.
2. **Perform exploratory data analysis (EDA)** to uncover key customer and loan patterns.
3. **Visualize insights** to support decision-making and risk profiling.
4. **Develop predictive models** to estimate loan interest rates based on borrower characteristics.


## Data

- **Source:** Bondora P2P Loans (Provided within the course environment)
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
git clone https://github.com/yourusername/Loan-Interest-Rates.git
cd Loan-Interest-Rates
