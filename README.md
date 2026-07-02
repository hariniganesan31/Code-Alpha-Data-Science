# Iris Flower Classification Using Machine Learning

## Project Overview

This project uses Machine Learning to classify Iris flowers into three species:

* Setosa
* Versicolor
* Virginica

The model uses flower measurements as input data and predicts the species of the flower.

## Dataset

This project uses the Iris dataset available directly from the Scikit-learn library using `load_iris()`.

No separate CSV dataset file is required.

The dataset contains 150 flower records from three Iris species:

* Setosa
* Versicolor
* Virginica

## Input Features

The following flower measurements are used as input features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## Output Classes

The model predicts one of the following flower species:

* Setosa
* Versicolor
* Virginica

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Machine Learning Algorithm

This project uses the Decision Tree Classifier algorithm.

The model is trained using Iris flower measurements and predicts the flower species based on those measurements.

## Project Steps

1. Load the Iris dataset using Scikit-learn.
2. Separate flower measurements and species labels.
3. Split the dataset into training and testing data.
4. Train the Decision Tree Classifier model.
5. Predict the species using test data.
6. Evaluate the model using accuracy score, classification report, and confusion matrix.

## Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

The model achieves approximately 96% to 100% accuracy.

## Project Files

```text
Iris-Flower-Classification/
│
├── iris_classification.py
├── README.md
```

## Installation

Install the required libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## How to Run

Run the Python file using:

```bash
python iris_classification.py
```

## Expected Output

The program displays:

* First five rows of the dataset
* Accuracy score
* Classification report
* Confusion matrix graph

## Conclusion

This project demonstrates supervised machine learning classification. The Decision Tree model uses sepal and petal measurements to classify Iris flowers as Setosa, Versicolor, or Virginica.
