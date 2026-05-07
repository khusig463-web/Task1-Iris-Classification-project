#  Iris Flower Classification Project

##  Objective

The objective of this project is to build a machine learning model that can classify iris flowers into different species based on their physical features.

---

##  Dataset

The dataset used in this project is the Iris dataset.

 Dataset Link:
https://www.kaggle.com/datasets/bhanupratapbiswas/iris-classification-dataset

---

##  Features Used

The model uses the following input features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

##  Target Variable

* Species (Setosa, Versicolor, Virginica)

---

##  Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

##  Steps Performed

### 1. Data Loading

The dataset was loaded using Pandas.

### 2. Exploratory Data Analysis (EDA)

* Data overview using head(), info(), describe()
* Missing value check

### 3. Data Visualization

* Scatter Plot
* Histogram
* Boxplot
* Pairplot

### 4. Data Preprocessing

* Features and target split
* Train-test split

### 5. Model Training

Three models were trained:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree

### 6. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

---

##  Best Model

K-Nearest Neighbors (KNN) performed best with the highest accuracy.

---

##  Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score

---

##  Model Saving

The trained model was saved using Joblib as:

iris_model.pkl

---

##  Example Prediction

Input:
[5.1, 3.5, 1.4, 0.2]

Output:
Setosa

---

##  How to Run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Run all cells step by step
3. Train the model
4. Use the saved model (.pkl file) for prediction

---

##  Project Files

* iris_project.ipynb (Notebook)
* iris_model.pkl (Saved Model)
* README.md (Project Documentation)

---

##  Libraries Documentation Links

Pandas: https://pandas.pydata.org/docs/
NumPy: https://numpy.org/doc/
Matplotlib: https://matplotlib.org/stable/contents.html
Seaborn: https://seaborn.pydata.org/
Scikit-learn: https://scikit-learn.org/stable/
Joblib: https://joblib.readthedocs.io/en/latest/

---
## Google Drive Link

https://drive.google.com/drive/folders/15Ndq5v4jalCBsuzwy9inkh6Xtng6psJy?usp=sharing

---

## Conclusion

This project successfully demonstrates the use of machine learning algorithms to classify iris flower species with high accuracy. Among all models, KNN performed the best.

---

## Author
Khushi Gupta
