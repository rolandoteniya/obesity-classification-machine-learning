# Multi-Class Obesity Level Classification: A Supervised Learning Approach
> **Applied AI Project | University of Liverpool**

## 📊 Project Overview
This project develops a predictive machine learning model for a medical organization to classify patients' obesity levels based on eating habits, physical conditions, and demographic data. 

### **The Result:**
After conducting a systematic "bake-off" between six different supervised learning architectures, the final **Support Vector Machine (SVM)** model achieved an accuracy of **95.97%** on unseen test data.

---

### **📄 [View Full Project Report (PDF)](./Obesity_Classification_Report.pdf)**

---

## 🛠️ Tech Stack & Models Evaluated
I implemented and benchmarked a suite of supervised learning algorithms to identify the most robust classifier:
* **Linear Models:** Logistic Regression
* **Instance-based:** k-Nearest Neighbours (kNN)
* **Probabilistic:** Naive Bayes
* **Tree-based:** Decision Trees, Random Forest
* **Kernel-based:** Support Vector Machine (SVM) — *Top Performer*

**Libraries:** `Scikit-learn`, `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`.

## 🧪 Systematic Pipeline & Methodology
1. **Data Management:** Performed an 80:20 train-test split and handled categorical encoding for multi-dimensional lifestyle features.
2. **Model Benchmarking:** Evaluated 6 different algorithms to establish baseline performance metrics across Accuracy, Precision, Recall, and F1-Score.
3. **Optimization:** Conducted **GridSearchCV** for hyperparameter tuning and utilized **Stratified 5-Fold Cross-Validation** to ensure model stability and prevent overfitting.
4. **Clinical Validation:** Analyzed the **Confusion Matrix** to ensure that any misclassifications occurred only between "adjacent" categories, maintaining high clinical reliability.

## 📈 Final Model Performance (SVM)
* **Test Accuracy:** 95.97%
* **Robustness:** Successfully categorized 7 distinct obesity levels with minimal marginal error.
