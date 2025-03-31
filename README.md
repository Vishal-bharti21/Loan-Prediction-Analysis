# Loan Prediction Analysis

## Overview

This project focuses on analyzing a loan dataset to predict loan approval status. The analysis includes data cleaning, exploration, and the application of machine learning models to predict whether a loan will be approved or not.

## Project Structure

-   `Loan_prediction_analysis.ipynb`: Jupyter Notebook containing the complete analysis, from data loading and preprocessing to model building and evaluation.
-   `Dataset.csv`: The dataset used for the loan prediction analysis.

## Data Description

The dataset contains the following features:

*   **Loan_ID**: Unique loan ID.
*   **Gender**: Applicant gender (Male/Female).
*   **Married**: Marital status of the applicant (Yes/No).
*   **Dependents**: Number of dependents.
*   **Education**: Education level of the applicant (Graduate/Not Graduate).
*   **Self_Employed**: Self-employed status (Yes/No).
*   **ApplicantIncome**: Applicant income.
*   **CoapplicantIncome**: Co-applicant income.
*   **LoanAmount**: Loan amount in thousands.
*   **Loan_Amount_Term**: Term of the loan in months.
*   **Credit_History**: Credit history available (Yes/No).
*   **Property_Area**: Property area type (Urban/Semi-Urban/Rural).
*   **Loan_Status**: Loan approved (Y) or not approved (N).

## Libraries Used

*   `pandas`: For data manipulation and analysis.
*   `numpy`: For numerical computations.
*   `seaborn`: For data visualization.
*   `matplotlib`: For creating plots.

## Data Preprocessing Steps

1.  **Importing Libraries**: Importing necessary libraries such as Pandas, NumPy, Seaborn, and Matplotlib.
2.  **Loading the Dataset**: Loading the dataset from a CSV file into a Pandas DataFrame.
3.  **Handling Missing Values**: Imputing missing values in numerical and categorical columns.
4.  **Data Transformation**: Applying logarithmic transformations to reduce skewness.
5.  **Encoding Categorical Variables:** Converting categorical features into numerical format using techniques.

## How to Use

1.  **Clone the Repository**

    ```
    git clone [repository link]
    cd [repository name]
    ```

2.  **Install Dependencies**

    ```
    pip install pandas numpy seaborn matplotlib
    ```

3.  **Run the Notebook**

    *   Open `Loan_prediction_analysis.ipynb` in Jupyter Notebook or JupyterLab.
    *   Execute the cells in order to reproduce the analysis and results.

## Key Findings

*   Insights into which factors most strongly influence loan approval.
*   Visualizations illustrating the relationships between different variables.

## Contributing

Feel free to contribute to this project by submitting pull requests.
