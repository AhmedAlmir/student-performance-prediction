# student-performance-prediction
# 🎓 Student Performance Prediction using Linear Regression

## 📌 Project Overview
This project uses Linear Regression to predict students' final grades based on demographic, social, and academic features.  
The dataset contains information about students such as age, study time, family background, and previous grades.

---

## 🎯 Objective
The main goal of this project is to:
- Analyze factors affecting student performance.
- Build a Linear Regression model to predict the final grade (G3).
- Evaluate the model using regression metrics.

---

## 📊 Dataset Description
The dataset includes 33 features related to students' academic and personal characteristics.

### 🔹 Key Features:
- age: Student age
- studytime: Weekly study time
- absences: Number of absences
- failures: Number of past class failures
- G1: First period grade
- G2: Second period grade
- G3: Final grade (Target Variable)

📁 Dataset Source: UCI Machine Learning Repository / Kaggle

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow
1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
   - Handling categorical variables
   - Feature selection
   - Scaling (if needed)
4. Building Linear Regression Model
5. Model Evaluation
6. Results & Insights

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Correlation Heatmap
![Correlation Heatmap](images/eda_correlation.png)

### 🔹 Relationship Between Study Time and Final Grade
![Study Time vs Grade](images/studytime_vs_grade.png)

### 🔹 Absences vs Final Grade
![Absences vs Grade](images/absences_vs_grade.png)

---

## 🤖 Model Building
- Split dataset into training and testing sets.
- Train a Linear Regression model using scikit-learn.
- Predict final grades on test data.

---

## 📈 Model Evaluation

### 🔹 Actual vs Predicted Grades
![Actual vs Predicted](images/actual_vs_predicted.png)

### 🔹 Performance Metrics
- R² Score: 0.82  
- Mean Squared Error (MSE): 10.5  
- Mean Absolute Error (MAE): 2.4  

---

## ✅ Results & Conclusion
The Linear Regression model shows good performance in predicting students' final grades.  
Previous grades (G1, G2) and study time were found to be the most influential factors.  
Future improvements may include using advanced machine learning models such as Random Forest or Gradient Boosting.

---

## ▶️ How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/student-performance-prediction.git
