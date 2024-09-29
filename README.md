# Algerian Forest Fires Analysis and Prediction

This project analyzes the Algerian Forest Fires dataset and builds predictive models using various regression techniques. It follows a complete machine learning project lifecycle from data collection to deployment on AWS Elastic Beanstalk.

## Project Structure

- `dataset/`
  - `Algerian_forest_fires_dataset_UPDATE.csv`: Original dataset
  - `Algerian_forest_fires_cleaned_dataset.csv`: Cleaned dataset
- `models/`
  - `scaler.pkl`: For standardization and feature scaling
  - `ridge.pkl`: Trained Ridge Regression model
- `.ebextensions/`: AWS Elastic Beanstalk configuration
- `notebooks/`
  - `EDA And FE Algerian Forest Fires.ipynb`: Exploratory Data Analysis and Feature Engineering
  - `Model Training.ipynb`: Model selection, training, and evaluation
- `templates/`: HTML file for frontend
- `requirements.txt`: Required Python libraries
- `application.py`: Main Flask application

## Project Lifecycle

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Feature Selection
5. Model Training
6. Flask Application Integration
7. GitHub Repository
8. AWS Deployment
9. CI/CD Pipeline Setup

## Setup and Installation

1. Clone the repository
2. Install required libraries: `pip install -r requirements.txt`
3. Run the Flask application locally: `python application.py`

## AWS Deployment

The application is deployed on AWS Elastic Beanstalk. The `.ebextensions` folder contains necessary configurations.
