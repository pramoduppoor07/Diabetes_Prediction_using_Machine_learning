

# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

This machine learning project uses the **PIMA Indians Diabetes Dataset** to predict whether a person is diabetic or not based on diagnostic measurements. The model is trained using a **Support Vector Machine (SVM)** classifier with a linear kernel.

---

## 📌 Project Overview

- Supervised binary classification task.
- Algorithm used: `SVM (Support Vector Machine)` from `scikit-learn`.
- Input features include medical attributes like glucose, BMI, insulin level, etc.
- Target variable: `Outcome` (0 = Non-Diabetic, 1 = Diabetic)

---

## 🔍 Dataset Information

- **Source**: PIMA Diabetes Dataset (`diabetes.csv`)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target**: Outcome (0: Not diabetic, 1: Diabetic)

---

## 🧪 Model Workflow

1. Load and analyze the dataset.
2. Preprocess data (standardization using `StandardScaler`).
3. Split dataset into training and testing sets.
4. Train an SVM classifier (`SVC` with `linear` kernel).
5. Evaluate model accuracy on both training and testing sets.
6. Make predictions for new input data.

---

## 🧠 Model Evaluation

- **Train Accuracy**: ~78%
- **Test Accuracy**: ~77%

(Note: Actual accuracy may vary slightly based on random state.)

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-svm.git
   cd Diabetes_Prediction

2. Run the Jupyter Notebook:
   ````bash
   jupyter notebook

---
## 💡 Future Improvements

- Tune hyperparameters using `GridSearchCV`.
- Try different SVM kernels (e.g., `rbf`, `poly`, `sigmoid`).
- Add confusion matrix and classification report for deeper evaluation.
- Deploy the model as a web app using **Flask** or **Streamlit**.

---

## 🙌 Acknowledgements

- [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
