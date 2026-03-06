# Breast Cancer Classification Using Machine Learning

## Project Overview
This project applies machine learning techniques to classify breast tumors as **malignant or benign** using measurements derived from breast cell nuclei.

The goal of this project was to practice building a complete machine learning workflow using Python, including data exploration, preprocessing, model training, evaluation, and visualization of results.

The final results are presented through a **Power BI dashboard** and shared through **GitHub** as a portfolio project.

---

## Tools and Technologies
This project was built using:

- Python
- Jupyter Notebook (VS Code)
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- Power BI
- GitHub

---

## Dataset
This project uses the **Breast Cancer Wisconsin Diagnostic Dataset** available through scikit-learn.

The dataset contains numeric measurements calculated from digitized images of breast mass cell nuclei, including features such as:

- radius
- texture
- perimeter
- area
- smoothness
- compactness
- symmetry

Each observation is labeled as either:

- **Malignant**
- **Benign**

---

## Project Workflow

### 1. Data Loading
The dataset was loaded using the scikit-learn dataset library and converted into a pandas DataFrame.

### 2. Exploratory Data Analysis (EDA)
Initial analysis included:

- examining dataset structure
- checking for missing values
- analyzing summary statistics
- visualizing feature distributions
- evaluating class balance

### 3. Data Preparation
The dataset was prepared for machine learning by:

- separating feature variables and target variable
- splitting the dataset into training and testing sets
- scaling features for logistic regression

### 4. Machine Learning Models
Two classification models were trained:

- Logistic Regression
- Random Forest Classifier

### 5. Model Evaluation
Models were evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix

### 6. Feature Importance
Random Forest feature importance was used to identify which variables contributed most to the predictions.

### 7. Data Visualization
Results were exported and visualized using **Power BI** to create a dashboard showing:

- class distribution
- model accuracy comparison
- most important predictive features

---

## Key Results
- Both models performed strongly on the classification task.
- Random Forest provided interpretable feature importance rankings.
- Measurements related to **radius, perimeter, and area** were among the strongest predictors.

---

## Project Structure
