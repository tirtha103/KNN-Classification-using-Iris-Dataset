#  Iris Flower Classification using K-Nearest Neighbors (KNN)

>  **Internship Task 6 – Distance-Based ML Model**  
>  **Submitted by:** Tirtha Dutta  
>  **Model Type:** Multiclass Classification | Supervised Learning  

---

##  Objective

Build and evaluate a **K-Nearest Neighbors (KNN)** model to classify species of iris flowers based on petal and sepal measurements. Demonstrate complete ML workflow from data cleaning to visual decision boundaries.

---

##  Dataset

- **Source:** [Iris Dataset – Kaggle](https://www.kaggle.com/datasets/uciml/iris)  
- **Classes:** `Iris-setosa`, `Iris-versicolor`, `Iris-virginica`  
- **Shape (after cleaning):** `150 rows × 5 columns`  
- **Target Variable:** `Species`

---

##  Workflow Summary

### 1️ Data Cleaning  
- Dropped unnecessary `Id` column  
- Verified no missing/null values  
- Saved cleaned version as `iris_cleaned.csv`   

### 2️ Label Encoding & Feature Scaling  
- Encoded flower names (`Species`) to numeric labels: `0`, `1`, `2`  
- Standardized all features using `StandardScaler`  

### 3️ Exploratory Data Analysis (EDA)  
-  Generated **boxplots** to visualize feature distributions  
-  Created a **correlation heatmap**  
-  Analyzed class distribution, feature types, and outliers  

### 4️ Model Building: KNN Classifier  
- Explored different values of **K (1 to 15)**  
- Best accuracy at **K = 1**: `96.67%`  
- Trained final KNN model on scaled data  

### 5️ Model Evaluation  
- Evaluated using **accuracy**, **confusion matrix**, and **classification report**  
- Saved confusion matrix proof as: `images/confusion_matrix.png`  

### 6️ Visual Decision Boundary  
- Trained a 2D KNN model on first two features  
- Created a **mesh grid** to plot class separation  
- Saved output as: `images/knn_decision_boundary.png`  

---

##  Final Results

| Metric              | Value       |
|---------------------|-------------|
| Accuracy (K = 1)    | **96.67%**  |
| Number of Classes   | 3           |
| Best K Value        | 1           |

---
##  Tools & Libraries Used

- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- Jupyter Notebook  

---

##  Skills Demonstrated

- Data Cleaning & Preprocessing (Task 1)  
- Exploratory Data Analysis (Task 2)  
- Feature Scaling & Label Encoding (Task 3)  
- Classification using KNN (Task 4 & Task 6)  
- Confusion Matrix & Evaluation Reports  
- Visual Decision Boundary Plot (Task 6B)  
- GitHub project structuring & documentation

---

>  *This project is built for internship evaluation and job-readiness. All steps are implemented with professional standards, including proofs from Tasks 1–6.*



