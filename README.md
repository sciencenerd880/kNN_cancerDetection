# Breast Cancer Diagnostic Classifier using KNN

## Objective
This project aims to create a classifier using the K-Nearest Neighbors algorithm to diagnose breast cancer as malignant or benign using the Breast Cancer Wisconsin (Diagnostic) Database.
Explore: to visualize the different predicition scores with different test splits
Select: to choose the best model or optimal train-test split with best performance
<p align="center">
 <img src="/assets/img/background.png" width="450" height="300">
</p>

## Dataset
The dataset used is the Breast Cancer Wisconsin (Diagnostic) Database. It includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

**Dataset Characteristics:**

    :Number of Instances: 569

    :Number of Attributes: 30 numeric, predictive attributes and the class

    :Attribute Information:
        - radius (mean of distances from center to points on the perimeter)
        - texture (standard deviation of gray-scale values)
        - perimeter
        - area
        - smoothness (local variation in radius lengths)
        - compactness (perimeter^2 / area - 1.0)
        - concavity (severity of concave portions of the contour)
        - concave points (number of concave portions of the contour)
        - symmetry
        - fractal dimension ("coastline approximation" - 1)

        The mean, standard error, and "worst" or largest (mean of the three
        worst/largest values) of these features were computed for each image,

## Key Learnings
- Understanding and application of the K-Nearest Neighbors algorithm.
- Data preprocessing and feature analysis.
- Model evaluation and performance metrics.

## Results
A summary of the model's performance and accuracy in classifying breast cancer.
Select: to choose the best model or optimal train-test split with best performance

<img src="/assets/img/tsplit_score.png" width="350" height="300">

## Instructions
Detailed instructions on how to run the project are provided in the notebooks and scripts.

## Requirements
Python dependencies required to run this project are listed in `requirements.txt`.

pip install -r requirements.txt

