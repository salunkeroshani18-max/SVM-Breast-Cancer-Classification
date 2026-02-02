# SVM-Breast-Cancer-Classification
Breast Cancer Classification using Support Vector Machine (SVM) with hyperparameter tuning and ROC-AUC evaluation

# SVM – Breast Cancer Classification

## 📌 Project Overview
This project focuses on classifying breast cancer tumors as **Malignant** or **Benign** using the **Support Vector Machine (SVM)** algorithm. The model is trained using a medical dataset (`data.csv`) and evaluated using standard performance metrics.

---

## 📂 Dataset
- File: `data.csv`
- Target column: `diagnosis`
  - M → Malignant
  - B → Benign
- Unnecessary columns such as `id` were removed during preprocessing.

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib

---

## ⚙️ Steps Performed
1. Loaded and explored the dataset
2. Performed data preprocessing and feature scaling
3. Split data into training and testing sets
4. Trained SVM with Linear and RBF kernels
5. Tuned hyperparameters using GridSearchCV
6. Evaluated model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
   - ROC Curve and AUC Score
7. Saved the trained model and scaler

---

## 📊 Model Evaluation
- The RBF kernel performed better than the linear kernel.
- ROC-AUC score indicates strong classification capability.
- Feature scaling significantly improved SVM performance.

---

## 💾 Saved Files
- `svm_model.pkl` – Trained SVM model
- `scaler.pkl` – StandardScaler object

---

## 🎯 Learning Outcomes
- Understanding of Support Vector Machines
- Importance of feature scaling
- Hyperparameter tuning using GridSearchCV
- Model evaluation using ROC-AUC
