## 📌 Project Title
# Mobile Banking Customer Satisfaction Prediction using Machine Learning

This project focuses on predicting **customer satisfaction in Mobile Banking Services** using Machine Learning techniques.  
The dataset includes user behavior, online transaction usage, telecom operator preference, service ratings, and satisfaction labels.

The goal is to classify whether a customer is **Good** or **Average**,  enhance customer experience.


## 🎯 Objectives

- Analyze mobile banking customer behavior  
- Identify factors affecting satisfaction  
- Build predictive ML models  
- Improve digital financial services  
- Support business decision making  



## 📂 Dataset Features

- Dataset collected from kaggle


| Feature Name | Description |
|-------------|-------------|
| useOnlineTransaction | Uses online/mobile transaction or not |
| WhichOperators | Customer mobile operator |
| SingleOperatorRating | Rating if using one operator |
| operatorRating1 | Rating of Operator 1 |
| operatorRating2 | Rating of Operator 2 |
| operatorRating3 | Rating of Operator 3 |
| operatorRating4 | Rating of Operator 4 |
| Satisfaction | Customer satisfaction score |
| classlabel | Target label |

> Note: Some duplicated column names were cleaned during preprocessing.


## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Programming |
| Pandas | Data Analysis |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Charts |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development |

---

## 🤖 Machine Learning Models

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine  
- K-Nearest Neighbors  
- XGBoost (Optional)

---

## 📊 Evaluation Metrics

- Accuracy Score  
- Precision  
- Recall  
- F1 Score  
- ROC AUC Score  
- Confusion Matrix  


## 🔮 Future Improvements
- Deploy using Streamlit
- Real-time Customer Dashboard
- Sentiment Analysis on Feedback
- Telecom-wise Satisfaction Analytics
- Deep Learning Models

## 📈 Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
EDA & Visualization
      ↓
Feature Engineering
      ↓
Train/Test Split
      ↓
Model Training
      ↓
Evaluation
      ↓
Prediction

mobile-banking-satisfaction-ml/
│── data/
│   └── dataset.csv
│── notebooks/
│   └── analysis.ipynb
│── models/
│   └── model.pkl
│── app.py
│── requirements.txt
│── README.md
