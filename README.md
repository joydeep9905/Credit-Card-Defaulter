# Credit Card Default Prediction

## Project Overview
This project entails a web application that estimates the probability of a credit card default by analyzing various financial and personal factors. It employs a machine learning model to make these predictions and displays the results through an easy-to-use web interface.

## Features
- **User-friendly Web Interface**: Enables users to enter customer data seamlessly.
- **Instant Predictions**: Uses a pre-trained machine learning model to provide real-time results.
- **Secure Data Handling**: Manages sensitive financial information securely.
- **Responsive Layout**: Compatible with multiple devices for versatile use.

## Technology Stack
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS
- **Machine Learning**: scikit-learn
- **Data Preprocessing**: StandardScaler

## Installation

### 1.Clone the Repository:
```bash
git clone https://github.com/yourusername/credit-card-default-prediction.git
cd credit-card-default-prediction

### 2.Install Required Packages:
```bash
pip install -r requirements.txt

### 3.Usage:
```bash
Ensure the trained model (clf2.pkl) and scaler (train_scaler.pkl) are located in the models/ directory.
Start the Flask application:
python main.py
Open your web browser and navigate to http://localhost:5000.
Complete the form with the necessary information and submit it to receive the prediction.

### 3.Model Information:
```bash
This project utilizes a [type of model, e.g., Random Forest Classifier] trained on historical credit card data. The model evaluates factors such as credit limit, payment history, bill amounts, and personal information to predict the likelihood of a default.

Replace `[type of model, e.g., Random Forest Classifier]` with the actual model type you used. Save this content in a file named `README.md` in your project directory.


