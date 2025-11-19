# Heart Disease Prediction Model

This repository contains a machine learning model trained to predict heart disease rates under differing circumstances using logistic regression. The model is integrated into an interactive web application built with Streamlit, allowing users to input health parameters and receive a prediction on the likelihood of heart disease.

## Features

- Logistic Regression model trained on heart disease dataset
- Interactive Streamlit frontend for user input and prediction
- Easy to run locally with minimal setup

## Getting Started

### Prerequisites

Make sure you have Python 3 installed on your device. It is recommended to use a Python virtual environment.

### Installation

1. Clone this repository:

   ```
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. (Optional) Create and activate a virtual environment:

   On Linux/macOS:
   ```
   python3 -m venv env
   source env/bin/activate
   ```

   On Windows:
   ```
   python -m venv env
   .\env\Scripts\activate
   ```

### Running the Streamlit Frontend

To launch the frontend application on your device:

```
streamlit run app.py
```

This command will open the web application in your default browser, where you can enter health details such as age, sex, blood pressure, cholesterol, and more, then click the "Predict" button to see the model's prediction.

## Model Details

- Algorithm: Logistic Regression
- Dataset: Heart disease-related health features (e.g., age, blood pressure, cholesterol, etc.)
- Evaluation metric: F1 and Recall scores

## License

This project is licensed under the MIT License.
