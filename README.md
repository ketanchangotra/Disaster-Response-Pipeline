# Disaster Response Pipeline Project

Objective: Classify Disaster Response Text data using ML techniques.

### Project Outline:
1. Data
disaster_categories.csv and disaster_messages.csv (datasets)
DisasterResponse.db: Database from transformed and cleaned data.
process_data.py: Code for Data cleaning and storage in a SQL database. 
2. Models
train_classifier.py: Code to load & trasform data using NLP and ML model to train using GridSearchCV .
3. App
run.py: Flask app and the user interface used to predict results and display them.
templates: folder containing the html templates

### Code Use:
python process_data.py disaster_messages.csv disaster_categories.csv DisasterResponse.db
python train_classifier.py ../data/DisasterResponse.db classifier.pkl
python run.py

### Screenshots

App Front Page:
![Front Page](https://github.com/ketanchangotra/Disaster-Response-Pipeline/blob/master/app/snapshot1.PNG)

![Overview of Training Data](https://github.com/ketanchangotra/Disaster-Response-Pipeline/blob/master/app/snapshot2.PNG)

Result Output:

![Output](https://github.com/ketanchangotra/Disaster-Response-Pipeline/blob/master/app/snapshot2.PNG)


This project is prepared as part of the Udacity Data Scientist Nanodegree programme



