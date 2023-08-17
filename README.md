# Telco_customer_churn_prediction_ANN

Telco Customer Churn Prediction using Artificial Neural Network (ANN)
This repository contains code and resources for predicting customer churn in a Telco dataset using an Artificial Neural Network (ANN). Customer churn prediction is crucial for businesses to understand and mitigate customer attrition. In this project, we leverage deep learning techniques to predict whether a customer is likely to churn based on historical data.

Table of Contents
Introduction
Dataset
Installation
Usage
Results
Contributing
License
Introduction
Customer churn refers to the phenomenon where customers stop doing business with a company. Predicting customer churn helps businesses take proactive measures to retain customers. In this project, we build and train an Artificial Neural Network to predict customer churn using features like contract duration, monthly charges, and more.

Dataset
The dataset used for this project is the Telco Customer Churn dataset, which contains various features of customers along with their churn status. You can find the dataset here. Make sure to download and place it in the data directory before running the code.

git clone https://github.com/ganeshkadam914/telco-churn-prediction.git
cd telco-churn-prediction
Create a virtual environment (optional but recommended)

python3 -m venv venv
source venv/bin/activate
Install the required packages:

pip install -r requirements.txt
Usage
Navigate to the project directory:

cd telco-churn-prediction
Prepare the dataset: Download the Telco Customer Churn dataset and place it in the data directory.

Train the ANN model:

sh
Copy code
python train_model.py
Make predictions:

sh
Copy code
python predict.py
Results
Our trained ANN achieved an accuracy of X% on the test dataset. The model successfully predicts customer churn with high precision, which can help businesses in devising effective retention strategies.

Contributing
Contributions are welcome! If you find any issues or want to add enhancements to the project, feel free to open a pull request.
