# Predicting-Employee-Churn-in-Python

Employee churn refers to the departure of employees from an organization. It's essentially the loss of intellectual assets and workforce, which impacts productivity, morale, and operational continuity.

#### 📉 Causes of Employee Churn:

Research shows that churn is influenced by:


Personal factors: Age, gender, ethnicity, education, marital status

Work-related factors: Tenure, pay, job satisfaction, salary, working conditions, growth opportunities, and perceived fairness

Special skill sets: Employees with niche skills are harder to replace and their loss has a greater impact.

#### 💰 Cost of Churn:


Financial: Hiring and training replacements is expensive

Operational: Loss of expertise and temporary productivity drop

Time: New employees take time to ramp up

#### 🧠 Why Predict Churn?

Machine learning helps organizations predict churn and take proactive actions such as:

Improving retention strategies

Enhancing employee satisfaction

Reducing recruitment costs

#### 🔁 Employee vs. Customer Churn:


Employees are selected by the company, customers are not.

Employees are the face and engine of the organization.

Losing employees, like losing customers, affects business but with different internal implications.

Understanding employee churn helps build better HR policies.




### 🛠️ Machine Learning Approach



#### 🔢 Data Preprocessing:

Encoded categorical features using LabelEncoder and OrdinalEncoder

Handled class imbalance using SMOTE to oversample the minority class (left = 1)

Split data into training and testing sets (e.g., 70/30)

#### 🤖 Model Training:

Used a Random Forest Classifier to model the data.



#### ✅ Conclusion


The model demonstrated excellent performance in predicting employee churn, with high accuracy, precision, recall, and F1 scores — even on an imbalanced dataset.

By leveraging this model, organizations can:

Better understand the factors contributing to churn

Implement targeted retention strategies

Minimize the costs and disruption of employee turnover

