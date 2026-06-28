# AI-ML-Model-Validation

# AI & ML Task 3: Model Validation, Overfitting Control & Hyperparameter Tuning

## 📌 Project Overview
This project focuses on improving machine learning model performance by moving beyond basic training and evaluation. It demonstrates how to build a **robust and generalizable regression model** using proper validation techniques.

The main goal is not just accuracy, but **model reliability and real-world performance**.

## 🎯 Objectives

- Detect and analyze overfitting in machine learning models  
- Apply cross-validation for reliable performance estimation  
- Tune hyperparameters using GridSearchCV  
- Improve model generalization  
- Compare multiple regression models  
- Select the best model based on RMSE and R² Score  

## 📊 Dataset Used

- **Name:** California Housing Dataset  
- **Source:** Scikit-learn built-in dataset  
- **Target Variable:** Median House Value  
- **Features:** Income, rooms, population, location-based attributes  

## 🧠 Machine Learning Models Used

- Linear Regression (Baseline model)
- Ridge Regression (Regularized model)
- Decision Tree Regressor
- Tuned Decision Tree (Optimized model)

## ⚙️ Techniques Implemented

### ✔ Data Preprocessing
- Feature scaling using StandardScaler
- Train-test split (80-20)

### ✔ Model Evaluation
- RMSE (Root Mean Squared Error)
- R² Score

### ✔ Overfitting Detection
- Comparison of training vs testing performance
- Decision Tree behavior analysis

### ✔ Cross-Validation
- 5-fold cross-validation for stable evaluation

### ✔ Hyperparameter Tuning
- GridSearchCV applied on Decision Tree
- Tuned parameters:
  - max_depth
  - min_samples_split

## 🏆 Final Outcome

- Best performing model selected after hyperparameter tuning  
- Overfitting reduced using constraints on Decision Tree  
- Cross-validation ensured stable and reliable performance  
- Final model chosen based on lowest RMSE and highest R² score  

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  
 
## 📌 Key Learnings

- Understanding overfitting vs underfitting  
- Importance of cross-validation in ML  
- Hyperparameter tuning using GridSearchCV  
- Building production-ready ML models  
- Model comparison and selection techniques  

## 🚀 Future Improvements

- Try Random Forest and XGBoost models  
- Apply RandomizedSearchCV for faster tuning  
- Deploy model using Flask or Streamlit  
- Add feature importance visualization  

## 👨‍💻 Author

RAJAMANI S
