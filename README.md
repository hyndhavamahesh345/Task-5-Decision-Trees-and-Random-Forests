## 📌 Task 5: AI & ML Internship Assignment  
# 🌳 Heart Disease Dataset - Decision Trees & Random Forests  

This repository contains a classification project using **Decision Tree** and **Random Forest** algorithms on the Heart Disease dataset. This task is part of the **AI & ML Internship** program and focuses on tree-based machine learning models, model visualization, feature importance, and cross-validation.

---

## 🎯 Objective  

To implement and compare Decision Tree and Random Forest models to:  
- Understand decision tree structure and prediction logic  
- Visualize the tree and interpret model decisions  
- Control overfitting by tuning tree depth  
- Use ensemble learning with Random Forests  
- Interpret important features  
- Evaluate models using cross-validation  

---

## 🧰 Tools and Libraries Used  

- Python  
- Jupyter Notebook / Google Colab  
- Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 📂 Dataset  

The dataset used is the **Heart Disease Dataset**, provided as `heart.csv`.  
It contains clinical and demographic information to predict the presence of heart disease.

---

## 📊 What Was Done  

1. **Loaded and prepared the dataset**  
   - Checked for missing values  
   - Separated features (`X`) and target (`y`)  
   - Performed train-test split  

2. **Trained a Decision Tree Classifier**  
   - Fitted the model on training data  
   - Visualized the tree structure  
   - Controlled overfitting by adjusting `max_depth`  

3. **Analyzed overfitting**  
   - Plotted training vs test accuracy at different depths  

4. **Trained a Random Forest Classifier**  
   - Compared its performance with a single Decision Tree  
   - Extracted feature importances  

5. **Evaluated using Cross-Validation**  
   - Used 5-fold cross-validation to assess generalization  

---

## 🔍 Key Insights  

- 🌳 **Decision Tree** achieved perfect cross-validation accuracy (1.0), suggesting possible overfitting.  
- 🌲 **Random Forest** provided high test accuracy (**0.985**) and excellent generalization with **cross-validation accuracy of 0.997**.  
- 🧠 **Top Features**: `thal`, `ca`, `cp`, `oldpeak`, `chol` were most influential in predictions.  
- ✅ **Random Forest** outperformed Decision Tree in overall reliability and stability.

---

## 🧪 Results Summary  

| Model           | Test Accuracy | Cross-Validation Accuracy |
|----------------|---------------|----------------------------|
| Decision Tree  | —             | **1.000**                  |
| Random Forest  | **0.985**     | **0.997**                  |


