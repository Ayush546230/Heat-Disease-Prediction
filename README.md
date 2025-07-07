# 🫀 Heart Disease Prediction using Machine Learning

Heart disease is one of the leading causes of death globally. Early prediction can save lives.  
This project uses **machine learning** techniques to predict whether a person has heart disease based on clinical features.

---

## 🚀 Run the Project

Click below to launch the notebook directly in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ayush546230/Heat-Disease-Prediction/blob/main/heart-disease-prediction.ipynb)

---

## 📁 Project Structure

📦 Heat-Disease-Prediction
├── heart-disease-prediction.ipynb # Main ML notebook
├── heart.csv # Dataset (UCI-based)
├── requirements.txt # Python dependencies (optional)
└── README.md # Project overview


---

## 📊 Dataset Information

- **Source:** UCI Machine Learning Repository  
- **Total Samples:** 303  
- **Target Column:** `target` (1 = heart disease, 0 = no disease)  
- **Features:**
  - `age`, `sex`, `cp` (chest pain type), `trestbps` (resting BP), `chol` (cholesterol)
  - `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`

---

## 🧠 ML Pipeline

✔️ **Data Preprocessing**  
✔️ **Exploratory Data Analysis (EDA)**  
✔️ **Feature Scaling & Encoding**  
✔️ **Model Training**
- Logistic Regression
- Random Forest
- SVM
- KNN

✔️ **Model Evaluation**
- Accuracy, Precision, Recall, F1-score
- ROC Curve & AUC

---

## ✅ Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 86%     |
| Random Forest       | 90%     |
| SVM                 | 88%     |
| KNN                 | 84%     |

---

## 🧪 How to Run

1. Open the Colab link above ☝️  
2. Upload the `heart.csv` file when prompted  
3. Run each cell in order to train and test the models

> No installation required. Just a browser and internet connection.

---

## 🚀 Future Improvements

- Streamlit Web App UI
- Model Deployment with Flask or FastAPI
- Add SHAP-based feature importance
- Optimize with GridSearchCV

---

## 🙋‍♂️ Author

**Ayush Srivastava**  
[GitHub](https://github.com/Ayush546230)

---

## 📄 License

This project is licensed under the **MIT License**.

---
