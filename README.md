# 💚 Heart Disease Prediction

## 💡 Project Overview

This project aims to predict the likelihood of heart disease using machine learning. Various classification models, including **Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Naive Bayes, Decision Tree, and Random Forest**, are tested for performance and accuracy.

## 🔧 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Machine Learning Models)

## ⚖️ Problem Statement

The objective is to develop an **effective machine learning model** for classifying heart disease presence based on a dataset of medical parameters.

## 📅 Dataset

The dataset consists of patient health records with 14 key attributes. The "target" variable indicates the presence of heart disease (1 = disease, 0 = no disease).

### **Key Features:**

- **Age**
- **Sex**
- **Chest Pain Type**
- **Resting Blood Pressure**
- **Serum Cholesterol**
- **Fasting Blood Sugar**
- **Resting ECG Results**
- **Max Heart Rate Achieved**
- **Exercise Induced Angina**
- **ST Depression (Oldpeak)**
- **Slope of ST Segment**
- **Number of Major Vessels Colored by Fluoroscopy**
- **Thalassemia (Thal)**

## 🌍 Data Preprocessing

- Handling missing values
- Normalization & scaling
- Train-test split

## 💻 Model Development

The following models were trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Naive Bayes
5. Decision Tree
6. Random Forest

## 🔄 Model Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Random Forest       | 100%     |
| Decision Tree       | 100%     |
| KNN                 | 91%      |
| Naive Bayes         | 88%      |
| Logistic Regression | 86%      |
| SVM                 | 75%      |

## 📊 Results & Conclusion

- **Random Forest** performed the best with 100% accuracy.
- **SVM** performed the worst at 75% accuracy.
- Feature importance analysis helped determine which medical factors are most predictive of heart disease.

## 📑 Documentation

- **[Project Report](docs/heartdisease.pdf)**
- **[Presentation Slides](docs/project.pptx)**

## 🚀 Getting Started

### **1️⃣ Clone the Repository**

```sh
git clone git@github.com:MohdSafiya02/heart-disease-prediction.git
cd heart-disease-prediction
```

### **2️⃣ Install Dependencies**

```sh
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**

```sh
jupyter notebook heart-disease-prediction.ipynb
```

## 📈 Future Enhancements

- Deploy the model as a web app
- Improve model performance using advanced techniques
- Address class imbalance in the dataset

---
