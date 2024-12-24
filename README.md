This repository implements a Credit Card Fraud Detection system using machine learning and web-based visualization. The project integrates a Flask application with data analysis and
modeling pipelines to detect fraudulent transactions and visualize results.

Project Overview
The project uses a dataset of credit card transactions (creditcard.csv) to develop and evaluate a K-Nearest Neighbors (KNN) classification model. It includes features for data preprocessing,
machine learning, and web-based interaction. Users can visualize the data, test sample transactions, and view performance metrics through a Flask web application.

Key Components

1. Dataset:
   The creditcard.csv file contains anonymized credit card transaction data, including time, amount, and class labels (0 for normal and 1 for fraudulent transactions).

2. Machine Learning Pipeline:
   Implemented in KNNCreditCardFraudDetection.ipynb, this pipeline preprocesses the data, splits it into training and testing sets, and trains a KNN classifier. It evaluates the model using metrics such as accuracy, precision, recall, and F1 score.

3. Flask Application:
   The app.py file powers a web application that allows users to:

   -> Visualize the dataset with histograms, scatter plots, and other statistical summaries.
   -> Predict transaction outcomes (fraudulent or normal) by testing predefined inputs.
   -> View model performance metrics through an interactive interface.
   
Features:

 -> Data Visualizations: Histograms and scatter plots (2D and 3D) to explore the distribution of transaction data.
 -> Interactive Web Interface: Powered by Flask and Bootstrap, enabling user-friendly navigation.
 -> Real-Time Predictions: Test transactions to classify them as normal or fraudulent using the trained KNN model.
 
How to Use:

Run the Flask application:

bash
Copy code
python app.py

Access the web interface at http://127.0.0.1:5000/.

Notes:

The repository includes visualization scripts commented out in app.py for performance reasons.
Large files like creditcard.csv may require Git LFS or external storage due to GitHub's size limitations.
This project demonstrates a complete workflow for detecting and analyzing credit card fraud while offering interactive features for exploration and real-time testing.
