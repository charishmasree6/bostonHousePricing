1. Activate the Environment
In your VS Code terminal (or whichever terminal you are using), ensure you activate the environment you created earlier:

Bash

conda activate .\venv
Your prompt should change to look like this: (venv) C:\Users\chari\...\bostonHousePricing>

2. Install Flask and Other Dependencies
Once the environment is active, you need to install Flask, scikit-learn (for the model/scalar), NumPy, and Pandas.

If you have a requirements.txt file in your project, run:

Bash

pip install -r requirements.txt
If you do not have a requirements.txt file, you must manually install the packages mentioned in your script:

Bash

pip install flask numpy pandas scikit-learn
(Note: Scikit-learn is required because pickle.load is used to load a scaler and model, which are typically scikit-learn objects.)

3. Run the App
After installation finishes, run your script again:

Bash

python app.py
This time, Python will look for and find the installed Flask module inside the active (venv) environment, and your web server should start.