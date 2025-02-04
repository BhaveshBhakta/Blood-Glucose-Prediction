# Blood Glucose Prediction

## Project Overview
This project aims to predict blood glucose levels based on various factors including activity levels and other time-based features. The dataset used contains data about blood glucose readings and various activity measurements at specific time intervals. The project involves cleaning, preprocessing, feature selection, and the development of a machine learning model to predict future glucose levels based on historical data.

## Key Features
- **Data Preprocessing**: The dataset undergoes extensive cleaning, including missing value imputation, removal of low-variance columns, and encoding of categorical variables.
- **Feature Engineering**: Specific columns related to blood glucose levels and activities are selected, ensuring the model is trained on relevant data.
- **Outlier Removal**: Outliers are removed using the Interquartile Range (IQR) method to ensure the data used for training is clean.
- **Model Development**: A neural network (ANN) model is built using Keras, optimized with Adam optimizer and EarlyStopping for better performance.
- **Evaluation**: Model performance is evaluated using mean squared error (MSE), and hyperparameters are adjusted using callbacks like learning rate reduction and early stopping.

## Purpose and Applications
The goal of this project is to predict future blood glucose levels, which can be used in healthcare applications, especially for people with diabetes or those at risk of developing diabetes. Accurate prediction models can help patients better manage their condition by providing insights into their blood glucose fluctuations. Potential applications include:
- **Personalized Healthcare**: Tailored glucose management strategies.
- **Healthcare Monitoring**: Continuous prediction of glucose levels for remote monitoring.
- **Diabetes Prevention**: Helping individuals at risk to monitor their health and take preventive actions.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/BhaveshBhakta/Blood-Glucose-Prediction-Using-ANN.git
    ```

2. Navigate to the project folder:

    ```bash
    cd Blood-Glucose-Prediction-Using-ANN
    ```

3. Run the notebook 

## Collaboration

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.
