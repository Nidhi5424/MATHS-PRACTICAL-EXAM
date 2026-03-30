# 📊 Loan Default Statistical Analysis

## 📌 Project Overview

This project performs statistical and probability analysis on a loan
application dataset using Python.

The objective of this project is to analyse customer financial data and
understand loan default behaviour using statistical techniques,
probability calculations, visualisation, and linear algebra operations.

The project consists of:

-   **Part A --- Theory Concepts**
-   **Part B --- Python Implementation**

------------------------------------------------------------------------

# 📁 Dataset Information

Dataset file used:

`loan_applications.csv`

## Columns in Dataset:

-   Customer_ID --- Unique customer ID
-   Age --- Customer age
-   Income --- Monthly income
-   Loan_Amount --- Loan amount taken
-   Credit_Score --- Credit score value
-   Loan_Term --- Loan duration
-   Default_Status --- Loan default status (Yes/No)

------------------------------------------------------------------------

# 🧮 Part A --- Theory Concepts

The following statistical concepts are explained:

1.  Mean, Median and Mode
2.  Variance and Standard Deviation
3.  Random Variable
4.  Conditional Probability
5.  Bayes Theorem
6.  Empirical vs Theoretical Probability
7.  Poisson Distribution
8.  Eigenvalues and Eigenvectors

Each topic includes:

-   Definition
-   Formula
-   Example
-   Application

------------------------------------------------------------------------

# 🧑‍💻 Part B --- Python Implementation Steps

## Step 1 --- Import Libraries

Libraries used:

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   scipy

These libraries are used for data handling, calculations, and visualisation
and statistical analysis.

------------------------------------------------------------------------

## Step 2 --- Load Dataset

Dataset is loaded using:

`pd.read_csv()`

The first five records are displayed using:

`df.head()`

------------------------------------------------------------------------

## Step 3 --- Central Tendency

Calculated:

-   Mean
-   Median
-   Mode

Purpose:

To find the typical income value of customers.

------------------------------------------------------------------------

## Step 4 --- Dispersion Measures

Calculated:

-   Range
-   Variance
-   Standard Deviation

Purpose:

To measure variation in loan amounts.

------------------------------------------------------------------------

## Step 5 --- Default Probability

Calculated:

Probability of loan default.

Purpose:

To determine the proportion of customers who defaulted.

------------------------------------------------------------------------

## Step 6 --- Contingency Table

Created a comparison between:

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

-   Histogram
-   KDE Curve

Purpose:

To visualise the distribution of credit scores.

------------------------------------------------------------------------

## Step 9 --- Skewness and Kurtosis

Calculated:

-   Skewness
-   Kurtosis

Purpose:

To understand the distribution shape.

------------------------------------------------------------------------

## Step 10 --- Q-Q Plot

Generated a Q-Q plot to check the normal distribution.

------------------------------------------------------------------------

## Step 11 --- Linear Algebra

Performed:

-   Dot Product
-   Vector Norm
-   Angle Calculation

Purpose:

To measure similarity between customer vectors.

------------------------------------------------------------------------

# 📊 Key Insights

1.  Customers with low credit scores show higher default probability.
2.  Loan amount distribution shows variation across customers.
3.  Credit score distribution follows a near-normal pattern.
4.  Higher-income customers generally take higher loan amounts.
5.  Default risk increases when the credit score decreases.

------------------------------------------------------------------------

# 🛠 Tools Used

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   SciPy

------------------------------------------------------------------------

# 📂 Project Structure

loan-default-analysis

├── Part_A_Detailed_Final.pdf
├── Part_B_Final_Explained.ipynb
├── loan_applications.csv
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

To apply statistical and probability techniques to the loan dataset and
Analyse customer loan default behaviour.

------------------------------------------------------------------------
-<img width="640" height="480" alt="Histogram_Credit_Score" src="https://github.com/user-attachments/assets/4911cbaa-cbb1-4c9b-b8f2-b8d8f993f70f" />


-<img width="640" height="480" alt="QQ_Plot_Income" src="https://github.com/user-attachments/assets/fac71a14-54cd-475c-80c0-ac325ec0d916" />


