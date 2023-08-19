# Salary Prediction Flask API
 This Flask API provides a simple web interface for predicting salaries based on years of experience using a trained linear regression model. 
 ## Installation  
 1. Clone the repository:
 ```bash
	git clone https://github.com/Menna-elgallad/salary-prediction-api.git cd salary-prediction-api
```
2. Install the required dependencies using `pip`
 ```bash
	pip install -r requirement.txt
 ```
 3.  Training the Model
 ```bash
	python model.py
```
3. Running the Flask Server
 ```bash
	flask run
	##or
	python app.py
```

## API Endpoints

-   `/`: Home page with a form to input years of experience and get a predicted salary.
-   `/predict`: Predict page with the predicted data.

## Directory Structure

-   `app.py`: The main Flask application file.
-   `model.py`: Script to train the linear regression model.
-   `model.pkl`: Trained model saved as a serialized object.
-   `requirements.txt`: List of required Python packages.
-   `templates/`: Folder containing HTML templates for the web interface.
-  `static/` Folder containing static files used in website eg. css files