# Iris Flower Classification

This project classifies iris flowers into one of three species: Setosa, Versicolour, or Virginica, based on the length and width of their sepals and petals. The classification is performed using various machine learning algorithms.

## Project Overview

The Iris dataset, a classic dataset in the field of machine learning, is used for this project. The dataset contains 150 samples with four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Each sample is labeled with one of three species of iris flowers.

## Models Used

The following machine learning algorithms were used to build and evaluate models:
1. **K-Nearest Neighbors (KNN)**
2. **Decision Trees (CART)**
3. **Linear Discriminant Analysis (LDA)**
4. **Logistic Regression**
5. **Gaussian Naive Bayes**

The model performances were evaluated using accuracy scores. The results for each algorithm are as follows:
- **KNN**: 0.9 accuracy
- **CART**: 0.9 accuracy
- **LDA**: 0.967 accuracy
- **Logistic Regression**: 0.8 accuracy
- **Naive Bayes**: 0.833 accuracy

## Project Structure

- `iris_flower_classification.ipynb`: Contains the code for loading the dataset, training models, and evaluating their performance.

## Installation

To run this project, you'll need the following dependencies:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage

To use the project, open the Jupyter notebook and run the cells. The notebook walks you through loading the dataset, splitting it into training and validation sets, training various classifiers, and evaluating their accuracy.
