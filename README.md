# Breast-Cancer-Prediction-Model-using-Machine-Learning
This project implements a machine learning model to predict whether a breast tumor is malignant or benign based on a set of features extracted from the digital images of breast mass

# 🎗️ Breast Cancer Prediction Web App 🎗️

A machine learning-powered web application for predicting breast cancer diagnoses (Malignant or Benign) based on tumor features. Built using Python, Flask, and a trained ML model — with a clean and intuitive Bootstrap interface.

---

## 📊 Project Overview

Early detection of breast cancer can save lives. This project uses a supervised machine learning model trained on a breast cancer dataset to predict whether a tumor is malignant or benign based on various medical measurements.

Users can enter tumor-related features into a web form, and the app instantly predicts the diagnosis.

---

## 🚀 Features

- 📊 Exploratory Data Analysis (EDA) of the breast cancer dataset
- 📚 Data preprocessing including handling missing values and feature scaling
- 🧠 Machine Learning model training and evaluation
- 🌐 Web interface powered by Flask and Bootstrap
- 📈 Real-time prediction based on user input
- 🩺 Clear diagnostic messages with informative visuals

---

## 📈 Exploratory Data Analysis 📉

A few key visualizations from the analysis:

### 🔍 Distribution of Diagnosis



**Observation:** The dataset has more benign cases than malignant, which affects model training and performance evaluation.

---

### 📊 Feature Correlation Heatmap



**Observation:** Certain features like `radius_mean`, `area_mean`, and `concavity_mean` have a high positive correlation with the diagnosis outcome.

---

### 📊 Important Features (Feature Importance)



**Observation:** Top contributing features to the prediction include `radius_worst`, `perimeter_worst`, and `concave points_worst`.

---

## 🧠 Model Performance

**Accuracy:** `97.7%`  
**Precision:** `96.5%`  
**Recall:** `98.2%`  
**F1-Score:** `97.3%`

---

## 📊 Sample Predictions

| Input Features (scaled)                                           | Predicted Diagnosis |
|:-----------------------------------------------------------------:|:------------------|
| `14.8, 20.3, 96.7, 674.0, 0.1, 0.18, 0.18, 0.08, 0.2, 0.07`      | Malignant (Cancrouse) |
| `9.5, 15.4, 59.0, 273.9, 0.09, 0.08, 0.04, 0.02, 0.18, 0.06`     | Benign (Not Cancrouse) |

---

## 📸 Demo Screenshots

| Homepage                     | Prediction Result |
|:----------------------------|:----------------|
| ![Homepage](static/images.jpg) | Example: "Not Cancrouse" or "Cancrouse" card display |

---

## 📁 Project Structure

├── app.py # Flask app backend ├── model.pkl # Trained ML model ├── breast cancer.csv # Breast cancer dataset ├── index.html # Web UI template ├── static/ │ ├── images.jpg # Header image │ ├── img1.png # Image for positive diagnosis │ └── img2.jpg # Image for negative diagnosis ├── images/ # Visual outputs from notebook │ ├── diagnosis_distribution.png │ ├── correlation_heatmap.png │ └── feature_importance.png ├── Breast Cancer Project Analysis Report.docx ├── Breast Cancer Prediction using Machine Learning.ipynb └── README.md


---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ⭐ Acknowledgements

- [UCI Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- Scikit-learn documentation
- Flask and Bootstrap communities

---

## 📥 Clone & Run

```bash
git clone https://github.com/your-username/breast-cancer-prediction.git
cd breast-cancer-prediction
pip install -r requirements.txt
python app.py
http://127.0.0.1:5000/
```

---

## 📦 Next Step for You:
You just need to:

- Export the EDA plots from your notebook (`.ipynb`) as PNG images.
- Save them in a `/images/` folder inside your project directory.
- Reference them in the `README.md` as shown above.

Would you like me to also write a Python code snippet to generate those specific plots for you inside your notebook if you haven't already? I can hook you up with those too! 🚀
