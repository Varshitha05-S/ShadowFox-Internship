📌 Project Overview

The objective of this project is to predict whether a loan application will be approved or not based on applicant details such as income, education, credit history, and property area.

This project demonstrates a complete machine learning classification pipeline, commonly used in banking and financial institutions to automate loan approval decisions.

📊 Dataset Description

The dataset contains information about loan applicants and their approval status.

🔹 Features Used
Feature	Description
Loan_ID	Unique loan identifier
Gender	Male / Female
Married	Applicant married or not
Dependents	Number of dependents
Education	Graduate / Not Graduate
Self_Employed	Self-employed or not
ApplicantIncome	Income of applicant
CoapplicantIncome	Income of co-applicant
LoanAmount	Loan amount requested
Loan_Amount_Term	Loan duration (in months)
Credit_History	Credit score (1 = good, 0 = bad)
Property_Area	Urban / Semiurban / Rural
🎯 Target Variable
Column	Description
Loan_Status	Y = Approved, N = Not Approved
📐 Dataset Shape

Rows: 614

Columns: 13

🪜 Step-by-Step Work Done
✅ Step 1: Data Loading

Loaded a real-world loan dataset using Pandas.

Displayed initial rows to understand the structure.

✅ Step 2: Exploratory Data Analysis

Checked dataset information and statistical summary.

Identified missing values in multiple columns.

✅ Step 3: Handling Missing Values

Filled missing numerical values using median.

Filled missing categorical values using mode.

Ensured no missing values remained.

✅ Step 4: Encoding Categorical Variables

Converted categorical data (Gender, Education, etc.) into numerical values using Label Encoding.

Converted target variable:

Approved → 1

Not Approved → 0

✅ Step 5: Feature & Target Separation

Input features (X): Applicant and loan details.

Target variable (y): Loan approval status.

✅ Step 6: Train-Test Split

Split data into:

80% Training set

20% Testing set

This ensures unbiased model evaluation.

✅ Step 7: Model Building

Used Logistic Regression, suitable for binary classification.

Trained the model using training data.

✅ Step 8: Model Evaluation

The model performance was evaluated using accuracy, classification report, and confusion matrix.

📌 Numerical Results
Metric	Value
Accuracy	~78%

(Accuracy may slightly vary due to random splitting)

📊 Classification Report (Example Output)
              precision    recall  f1-score   support

           0       0.70      0.55      0.62
           1       0.81      0.89      0.85

    accuracy                           0.78


1 → Loan Approved

0 → Loan Not Approved

📈 Confusion Matrix Visualization

A confusion matrix was plotted to visually analyze:

Correct approvals

Correct rejections

Misclassifications

This helps understand model strengths and weaknesses.

🧠 Final Output Example

Example prediction:

Predicted Loan Status: Approved
Actual Loan Status: Approved

🛠️ Technologies Used

Python

Pandas

Scikit-learn

Matplotlib

Seaborn

🎯 Key Learnings

Handling real-world missing data

Encoding categorical variables

Understanding classification problems

Training and evaluating ML models

Using confusion matrix for performance analysis

End-to-end ML project workflow

🏁 Conclusion

This project successfully demonstrates how machine learning can be applied to automate loan approval decisions.
By following proper data preprocessing, model training, evaluation, and visualization steps, a reliable classification model was built.


