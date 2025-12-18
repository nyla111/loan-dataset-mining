# Data Science Portfolio: Loan Default Analysis

## Repository Overview

This repository contains two complementary Jupyter notebooks that demonstrate a complete **data science workflow** for financial risk analysis:

1. **`data_preprocessing.ipynb`** - Data Exploration & Preprocessing Assignment
2. **`prediction_classifiers.ipynb`** - Machine Learning Classification Project

## Project Structure

### **1. Data Exploration & Preprocessing**
**File:** `data_preprocessing.ipynb`

**Objective:** Comprehensive exploratory data analysis (EDA) and data preparation on loan data.

**Key Components:**
- Attribute type identification (nominal, ordinal, interval, ratio)
- Statistical summaries and distribution analysis
- Missing value assessment and impact analysis
- Data visualization with histograms and boxplots
- Preprocessing techniques:
  - Binning (equi-width, equi-depth)
  - Normalization (min-max, z-score)
  - Discretization for risk scoring
  - Categorical binarization

**Technical Stack:**
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn for preprocessing

---

### **2. Machine Learning Classification**
**File:** `prediction_classifiers.ipynb`

**Objective:** Build and optimize machine learning models to predict loan default risk.

**Dataset:**
- Training: 48,962 samples × 19 features
- Testing: 20,984 samples × 18 features
- Target: `loan_default` (0=No Default, 1=Default)
- Class distribution: ~78% non-default, ~22% default

**Classification Algorithms Implemented:**
1. Decision Tree Classifier
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. Multi-layer Perceptron (Neural Network)

**Machine Learning Pipeline:**
1. **Data Preprocessing:** Missing value handling, feature correlation analysis
2. **Model Development:** 5 algorithms with hyperparameter tuning
3. **Model Evaluation:** Accuracy, F1-score, Precision, Recall, ROC-AUC
4. **Prediction:** Test set predictions and submission formatting

**Technical Stack:**
- Core: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn, Imbalanced-learn

---

## Dataset Files

The repository includes the necessary dataset files for both projects:
- **`dataset.xlsx`** - Primary dataset for the exploration assignment
- Additional training/testing datasets for the ML classification project

---

## Skills Demonstrated

### **Technical Skills**
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn (classification, preprocessing)
- **Statistical Analysis:** Distribution analysis, correlation studies
- **Feature Engineering:** Binning, normalization, discretization

### **Data Science Workflow**
1. Exploratory Data Analysis (EDA)
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Model Development and Evaluation
5. Results Interpretation and Reporting

---

## **Prerequisites**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
