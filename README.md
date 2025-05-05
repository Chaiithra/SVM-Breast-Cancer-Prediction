# 🧠 Breast Cancer Classification with SVM & PCA

## 📌 Project Overview

This notebook focuses on building a classification model to distinguish between **Malignant** and **Benign** breast tumors using the **Breast Cancer Wisconsin Diagnostic dataset**. 

The pipeline includes full **EDA**, **feature importance**, **dimensionality reduction**, and **SVM-based classification** using both **Linear** and **RBF kernels**.

---

## 🧱 Notebook Structure

```text
1. 📦 Importing Libraries
2. 📥 Loading Dataset
3. 🔍 Understanding Data
   ├── Removing 'id' column
   ├── Checking dtypes and NaN values
   ├── Checking for Duplicates
   └── Statistical Summary
4. 📊 Exploratory Data Analysis (EDA)
   ├── Univariate Analysis
   ├── Box Plots
   ├── Distribution Plots (Histograms)
   │   ├── Right-Skewed Features
   │   ├── Left-Skewed Features
   │   └── Symmetrical Features
   ├── Why Skewness & Histograms Matter
   └── What We Can Do
5. 🔗 Bivariate Analysis
   └── Correlation Heatmap
6. 🌟 Feature Engineering
   ├── Feature Importance (Random Forest)
   └── Label Encoding
7. 🧠 Model Training
   ├── Train-Test Split
   ├── SVM Pipeline + Grid Search CV
   ├── Best Models (Linear & RBF)
   └── Refit and Evaluation
8. 📈 Evaluation
   ├── Classification Report
   ├── 2D Decision Boundary Visualization (PCA)
   └── Learning Curves
## 💡 Key Insights

- **Strong skewness** in several features was identified and addressed during the EDA phase.
- **Random Forest-based feature importance** revealed that features like `radius_mean`, `texture_mean`, and `perimeter_worst` are highly predictive.
- **PCA** enabled effective dimensionality reduction and helped us visualize decision boundaries in 2D space.
- The **RBF kernel SVM** slightly outperformed the **Linear kernel SVM** in terms of cross-validation accuracy, highlighting its strength in capturing nonlinear patterns.

---
```
## ✅ Key Takeaways

- Hands-on with all standard data transformation techniques.
- Clean, modular code with reusable functions.
- Statistical and ML-based outlier detection methods.
- Insightful visualizations at every step.

---

## 🤝 Contribution

Want to contribute?
- ⭐ Star this repo to support the work
- 🐞 Found a bug or improvement? Open an issue
- 🚀 Fork and submit a pull request with enhancements

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

## 🚀 Future Work

- **Feature Importance Analysis** using more interpretable models like SHAP or LIME.
- **Dimensionality Reduction** with advanced techniques such as **UMAP**.
- Automate **Model Training Pipelines** using **Optuna** or **AutoML**.

---

## 📁 How to Use

**1. Clone the Repo**
```bash
git clone https://github.com/Chaiithra/SVM-Breast-Cancer-Prediction.git
```

**2. Navigate to Project Directory**
```bash
cd breast-cancer-prediction
```

**3. Open the Notebook**
```bash
jupyter notebook SVM-Breast-Cancer-Prediction.ipynb
```

---

### 🙌 Acknowledgements
- **Dataset**: [Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)  
- **Libraries Used**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Label Encoders, etc.

---

### 📧 Contact  
Made with ❤️ by **Chaiithra Thota**  

- 🔗 [Connect on LinkedIn](https://www.linkedin.com/in/chaiithrathota/)  
- 🐦 [Connect on Twitter](https://x.com/DebugDiary_)  

