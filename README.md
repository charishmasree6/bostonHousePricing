Boston House Price Prediction
This project implements a Machine Learning model to predict house prices in the Boston area and deploys it as a Flask web application. The goal is to provide a simple interface where a user can input various socio-economic and environmental factors to get an estimated house price.

The core components are:

HousePricePrediction.ipynb: Data cleaning, EDA, model training, and evaluation.

regmodel.pkl: The saved, trained machine learning model.

scaling.pkl: The saved feature scaling object (e.g., StandardScaler), crucial for preprocessing new user input before prediction.

app.py: The Flask application logic that loads the model and handles web requests.

templates/home.html: The HTML frontend for user interaction.

⚙️ Setup and Installation
Prerequisites
Python 3.x

Git

Installation Steps
Clone the repository:

Bash

git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName
Create a virtual environment (Recommended):

Bash

python -m venv venv
source venv/bin/activate  # macOS/Linux
# venv\Scripts\activate   # Windows
Install the required dependencies: All necessary Python libraries are listed in requirements.txt.

Bash

pip install -r requirements.txt
🚀 How to Run the Web Application
The application uses Flask and runs on a local server.

Ensure your virtual environment is active.

Run the main application file:

Bash
python app.py
Access the application: Open your web browser and navigate to the address displayed in the terminal (typically http://127.0.0.1:5000)

python app.py
Access the application: Open your web browser and navigate to the address displayed in the terminal (typically http://127.0.0.1:5000).
