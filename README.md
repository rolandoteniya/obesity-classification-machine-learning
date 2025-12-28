# Multi-Class Obesity Level Classification: A Supervised Learning Approach
> **Applied AI Project | University of Liverpool**

## 📊 Project Overview
This project develops a predictive machine learning model for a medical organization to classify patients' obesity levels based on eating habits, physical conditions, and demographic data. The goal was to build a robust diagnostic tool that moves beyond simple BMI calculations to consider a holistic patient profile.

### **The Result:**
After a systematic evaluation of multiple supervised learning algorithms, the final **Support Vector Machine (SVM)** model achieved an accuracy of **95.97%** on unseen test data, misclassifying only 17 out of 422 cases.

---

### **📄 [View Full Project Report (PDF)](./Assignment_1_final.pdf)**

---

## 🛠️ Tech Stack
* **Machine Learning:** `Scikit-learn` (SVM, Random Forest, Decision Trees)
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Seaborn`, `Matplotlib`
* **Techniques:** Stratified 5-Fold Cross-Validation, GridSearchCV for Hyperparameter Tuning.



## 🧪 Systematic Pipeline & Methodology
1. **Data Management:** Performed an 80:20 train-test split and handled categorical encoding for lifestyle features (e.g., frequency of vegetable consumption, physical activity).
2. **Exploratory Data Analysis (EDA):** Utilized correlation matrices and distribution plots to identify key predictors of obesity levels.
3. **Model Selection "Bake-off":** Ran multiple baseline models without tuning to establish a performance floor.
4. **Optimization:** Conducted **Grid Search CV** to tune hyperparameters, ensuring the model generalized well and didn't overfit the training data.
5. **Robust Evaluation:** Prioritized the **Confusion Matrix** to ensure misclassifications were only occurring between "adjacent" categories (e.g., Overweight Level I vs. Level II), which is clinically acceptable compared to major errors.

## 📈 Key Results
* **Best Model:** Support Vector Machine (SVM)
* **Final Test Accuracy:** 95.97%
* **Feature Insight:** High correlation found between physical activity levels, age, and obesity types, validating the multi-dimensional approach to health classification.

## ⚙️ Professional Reflection & Growth
* **Feature Selection:** This project highlighted the importance of feature scaling, particularly for distance-based algorithms like SVM.
* **Evaluation Metrics:** While accuracy was high, I focused on **Precision and Recall** for each of the 7 classes to ensure the model wasn't biased toward the majority class.
