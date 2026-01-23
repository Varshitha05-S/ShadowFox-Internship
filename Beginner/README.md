🏠 House Price Prediction using Machine Learning

(Beginner Level – ShadowFox Internship)

📌 Project Overview

The objective of this project is to predict house prices based on various housing and location-related features using the California Housing Dataset.

This project demonstrates how regression-based machine learning models can be used to solve real-world prediction problems in the real estate domain.

📊 Dataset Description

The California Housing Dataset contains housing information collected from California districts.

🔹 Features Used
Feature	Description
MedInc	Median income in the district
HouseAge	Average age of houses
AveRooms	Average number of rooms
AveBedrms	Average number of bedrooms
Population	Population of the district
AveOccup	Average house occupancy
Latitude	Latitude of the district
Longitude	Longitude of the district
🎯 Target Variable
Column	Description
PRICE	Median house value (in hundreds of thousands)
📐 Dataset Shape

Rows: 20,640

Columns: 9

🪜 Step-by-Step Work Done
✅ Step 1: Data Loading

Loaded the California Housing dataset using fetch_california_housing() from Scikit-learn.

Converted the dataset into a Pandas DataFrame.

✅ Step 2: Exploratory Data Analysis

Displayed the first 5 rows of the dataset.

Checked dataset shape, column types, and statistical summary.

Verified that there were no missing values.

✅ Step 3: Feature & Target Separation

Input features (X): All housing-related attributes

Target (y): House price (PRICE)

✅ Step 4: Train-Test Split

Split the dataset into:

80% Training data

20% Testing data

This ensures the model is evaluated on unseen data.

✅ Step 5: Model Selection & Training

Used a Linear Regression model to predict house prices.

Trained the model using training data.

✅ Step 6: Model Evaluation

The model was evaluated using standard regression metrics:

📌 Numerical Results
Metric	Value
Mean Squared Error (MSE)	0.5559
R² Score	0.5758
🔍 Interpretation

MSE indicates the average squared difference between predicted and actual house prices.

R² Score (~57%) shows the model explains a reasonable amount of variance in house prices using the given features.

🧠 Final Output Example

The trained model predicts house prices based on input features such as income, location, and housing conditions.

Example output:

Predicted House Price: 2.45
Actual House Price: 2.38


(Values are in hundreds of thousands)

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

🎯 Key Learnings

Understanding regression problems

Working with real-world datasets

Feature-target separation

Model training and evaluation

Interpreting regression metrics

🏁 Conclusion

This project successfully demonstrates how machine learning regression techniques can be applied to predict house prices.
It serves as a strong beginner-level foundation for understanding supervised learning and real-world data analysis.
