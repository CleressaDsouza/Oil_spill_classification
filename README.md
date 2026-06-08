
# Oil Spill Classification using Machine Learning

## Project Overview

This project focuses on classifying oil spills using Machine Learning techniques. The dataset is preprocessed, analyzed, and used to train multiple classification models to identify whether a sample represents an oil spill or not.

The project includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and evaluation
* Hyperparameter tuning
* Data visualization techniques

---

## Objective

The main objective of this project is to build an accurate classification model capable of detecting oil spills based on sensor and environmental data.

---

## Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset Information

The dataset contains multiple numerical features related to satellite or environmental measurements along with a target class label indicating oil spill presence.

### Key Steps Performed:

* Renamed columns dynamically (`f0`, `f1`, ..., `class`)
* Checked missing values
* Statistical analysis using `describe()`
* Correlation analysis
* Removed constant-value features
* Applied encoding where necessary

---

## Exploratory Data Analysis (EDA)

The following visualizations were performed:

* Class distribution plot
* Correlation heatmap
* PCA visualization
* Confusion matrix heatmap
* Feature importance visualization

These visualizations helped understand:

* Data balance
* Relationships between variables
* Important predictive features
* Class separability

---

## Data Preprocessing

The preprocessing pipeline included:

* Handling missing values using median imputation
* Encoding categorical variables using one-hot encoding
* Removing zero-variance features
* Feature scaling for PCA

---

## Machine Learning Models Used

### 1. Random Forest Classifier

* Ensemble-based classification model
* Used for primary prediction and feature importance analysis

### 2. Logistic Regression

* Linear classification algorithm
* Used for baseline comparison

### 3. Support Vector Machine (SVM)

* Kernel-based classification model
* Implemented using RBF kernel

---

## Model Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

  * Precision
  * Recall
  * F1-score

---

## Hyperparameter Tuning

`GridSearchCV` was used to optimize the Random Forest model parameters:

* Number of estimators
* Maximum depth
* Minimum samples split

This improved model performance through cross-validation.

---

## Results

The project successfully compared multiple machine learning models for oil spill classification. Random Forest produced strong performance and provided useful feature importance insights.

---

## Project Structure

```bash
├── oil-spill.csv
├── Oil_Spill_Classification.ipynb
├── README.md
```

---

## Future Improvements

* Implement Deep Learning models
* Perform advanced feature selection
* Use t-SNE for enhanced visualization
* Deploy the model using Flask or Streamlit
* Add real-time prediction support

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <repository-link>
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Run the Notebook

Open the Jupyter Notebook:

```bash
jupyter notebook
```

---

## Conclusion

This project demonstrates how machine learning techniques can be applied to environmental monitoring tasks such as oil spill detection. Through preprocessing, visualization, and model comparison, the project provides an end-to-end classification workflow.

---
