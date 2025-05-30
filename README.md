# Breast Cancer Classification - Logistic Regression

This Jupyter Notebook (`Task4.ipynb`) provides an end-to-end implementation of a machine learning pipeline to classify tumors as **Malignant** or **Benign** using a dataset of breast cancer features.

## 🧠 Objective

To build a binary classifier using **Logistic Regression** that can predict whether a tumor is malignant or benign based on various medical measurements.

---

## 📁 Files

- `Task4.ipynb`: The main notebook containing the complete analysis and model.
- `data.csv`: The dataset used for training and evaluation.
- `Task4_modified_unaffectable.ipynb`: A version of the notebook with unimpactful code changes (e.g., improved comments and variable names).
- `README.md`: You are here.

---

## 📊 Dataset

The dataset consists of 33 columns with various features like:
- Radius, texture, perimeter, area, smoothness, compactness, etc.
- Target label: `diagnosis` (`M` = Malignant, `B` = Benign)

---

## 🔧 Steps Performed

1. **Data Loading**  
   Read the dataset into a pandas DataFrame.

2. **Exploratory Data Analysis (EDA)**  
   - Preview dataset
   - Check for missing values
   - Visualize correlations (optional)

3. **Data Preprocessing**  
   - Label encoding of target variable
   - Dropping unnecessary columns
   - Feature scaling with `StandardScaler`

4. **Model Training**  
   - Train-test split using `train_test_split`
   - Logistic Regression model fitting

5. **Evaluation**  
   - Confusion matrix
   - Classification report
   - ROC-AUC score and ROC curve

---

## 🛠 Requirements

To run the notebook, install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
