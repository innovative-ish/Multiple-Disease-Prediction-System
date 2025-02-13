**Multiple Disease Prediction System**
**Overview**
This project implements a machine learning-based system for predicting multiple diseases, including Heart Disease, Diabetes, and Parkinson's Disease. It was developed as a final year project for a Bachelor of Technology degree in Computer Science & Engineering at Sushila Devi Bansal College of Technology, Indore.

**Features**
	Predicts likelihood of Heart Disease, Diabetes, and Parkinson's Disease
	Uses machine learning algorithms including Logistic Regression and Support Vector Machines (SVM)
	Provides a user-friendly interface for inputting patient parameters
	Displays prediction results for multiple diseases in one platform

**Technologies Used**
	Python 3.7
	Streamlit for web application
	Machine Learning libraries (scikit-learn, etc.)
	Data visualization tools (matplotlib, seaborn, etc.)

**Installation**
	1. Clone this repository
	2. Install required dependencies:
		text
		pip install -r requirements.txt
	3. Run the Streamlit app:
		text
		streamlit run app.py

**Usage**
	1. Select the disease you want to predict
	2. Enter the required patient parameters
	3. Click "Predict" to see the results

**Dataset Information**
	The project uses separate datasets for each disease:
	1. Heart Disease Dataset
	2. Diabetes Dataset
	3. Parkinson's Disease Dataset

**Project Structure**
	app.py: Main Streamlit application
	models/: Trained machine learning models
	data/: Datasets used for training
	preprocessing/: Data preprocessing scripts
	visualization/: Data visualization scripts

**Future Scope**
	Addition of more diseases to the prediction system
	Improvement of model accuracy
	Integration with electronic health records
