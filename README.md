# 📊 Loan Default Statistical Analysis

## 📌 Project Overview

This project performs statistical and probability analysis on a loan
application dataset using Python.

The objective of this project is to analyze customer financial data and
understand loan default behavior using statistical techniques,
probability calculations, visualization, and linear algebra operations.

The project consists of:

-   **Part A --- Theory Concepts**
-   **Part B --- Python Implementation**

------------------------------------------------------------------------

# 📁 Dataset Information

Dataset file used:

`loan_applications.csv`

## Columns in Dataset:

-   Customer_ID --- Unique customer ID\
-   Age --- Customer age\
-   Income --- Monthly income\
-   Loan_Amount --- Loan amount taken\
-   Credit_Score --- Credit score value\
-   Loan_Term --- Loan duration\
-   Default_Status --- Loan default status (Yes/No)

------------------------------------------------------------------------

# 🧮 Part A --- Theory Concepts

The following statistical concepts are explained:

1.  Mean, Median and Mode\
2.  Variance and Standard Deviation\
3.  Random Variable\
4.  Conditional Probability\
5.  Bayes Theorem\
6.  Empirical vs Theoretical Probability\
7.  Poisson Distribution\
8.  Eigenvalues and Eigenvectors

Each topic includes:

-   Definition\
-   Formula\
-   Example\
-   Application

------------------------------------------------------------------------

# 🧑‍💻 Part B --- Python Implementation Steps

## Step 1 --- Import Libraries

Libraries used:

-   pandas\
-   numpy\
-   matplotlib\
-   seaborn\
-   scipy

These libraries are used for data handling, calculations, visualization
and statistical analysis.

------------------------------------------------------------------------

## Step 2 --- Load Dataset

Dataset is loaded using:

`pd.read_csv()`

First five records are displayed using:

`df.head()`

------------------------------------------------------------------------

## Step 3 --- Central Tendency

Calculated:

-   Mean\
-   Median\
-   Mode

Purpose:

To find typical income value of customers.

------------------------------------------------------------------------

## Step 4 --- Dispersion Measures

Calculated:

-   Range\
-   Variance\
-   Standard Deviation

Purpose:

To measure variation in loan amounts.

------------------------------------------------------------------------

## Step 5 --- Default Probability

Calculated:

Probability of loan default.

Purpose:

To determine proportion of customers who defaulted.

------------------------------------------------------------------------

## Step 6 --- Contingency Table

Created comparison between:

-   Default Status\
-   Credit Score Categories

Purpose:

To analyze relationship between credit score and default.

------------------------------------------------------------------------

## Step 7 --- Conditional Probability

Calculated:

P(Default \| Credit Score \< 600)

Purpose:

To identify high-risk customers.

------------------------------------------------------------------------

## Step 8 --- Visualization

Generated:

-   Histogram\
-   KDE Curve

Purpose:

To visualize distribution of credit scores.

------------------------------------------------------------------------

## Step 9 --- Skewness and Kurtosis

Calculated:

-   Skewness\
-   Kurtosis

Purpose:

To understand distribution shape.

------------------------------------------------------------------------

## Step 10 --- Q-Q Plot

Generated Q-Q plot to check normal distribution.

------------------------------------------------------------------------

## Step 11 --- Linear Algebra

Performed:

-   Dot Product\
-   Vector Norm\
-   Angle Calculation

Purpose:

To measure similarity between customer vectors.

------------------------------------------------------------------------

# 📊 Key Insights

1.  Customers with low credit scores show higher default probability.
2.  Loan amount distribution shows variation across customers.
3.  Credit score distribution follows near-normal pattern.
4.  Higher income customers generally take higher loan amounts.
5.  Default risk increases when credit score decreases.

------------------------------------------------------------------------

# 🛠 Tools Used

-   Python\
-   Jupyter Notebook\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   SciPy

------------------------------------------------------------------------

# 📂 Project Structure

loan-default-analysis/

├── Part_A_Detailed_Final.pdf\
├── Part_B_Final_Explained.ipynb\
├── loan_applications.csv\
├── README.md

------------------------------------------------------------------------

# ▶️ How to Run

1.  Download all files.
2.  Open Jupyter Notebook.
3.  Open `Part_B_Final_Explained.ipynb`
4.  Run all cells.
5.  Outputs and graphs will be generated.

------------------------------------------------------------------------

# 🎯 Project Objective

To apply statistical and probability techniques on loan dataset and
analyze customer loan default behavior.

------------------------------------------------------------------------

# 👨‍🎓 Author

Student Project\
Mathematics & Advanced Statistics
