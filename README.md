# 🏥 Hospital Patient Admission Prediction

## 📌 Overview

This project uses **Machine Learning** to predict whether a patient will be admitted to the hospital based on various factors like demographics, department referral, and waiting time.

---

## 🎯 Objective

* Analyze hospital patient data
* Build a predictive model for patient admission
* Improve hospital decision-making

---

## 📂 Dataset

The dataset includes:

* Patient demographics (Gender, Race)
* Department Referral
* Patient Wait Time
* Satisfaction Score
* Admission Flag (Target Variable)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Jupyter Notebook

---

## 🔧 Data Preprocessing

* Removed unnecessary columns (ID, Name)
* Converted date column into Year & Month
* Handled missing values
* Encoded categorical variables
* Converted all data into numeric format

---

## 📊 Exploratory Data Analysis (EDA)

* Correlation Heatmap
* Count Plot (Target Distribution)
* Histogram (Feature Distribution)
* Boxplot (Outlier Detection)

---

## 🤖 Models Used

### 1. Logistic Regression

* Baseline model
* Good for binary classification

### 2. Random Forest Classifier

* Improved accuracy
* Handles non-linear data better

---

## 📈 Model Evaluation

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-score
* ROC Curve & AUC Score

---

## 📊 Results

* Logistic Regression provides stable baseline performance
* Random Forest improves prediction accuracy
* Model successfully predicts patient admission

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/hospital-admission-prediction.git

# Navigate to folder
cd hospital-admission-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 📌 Project Structure

```
📁 hospital-admission-prediction
│── 📄 README.md
│── 📄 dataset.csv
│── 📄 model.ipynb
│── 📄 requirements.txt
```

---

## 🔮 Future Improvements

* Use advanced models like XGBoost
* Hyperparameter tuning
* Deploy as web application
* Use real-time hospital data

---

## 📚 Conclusion

This project demonstrates how machine learning can be applied in healthcare to predict patient admission and improve operational efficiency.

##

---

##
