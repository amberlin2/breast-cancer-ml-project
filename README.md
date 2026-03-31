# 🎗️ Breast Cancer Classification Using Machine Learning

🎓 UNCG MSIA | Python | Machine Learning | Power BI  

🚀 End-to-end machine learning pipeline using healthcare data

---

## 📌 Project Overview
This project focuses on building machine learning models to classify whether a tumor is **benign or malignant** using breast cancer diagnostic data.

Given my background in healthcare and lab work, I wanted to explore how machine learning can assist in **early detection and risk assessment**, which are critical in improving patient outcomes.

This project is framed as a **supervised binary classification problem**, where the goal is to accurately predict cancer diagnosis based on clinical features. 

---

## 📊 Dataset
- Breast Cancer dataset (commonly used for diagnostic classification)
- Features include:
  - Tumor size and shape measurements  
  - Texture and smoothness  
  - Radius, perimeter, and area  
- Target:
  - **0 = Benign**
  - **1 = Malignant**

---

## 🛠️ Workflow

### 1. Data Cleaning & Exploration
- Checked for missing values and inconsistencies  
- Explored feature distributions and correlations  
- Identified key variables influencing diagnosis  

### 2. Feature Engineering
- Evaluated feature importance  
- Removed unnecessary or redundant features where applicable  

### 3. Preprocessing
- Scaled numerical features  
- Split data into training and testing sets  
- Ensured proper handling of class distribution  

---

## 🤖 Models Used
- Logistic Regression  
- Random Forest  
- XGBoost / KNN  

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

---

## 🔍 Key Results
- Random Forest provided strong overall performance  
- Logistic Regression performed well as a baseline model  
- High recall was critical to minimize false negatives (missing malignant cases)  
- Model performance highlighted the importance of balancing precision and recall in healthcare applications  

---

## 💡 Key Takeaways
- In healthcare, **false negatives are far more critical than false positives**  
- Simpler models like Logistic Regression can still perform very well  
- Feature scaling significantly impacts model performance  
- Evaluation metrics must align with real-world consequences, not just accuracy  

---

## 📊 Power BI Dashboard
In addition to the machine learning model, I developed a **Power BI dashboard** to visualize:

- Diagnosis distribution  
- Feature trends  
- Model insights  
- Patient-level patterns  

This demonstrates how machine learning outputs can be translated into **actionable, user-friendly insights** for stakeholders.
