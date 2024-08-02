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

### 1. Clone the Repository:
```bash
git clone https://github.com/yourusername/credit-card-default-prediction.git && cd credit-card-default-prediction
```
### 2. Install Required Packages:
```bash
pip install -r requirements.txt
```
## Usage

1. Ensure the trained model (`clf2.pkl`) and scaler (`train_scaler.pkl`) are located in the `models/` directory.
2. Start the Flask application:
    ```bash
    python main.py
    ```
3. Open your web browser and navigate to `http://localhost:5000`.
4. Complete the form with the necessary information and submit it to receive the prediction.

