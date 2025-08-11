
#  Machine Learning Model Comparison Project

##  Overview

This project compares different **machine learning models** for classification using a dataset loaded from `data.csv`.
We start by exploring the data with **Pandas**, clean it, check for outliers, and then train several models to evaluate their performance.



##  Dataset

* **File:** `data.csv`
* **Description:** Contains multiple features (independent variables) and one target (dependent variable) for classification.
* **Steps Taken:**

  * Checked for missing values
  * Summarized dataset statistics
  * Detected outliers



##  Tools Used

* **Language:** Python
* **Libraries:**

  * Data Handling: `pandas`, `numpy`
  * Visualization: `matplotlib`, `seaborn`
  * Modeling: `scikit-learn`
  * Others: `warnings`



##  Project Workflow

### 1️ Data Exploration

* Loaded the dataset with Pandas
* Viewed the first rows and dataset shape
* Checked for:

  * Missing values
  * Statistical summary
  * Outliers



### 2️ Model Training

We trained and compared the following models:

1. **Logistic Regression**
2. **Support Vector Machine (Linear Kernel)**
3. **Support Vector Machine (RBF Kernel)**
4. **Decision Tree**
5. **K-Nearest Neighbors (KNN)**



### 3️ Evaluation

* Split data into **training** and **testing** sets
* Evaluated each model using:

  * Accuracy
  * Confusion matrix
  * Classification report



##  Example Plots

* Heatmaps for correlations
* Outlier visualizations
* Confusion matrices for model performance



