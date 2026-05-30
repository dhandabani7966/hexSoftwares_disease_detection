# hexSoftwares_disease_detection
Heart Disease Detection using Machine Learning  | Random Forest | 88% Accuracy | HexSoftware ML Internship Task  2
# ❤️ Heart Disease Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/ML-RandomForest-green)
![Accuracy](https://img.shields.io/badge/Accuracy-88%25-brightgreen)
![Internship](https://img.shields.io/badge/HexSoftwares-Internship-orange)

## 📌 Project Overview
This project uses Machine Learning to predict whether a patient
has heart disease based on clinical parameters like age, blood
pressure, cholesterol, and ECG results.

Built as part of the **HexSoftwares ML Internship Program — Task 2**.

---

## 🎯 Problem Statement
Heart disease is one of the leading causes of death worldwide.
Early detection using ML can help doctors identify high-risk
patients and take timely action.

---

## 📊 Dataset
- **Source**: UCI Heart Disease Dataset (via Kaggle)
- **Samples**: 1025 patients
- **Features**: 13 clinical features
- **Target**: 1 = Heart Disease, 0 = No Heart Disease

### Features Used:
| Feature | Description |
|---------|-------------|
| age | Age of patient |
| sex | Gender (1=Male, 0=Female) |
| cp | Chest pain type (0-3) |
| trestbps | Resting blood pressure |
| chol | Cholesterol level |
| fbs | Fasting blood sugar > 120 |
| restecg | Resting ECG results |
| thalach | Maximum heart rate |
| exang | Exercise induced angina |
| oldpeak | ST depression |
| slope | Slope of ST segment |
| ca | Number of major vessels |
| thal | Thalassemia type |

---

## 🤖 ML Models Used
| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~85% |
| **Random Forest** ✅ | **~88%** |

**Best Model: Random Forest Classifier**

---

## 🛠️ Tech Stack
- Python 3.10
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Gradio (UI)
- Google Colab

---

## 🚀 How to Run

### Option 1 — Google Colab
1. Open `heart_disease_detection.ipynb` in Google Colab
2. Upload `heart.csv` when prompted
3. Run all cells
4. Gradio UI will launch with a public link

### Option 2 — Local (Flask)
```bash
# Install dependencies
pip install -r requirements.txt

# Run Flask app
python app.py

# Open browser
http://localhost:5000
```

---

## 📸 Project Screenshots

> UI screenshot here — Gradio prediction form

---

## 📈 Results
- **Accuracy**: 88.29%
- **Precision**: 0.89
- **Recall**: 0.88
- **ROC-AUC**: 0.88

---

## 👤 Author
- **Name**: Dhandabani
- **Internship**: HexSoftwares ML Internship
- **Task**: Task 2 — Heart Disease Detection
- **LinkedIn**: [Your LinkedIn URL]
- **GitHub**: [Your GitHub URL]

---

## 🏢 Internship
This project was completed as part of the
**HexSoftwares Internship Program**.

> Innovate | Connect | Inspire
