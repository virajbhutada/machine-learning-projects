

# Image Classification Projects: SVM for Cats & Dogs, and Decision Tree for Iris Species

## Overview
This repository includes two machine-learning projects focused on classification tasks:
1. **Cat and Dog Classification** using Support Vector Machine (SVM).
2. **Iris Species Prediction** with a Decision Tree Classifier.

Both projects demonstrate data preprocessing, feature selection, model training, evaluation, and parameter optimization.

---

## Table of Contents
1. [Cat and Dog Classification](#cat-and-dog-classification)
    - [Dataset](#dataset)
    - [Data Preprocessing](#data-preprocessing)
    - [Model Training and Optimization](#model-training-and-optimization)
    - [Results and Evaluation](#results-and-evaluation)
2. [Iris Species Prediction](#iris-species-prediction)
    - [Dataset and Introduction](#dataset-and-introduction)
    - [Data Analysis and Feature Selection](#data-analysis-and-feature-selection)
    - [Model Building and Evaluation](#model-building-and-evaluation)
3. [Technologies Used](#technologies-used)
4. [Conclusion](#conclusion)

---

## Cat and Dog Classification

### Dataset
The dataset, sourced from [Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data), contains 25,000 labeled images, evenly split between cats and dogs.

### Data Preprocessing
- **Resizing**: All images are resized for uniformity.
- **Feature Extraction**: Histogram of Oriented Gradients (HOG) used to capture shape features.

```python
from skimage.feature import hog
hog_features = hog(image, orientations=9, pixels_per_cell=(8, 8), cells_per_block=(2, 2))
```

### Model Training and Optimization
- **Model**: SVM with initial linear kernel, optimized via Grid Search to an RBF kernel with principal component analysis.
- **Result**: Final model achieved ~67.57% accuracy.

### Results and Evaluation
The confusion matrix and accuracy provided insights into model performance.

---

## Iris Species Prediction

### Dataset and Introduction
The [Iris dataset](https://www.kaggle.com/uciml/iris), introduced by Ronald Fisher, includes 150 samples representing three species (*Setosa*, *Versicolor*, *Virginica*).

### Data Analysis and Feature Selection
- **EDA**: Pair plots highlighted petal dimensions as key discriminators among species.
- **Feature Selection**: Petal Length and Width chosen for superior classification accuracy.

```python
selected_features = iris_db[['PetalLengthCm', 'PetalWidthCm']]
species_labels = iris_db['Species']
```

### Model Building and Evaluation
A Decision Tree Classifier was trained, achieving high accuracy using only the selected petal features.

```python
from sklearn.tree import DecisionTreeClassifier
dt_model = DecisionTreeClassifier().fit(selected_features, species_labels)
```

---

## Technologies Used
- **Python**: Core programming language.
- **Scikit-Learn**: Machine learning algorithms and evaluation tools.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive project environment.

---

## Conclusion
These projects illustrate key principles of machine learning:
- **Image Classification** benefits from high-dimensional features and kernel optimization.
- **Species Classification** leverages simpler data and interpretable models.

Future improvements could explore deep learning for image classification and enhanced feature engineering for tabular data.

