# Hr_analytics
Employee retention and workforce management are vital for organizations. This project leverages HR Analytics to analyze employee data, identifying factors influencing attrition, job satisfaction, and workforce trends. Using the **general_data.csv** dataset, it provides insights to help HR professionals enhance retention strategies .

# 📊 HR Analytics Project

## 🏆 Overview
Employee retention and workforce management are key challenges for organizations. This project leverages HR Analytics to analyze employee data, identifying factors affecting attrition, job satisfaction, and workforce trends.

The dataset (**general_data.csv**) includes various employee attributes such as age, job role, education, attrition status, monthly income, job satisfaction, and more. The goal is to provide actionable insights for HR professionals to enhance employee retention strategies.

---

## 🎯 Objectives
- 🔍 **Understand Workforce Demographics**: Analyze employee distribution across roles, departments, and education levels.
- 📊 **Data Visualization & Insights**: Use statistical measures and visualizations to identify workforce trends.
- 🤖 **Predict Employee Attrition**: Develop a machine learning model to forecast attrition likelihood.

---

## 🚀 Features & Analysis
The notebook follows a structured approach:

### 1️⃣ Data Loading & Cleaning
- 📂 Load dataset (**general_data.csv**) using Pandas.
- 🧹 Handle missing values appropriately.
- 🔄 Ensure data consistency for analysis.

### 2️⃣ Exploratory Data Analysis (EDA)
- 📜 **Summary Statistics**: Compute mean, median, and standard deviation.
- 📈 **Distribution Analysis**: Visualize demographics (age, experience, salary).
- 🔗 **Correlation Analysis**: Examine relationships between variables.
- 🚪 **Attrition Breakdown**: Understand attrition rates across attributes.

### 3️⃣ Data Visualization
- 📊 **Categorical Features Analysis**
  - Bar charts for job roles, education, and attrition trends.
- 📈 **Numerical Features Analysis**
  - Histograms & box plots for continuous variables like age, income, and experience.
  - Outlier detection for better model accuracy.

### 4️⃣ Machine Learning Model
- 🤖 **Train a Classification Model**: Predict employee attrition.
- 🏋️ **Model Training**: Implement machine learning algorithms.
- 📊 **Evaluation Metrics**: Measure accuracy, precision, recall, and F1-score.

---

## ⚙️ Installation & Requirements
### 📦 Dependencies
Ensure Python 3.x is installed along with the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

### 🛠 Running the Notebook
🚀 Clone the repository:
```bash
git clone https://github.com/Havoc-ameen/Hr_analytics
cd HR-Analytics-Regression
```
📂 Open Jupyter Notebook:
```bash
jupyter notebook
```
▶️ Run **HR_Analytics.ipynb** sequentially.

## 📑 Dataset Information
The dataset consists of anonymized employee records with key features:

| 🏷️ Feature | 📋 Description |
|------------|--------------|
| 🆔 Employee ID | Unique identifier for employees |
| 🎂 Age | Employee's age |
| 👨‍💼 Job Role | Designation within the company |
| 🏢 Department | Department where the employee works |
| 🎓 Education | Education level (e.g., Bachelor's, Master's, PhD) |
| 💰 Monthly Income | Salary details |
| 📆 Total Working Years | Overall experience in years |
| ⏳ Years at Company | Number of years in the current company |
| 😊 Job Satisfaction | Employee satisfaction rating (1-4) |
| ❌ Attrition | Whether the employee left the company (Yes/No) |

---

## 📈 Model Performance

### 🏋️ Training Performance:
- **Training Accuracy**: 61.16%
- **Precision**: 61.95%
- **Recall**: 58.24%

**Confusion Matrix (Training Data):**
```
[[341 191]
 [223 311]]
```

### 🧪 Testing Performance:
- **Testing Accuracy**: 58.15%
- **Precision**: 58.75%
- **Recall**: 53.11%

**Confusion Matrix (Testing Data):**
```
[[113  66]
 [ 83  94]]
```

### 📊 Observations:
- The model generalizes moderately well, with a **testing accuracy of 58%**.
- Precision and recall indicate the need for further improvement via feature engineering or hyperparameter tuning.
- False positives and negatives in the confusion matrix highlight misclassifications.

---

## 📜 License
This project is open-source and available under the **MIT License**.

🚀 Feel free to contribute and enhance the model's performance!

