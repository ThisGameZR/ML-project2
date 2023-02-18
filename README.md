# Project Description

This project aims to develop a machine learning model that can classify fruits into 4 different categories based on their features, which include mass, width, height, and color score. The expected output of the model is the predicted class of the fruit.

## Data Preprocessing

To accomplish this task, we will perform data preprocessing on the given dataset by:

1. Combining `mass` and `width` into a new feature called `mass_width`, as it has a higher correlation with the expected class.
2. Handling missing values, normalizing the data, and performing other preprocessing steps depending on the specific characteristics of the dataset.

## Model Development

Next, we will build a machine learning model to predict the class of the fruits. As the dataset contains multiple classes, we will use a classification algorithm such as K-nearest neighbors (KNN). The steps involved in model development are:

1. Creating a KNN classifier using Scikit-learn.
2. Evaluating the performance of the classifier using cross-validation.
3. Tuning the hyperparameters of the KNN classifier to find the best combination of parameters that yields the highest accuracy.

## Model Export

Once we have developed the machine learning model, we will export it as a `.pkl` file using the joblib module in Scikit-learn. The `.pkl` file can be loaded and used to make predictions on new data in the future.

Overall, this project provides an opportunity to develop and implement a machine learning solution to a real-world problem and gain practical experience in data preprocessing, model development, and model evaluation.
