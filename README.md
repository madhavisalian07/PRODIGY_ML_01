# PRODIGY_ML_01
## House Price Prediction Using Linear Regression
**Internship Domain:** Machine Learning  
**Organization:** Prodigy InfoTech  
**Task Number:** 01  

---

### 1. Project Objective
The goal of this task is to build a predictive Machine Learning model using Linear Regression to estimate house sale prices. The model utilizes structural and spatial features from the House Prices dataset to establish underlying pricing trends.

### 2. Dataset & Features Used
The dataset used for this project is `train.csv`. The model relies on the following key features:
* **Independent Variables (Features):**
  * `GrLivArea`: Above grade/ground living area square feet.
  * `BedroomAbvGr`: Number of bedrooms above basement level.
  * `FullBath`: Number of full bathrooms above grade.
* **Dependent Variable (Target):**
  * `SalePrice`: The final property sale price in USD.

### 3. Workflow & Methodology
1. **Data Preprocessing:** Handled missing values across the selected feature matrix systematically using mean imputation (`fillna()`).
2. **Data Partitioning:** Split the dataset into an **80% Training Set** (to optimize weights) and a **20% Testing Set** (to validate generalizations) using `train_test_split`.
3. **Model Implementation:** Trained a **Linear Regression** algorithm from `scikit-learn` to calculate the best-fit hyperplane minimizing residual errors.
4. **Evaluation:** Evaluated performance metrics on unseen testing data to measure prediction accuracy.

### 4. Core Libraries Applied
* `pandas` & `numpy` - For data manipulation and structures.
* `scikit-learn` - For data splitting, linear modeling, and performance metrics.
* `matplotlib` & `seaborn` - For advanced structural data visualizations.

---
**Status:** Completed successfully! 🚀
