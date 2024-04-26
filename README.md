# Crop Prediction Web Application



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

1. **Random Forest Classifier**: This model is trained using a random forest algorithm, which is an ensemble learning method for classification. It achieves an accuracy of approximately 85% on the test dataset.

2. **Support Vector Machine (SVM)**: Another model utilized is the Support Vector Machine, a supervised learning algorithm used for classification tasks. The SVM model achieves an accuracy of around 80% on the test dataset.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/crop-prediction.git
