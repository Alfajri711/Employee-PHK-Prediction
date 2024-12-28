# Employee Attrition Prediction 🚀  
*Predicting Employee Turnover with Data Science*

## 📋 Project Overview  
This project focuses on predicting employee attrition (voluntary resignation or termination) using machine learning techniques. By analyzing HR datasets, we aim to provide insights and a predictive model that can help organizations manage employee turnover effectively.  

## 📂 Dataset  
The dataset used is the **HRDataset** from Kaggle. It contains detailed employee information such as:  
- **Salary**  
- **Gender**  
- **Age**  
- **Recruitment Source**  
- **Performance Score**  
- **Attrition Status**  

📁 **File:** [HRDataset_v14.csv](HRDataset_v14.csv)  

---

## 📊 Notebook Features  
The analysis and modeling process is documented in the notebook:  
**`HR_Employee_Attrition.ipynb`**  

### Steps Included:  
1. **Exploratory Data Analysis (EDA):**  
   Visualizations and statistical summaries to understand the dataset.  
2. **Data Preprocessing:**  
   Handling missing values, encoding categorical variables, and scaling numerical features.  
3. **Train-Test Split:**  
   Splitting data into training and testing sets for model evaluation.  
4. **Modeling:**  
   Building a Logistic Regression classifier to predict employee attrition.  
5. **Evaluation Metrics:**  
   Assessing the model using metrics like Accuracy, Precision, Recall, and F1-Score.  

---

## 🔍 Key Insights from the Analysis  
1. **Salary Impact on Attrition:**  
   Employees with lower salaries are significantly more likely to leave or face termination compared to higher-paid employees.  
2. **Age Factor:**  
   Younger employees, particularly those in their early 20s, showed a higher likelihood of attrition.  
3. **Performance Scores:**  
   Employees with lower performance scores were more prone to termination.  
4. **Recruitment Source:**  
   Recruitment channels had varying impacts on employee retention, with certain sources correlating with higher attrition rates.  
5. **Gender:**  
   No significant difference in attrition rates was observed between male and female employees.  

These insights can guide HR teams to focus retention strategies on at-risk groups and optimize recruitment practices.  

---

## ⚙️ Technologies Used  
- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-Learn**

---

## 🏆 Results  
The initial Logistic Regression model achieved:  
- **Accuracy:** 85%  
- **Precision:** 78%  
- **Recall:** 80%  

---

## 💡 Future Improvements  
1. Experimenting with other classification algorithms like Random Forest, XGBoost, etc.  
2. Hyperparameter tuning to boost model performance.  
3. Deploying the model for real-time use by HR teams.  
