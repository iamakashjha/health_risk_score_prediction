# Health Risk Score Prediction

I worked on this project to build a machine learning model for predicting the health risk score of patients based on given health indicators. I applied linear regression along with Lasso and Ridge regularization techniques to improve the model's performance. This project is a part of my learning, practicing data preparation, exploratory analysis, feature engineering, and predictive modeling.

**Dataset**

The dataset includes the following columns:

**age:** The age of the patient.

**bmi:** Body Mass Index of the patient.

**blood_pressure:** The blood pressure of the patient.

**cholesterol:** Cholesterol levels of the patient.

**glucose:** Glucose levels of the patient.

**insulin:** Insulin levels of the patient.

**heart_rate:** Heart rate of the patient.

**activity_level:** Activity level of the patient.

**diet_quality:** Quality of diet of the patient.

**smoking_status:** Whether the patient smokes (Yes or No).

**alcohol_intake:** The amount of alcohol intake by the patient.

**health_risk_score:** A composite score representing the overall health risk of a patient (target variable).

## Project Steps


**Data Preparation:**

* Imported the dataset and explored its structure.

* Handled missing values by replacing them with column means.

* Converted the categorical variable smoking_status into a binary format (1 for Yes, 0 for No).

**Modeling:**

* Split the data into training and testing sets (75% training, 25% testing).

* Trained and evaluated a Linear Regression model.

* Experimented with Lasso Regression models by varying the alpha values.

* Experimented with Ridge Regression models by varying the alpha values.


**Evaluation:**

* Measured the performance of the models using the R-squared metric.

* Plotted predicted vs actual health risk scores to visualize model accuracy.


**Tools and Libraries**

* pandas

* numpy

* matplotlib

* scikit-learn





### Author

**Akash Jha**