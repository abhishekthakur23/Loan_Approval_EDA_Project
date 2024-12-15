# Loan_Approval_EDA_Project
In this assessment, an Exploratory Data Analysis (EDA) will be conducted on a dataset related to home loan approval. The dataset, provided by Skill Circle, offers a wealth of information for analysis. The focus will be on exploring the data, identifying patterns, trends, and key insights that could impact loan approval decisions.


# Data Overview

Data Overview

The home loan approval dataset provides a detailed collection of variables related to borrower profiles, loan amounts, and approval outcomes. It consists of both categorical and numerical features, offering valuable insights for analysis.
•	Dataset contains 367 rows.
•	Dataset contains 12 columns.
•	Dataset contains Null Values.
•	Dataset contains 2 int type 3 float type and 7 object type columns.

Dataset Columns:
1.	Loan_ID: Unique identifier for each loan application.
2.	Gender: Applicant's gender (with some missing values).
3.	Married: Marital status of the applicant.
4.	Dependents: Number of dependents the applicant has (with some missing values).
5.	Education: Education level of the applicant (Graduate or Not Graduate).
6.	Self_Employed: Whether the applicant is self-employed (with some missing values).
7.	ApplicantIncome: Income of the applicant.
8.	CoapplicantIncome: Income of the co-applicant.
9.	LoanAmount: The amount of loan applied for (with some missing values).
10.	Loan_Amount_Term: Term of the loan in months (with some missing values).
11.	Credit_History: Whether the applicant has a credit history (with some missing values).
12.	Property_Area: The area where the property is located (Urban, Semiurban, or Rural).


# Data Cleaning and Preparation

- Missing Value Treatment
  
The dataset contains 84 missing values, which were addressed using various methods to ensure data integrity. Numerical data with missing values were imputed using the mean or median, while categorical data with only a few missing entries were replaced with placeholders. In cases where the missing data was deemed insignificant to the overall analysis, the affected rows were removed. Additionally, for features where imputation wasn't appropriate, alternative techniques were applied to effectively handle the missing data.

# EDA

The Exploratory Data Analysis (EDA) for loan approval focuses on uncovering key insights and patterns within the dataset that could influence the loan approval process. The analysis begins with a thorough examination of the data's structure, including the distribution of numerical and categorical features, as well as identifying any missing values. Visualizations are employed to explore relationships between variables such as applicant income, loan amount, credit history, and loan approval status. By examining these relationships, the EDA aims to reveal significant factors that may affect loan approval decisions. Additionally, outliers and anomalies are identified and analyzed to understand their impact on the data. The overall goal of the EDA is to provide a comprehensive understanding of the factors driving loan approvals, which will inform subsequent modeling and decision-making processes. It includes visualizations like Histogram, Box Plots, Bar Charts, Pie Charts, Heatmap to understand insights and key findings.
