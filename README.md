Boston House Price Prediction – ML Web App

A Machine Learning powered web application that predicts house prices using a trained regression model. The app is built using Flask, Scikit-Learn, and deployed on Render Cloud.

🌐 Live Demo:
https://bostonhousepricing-gcpp.onrender.com/

🚀 Features

📊 Predict house prices based on input features

🧠 Machine Learning model trained using Linear Regression

🔄 Data scaling using StandardScaler

🌐 REST API endpoint for predictions

🖥 Web interface using HTML templates

☁️ Deployed on cloud using Gunicorn + Render

🛠 Tech Stack

Python

Flask

Scikit-Learn

NumPy

Pandas

Gunicorn

Render (Cloud Deployment)

📂 Project Structure
bostonHousePricing/
│
├── templates/
│   └── home.html
│
├── app.py
├── regmodel.pkl
├── scaling.pkl
├── requirements.txt
└── README.md

⚙️ Installation (Run Locally)
1️⃣ Clone the Repository
git clone https://github.com/charishmasree6/bostonHousePricing.git
cd bostonHousePricing

2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
python app.py


Open in browser:

http://127.0.0.1:5000/

🔌 API Endpoint
POST /predict_api

Input (JSON):

{
  "data": {
    "feature1": value,
    "feature2": value
  }
}


Output:

predicted_price

☁️ Deployment Details

The application is deployed using:

Gunicorn as WSGI server

Render Web Service (Python 3 runtime)

Automatic deployment from GitHub

🧠 Model Details

Algorithm: Linear Regression

Feature Scaling: StandardScaler

Serialized using: Pickle

🎯 Learning Outcomes

Built end-to-end ML pipeline

Converted ML model into REST API

Understood production deployment

Debugged build & runtime errors

Deployed ML app on cloud
python app.py
Access the application: Open your web browser and navigate to the address displayed in the terminal (typically http://127.0.0.1:5000).
