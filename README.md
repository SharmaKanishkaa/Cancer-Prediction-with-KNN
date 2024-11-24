# 🦠 Breast Cancer Prediction with KNN & Advanced Models

Welcome to the **Breast Cancer Prediction Notebook**! This project dives into the **Breast Cancer Dataset**, exploring it through **EDA (Exploratory Data Analysis)** and building models to predict cancer diagnosis with high accuracy. 🚀

---

## 📋 **Project Overview**

This dataset contains patient data, including visual characteristics of diagnosed cancers. Our goal is to classify the type of cancer—**Malignant (M)** or **Benign (B)**—using machine learning techniques.

### 📚 **Dataset Features**  
- **ID**: A unique identifier for each patient.  
- **Diagnosis**: Cancer type (**M**: Malignant, **B**: Benign).  
- **Visual Characteristics** (e.g., `radius_mean`, `texture_mean`, `area_mean`): Numerical features representing the average visual properties of cancer.  

---

## ⚙️ **Workflow**

1. **Exploratory Data Analysis (EDA):**  
   - Visualized feature distributions and correlations to understand relationships in the data.  
   - Identified that certain features, like `radius_mean` and `area_mean`, are strongly correlated with the diagnosis.  

2. **Model Building:**  
   - **Gaussian Naive Bayes:** Initial classification model. Performance was decent but not optimal.  
   - **K-Nearest Neighbors (KNN):**  
     - Achieved **94% accuracy** after tuning hyperparameters with **GridSearchCV**.  
     - KNN proved effective at leveraging neighborhood relationships for classification.  
   - **Cross-Validation:** Ensured consistent performance across multiple splits of the data.  
   - **ANN (MLPClassifier):** Achieved a **100% accuracy** with a simple Artificial Neural Network, outperforming other models.

---

## 🛠️ **Techniques and Tools**

- **Libraries:** `pandas`, `NumPy`, `Matplotlib`, `seaborn`, `scikit-learn`  
- **Models Used:**  
  - Gaussian Naive Bayes  
  - K-Nearest Neighbors (KNN)  
  - Artificial Neural Network (ANN - MLPClassifier)  

---

## 🎯 **Results**

| **Model**                       | **Accuracy** |
|---------------------------------|--------------|
| Gaussian Naive Bayes            | ~90%         |
| KNN (GridSearchCV Tuned)        | 94%          |
| Cross-Validation with KNN       | 94%          |
| ANN (MLPClassifier)             | **100%**     |

---

## ✨ **Key Insights**

- **KNN** is a reliable model for this dataset, achieving consistent results across folds.  
- By using **ANN (MLPClassifier)**, the model performance improved to perfection, demonstrating the power of deep learning for complex datasets.  
- **EDA** was crucial in identifying the most informative features for diagnosis.  
