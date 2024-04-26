# Crop Prediction Web Application

![Index Page](https://github.com/NarendranathChakraborty/Crop-Prediction/blob/main/WhatsApp%20Image%202024-04-26%20at%2011.23.36%20PM.jpeg)

This repository contains the source code for a web application that predicts the suitable crop based on input parameters such as Nitrogen, Phosphorus, Potassium, temperature, humidity, pH, and rainfall.

## Features

- Predicts the suitable crop based on input parameters.
- User-friendly interface with form inputs.
- Utilizes a machine learning model trained on crop data.
- Provides real-time prediction without the need for registration or login.

## Technologies Used

- Flask: Python-based web framework for backend development.
- HTML/CSS: Frontend design and layout.
- JavaScript: Enhancing user interactivity and form submission.
- Machine Learning: Utilizes a machine learning model for crop prediction.
- ngrok: Exposes the local server to the internet for testing purposes.

## Machine Learning Models

The crop prediction functionality is powered by machine learning models trained on crop data. The models are trained using historical data on various crop attributes and environmental factors. Currently, the following models are implemented:

## Machine Learning Models and Accuracy

The crop prediction functionality is powered by several machine learning algorithms, each offering different strengths and performance characteristics. Here's an overview of the algorithms used and their respective accuracies:

### Decision Tree (Accuracy: 90%)

Decision Tree is a popular algorithm for classification tasks. It works by partitioning the data into subsets based on feature values, aiming to create the purest subsets (homogeneous with respect to the target variable). Despite its simplicity, Decision Trees can capture complex relationships in the data.

### Naive Bayes (Accuracy: 99.09%)

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem with the assumption of independence between features. Despite its simplicity and the "naive" assumption, Naive Bayes often performs well in practice, particularly on text classification tasks.

### Support Vector Machine (SVM) (Accuracy: 97.73%)

Support Vector Machine is a powerful supervised learning algorithm used for classification and regression tasks. SVM finds the optimal hyperplane that best separates the classes in the feature space. It can handle both linear and non-linear data by using different kernel functions.

### Logistic Regression (Accuracy: 95.23%)

Logistic Regression is a widely-used statistical technique for binary classification. Despite its name, it is used for classification rather than regression. Logistic Regression models the probability of a binary outcome based on one or more predictor variables.

### Random Forest (Accuracy: 99.09%)

Random Forest is an ensemble learning method that constructs multiple decision trees during training and outputs the mode of the classes (classification) or mean prediction (regression) of the individual trees. It can handle high-dimensional data and is less prone to overfitting compared to individual decision trees.

Each algorithm has its strengths and weaknesses, and their performance may vary depending on the specific characteristics of the dataset and the problem at hand. By employing multiple algorithms, this web application ensures robustness and reliability in crop prediction.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/crop-prediction.git
