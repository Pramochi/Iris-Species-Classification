# Iris Species Classification


![image](https://github.com/user-attachments/assets/af42484d-726f-4390-a155-dec9741a8583)     -  **Iris setosa**

![image](https://github.com/user-attachments/assets/c62d40ae-2657-4615-ac82-09e24319e3ce)     -  **Iris versicolor**

![image](https://github.com/user-attachments/assets/fd9cf55e-3832-4a40-85a3-fff91f9e07e4)     -  **Iris virginica**



---

# Iris Species Classification 

This project showcases the classification of Iris flowers into three species—**Setosa**, **Versicolor**, and **Virginica**—using four key features: **sepal length**, **sepal width**, **petal length**, and **petal width**. **Logistic Regression** is employed as the classification algorithm, and the model's performance is assessed using a range of evaluation metrics.



## Problem Statement

The task is to classify iris flowers into one of the three species:
- Setosa
- Versicolor
- Virginica

Using the following features:
- Sepal length
- Sepal width
- Petal length
- Petal width


## Solution Approach

The steps undertaken in this project are as follows:

 1.**Load the Dataset**: Import the Iris dataset from `sklearn.datasets`.
 2.**Split the Data**: Divide the dataset into training and testing sets using `train_test_split`.
 3.**Data Preprocessing**: Normalize the feature values by applying `StandardScaler`.
 4.**Model Training**: Train a Logistic Regression classifier on the training data.
 5.**Model Evaluation**: Assess the classifier's performance on the test data using accuracy and other relevant metrics.
 6.**Visualization**: Illustrate the model's performance with a confusion matrix.

## Requirements

Make sure you have the following libraries installed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Dataset

The Iris dataset is a classic dataset provided by **scikit-learn**. It consists of 150 samples, each with 4 features and a corresponding label ().

## Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/anushka-cseatmnc/iris-species-classification.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd iris-species-classification
   ```

3. Run the Python script:
   ```bash
   python iris_classification.py
   ```

## Evaluation

The model's performance is assessed using the following metrics:
- **Accuracy**: The proportion of correctly predicted instances relative to the total number of instances.
- **Classification Report**: Includes precision, recall, F1-score, and support for each class.
- **Confusion Matrix**: A tabular representation comparing the true labels to the predicted labels for each class.

**Output**:- on local machine


**Accuracy: 0.93**

Confusion Matrix:
 [[10  0  0]
 [ 0  9  1]
 [ 0  1  9]]
Classification Report:
               precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       0.90      0.90      0.90        10
   virginica       0.90      0.90      0.90        10

    accuracy                           0.93        30
   macro avg       0.93      0.93      0.93        30
weighted avg       0.93      0.93      0.93        30

![Figure_2](https://github.com/user-attachments/assets/bc91bef9-c91f-4695-ab58-b3fa4dcbd98c)


![Figure_1](https://github.com/user-attachments/assets/99560dfd-8777-4ff0-87c9-847d3f2e5f23)


## Visualization

The confusion matrix is visualized using **Seaborn**:

![Figure_2](https://github.com/user-attachments/assets/bc91bef9-c91f-4695-ab58-b3fa4dcbd98c)

## Conclusion

This project highlights the effective classification of Iris species using logistic regression. The model demonstrates high accuracy of about **93%** and strong performance on the testing dataset, showcasing its suitability for this well-balanced classification task.

---
