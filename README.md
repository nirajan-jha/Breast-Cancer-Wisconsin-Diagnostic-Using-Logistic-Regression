# Breast-Cancer-Wisconsin-Diagnostic-Using-Logistic-Regression

## Overview
The Breast Cancer Wisconsin (Diagnostic) dataset is a well-known collection of data used extensively in machine learning and medical research. It originates from digitized images of fine needle aspirates (FNA) of breast masses. The dataset contains various features extracted from these images, which can aid in the diagnosis of breast cancer.

## Aim:
Based on different factors, a model is created to Predict whether the cancer is benign or malignant

## About the Dataset
Attribute Information:
Diagnosis (Target Variable):
The diagnosis column contains two classes: Malignant (M =1 ) and Benign (B = 0). These labels represent whether the tumor is cancerous (malignant) or non-cancerous (benign). This is the target variable we want to predict.

Ten real-valued features are computed for each cell nucleus:
a. Radius (Mean of Distances): Represents the average distance from the center to points on the tumor’s perimeter.

b. Texture (Standard Deviation of Gray-Scale Values): Measures the variation in gray-scale intensity of the tumor mass.

c. Perimeter: The total length of the tumor’s boundary.

d. Area: Represents the area of the tumor.

e. Smoothness (Local Variation in Radius Lengths): Describes the variation in radius lengths within the tumor.

f. Compactness (Perimeter^2 / Area - 1.0): Combines information about the tumor’s shape (perimeter) and size (area).

g. Concavity (Severity of Concave Portions): Measures the severity of concave regions in the tumor contour.

h. Concave Points (Number of Concave Portions): Counts the number of concave portions in the tumor boundary.

i. Symmetry: Reflects the symmetry of the tumor shape.

j. Fractal Dimension (“Coastline Approximation” - 1): Describes the complexity of the tumor boundary.

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

Remember that accurate diagnosis requires a combination of clinical expertise and machine learning. While the dataset provides valuable insights, it’s crucial to collaborate with medical professionals for accurate predictions and patient care.

## Implemented Machine Learning Algorithm:
Logistic Regression
