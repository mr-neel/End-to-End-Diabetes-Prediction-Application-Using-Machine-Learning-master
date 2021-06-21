## End-to-End Diabetes Prediction Application using Machine Learning (MINI Project)  


### Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Demo](#demo)
  * [Learning Objective](#Learning-Objective)
  * [Technical Aspect](#technical-aspect)
  * [Technologies Used](#technologies-used)
  * [To Do](#to-do)
  * [Installation](#installation)
  * [Run](#run)
  * [Bug / Feature Request](#bug---feature-request)
  
  

### Overview 
In this project, the objective is to predict whether the person has Diabetes or not based on various features suach as 
- Pregnancies
- Insulin Level
- Age
- BMI.
The data set that has used in this project has taken from the [kaggle](https://www.kaggle.com/) . "This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage." and used a simple [random forest classifier](https://en.wikipedia.org/wiki/Random_forest).   


### Motivation
The motivation was to experiment  with end to end machine learning project and get some idea about deployment platform like [Heroku] and offcourse this "
Diabetes is an increasingly growing health issue due to our inactive lifestyle. If it is detected in time then through proper medical treatment, adverse effects can be prevented. To help in early detection, technology can be used very reliably and efficiently. Using machine learning we have built a predictive model that can predict whether the patient is diabetes positive or not.".
This is also sort of fun to work on a project like this which could be beneficial for the society. 

### Demo
[Visit this link for live demo]:pending

### Learning Objective
The following points were the objective of the project .
- Data gathering 
- Descriptive Analysis 
- Data Visualizations 
- Data Preprocessing 
- Data Modelling 
- Model Evaluation 
- Model Deployment 

### Technical Aspect 

- Training a machine learning model using scikit-learn. 
- Building and hosting a Flask web app on Heroku. 
- A user has to put details like Number of Pregnancies, Insulin Level, Age, BMI etc . 
  



<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>
![numpy](https://user-images.githubusercontent.com/71751175/122774216-a0ea4f80-d2c6-11eb-92e6-0c2527638677.png)
### Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/mr-neel/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/issues) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/mr-neel/End-to-End-Diabetes-Prediction-Application-Using-Machine-Learning/issues/new). Please include sample queries and their corresponding results.


### Installation 
- Clone this repository and unzip it.
- After downloading, cd into the flask directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt
- Execute the command: python app.py


![interface](https://user-images.githubusercontent.com/71751175/122774175-9a5bd800-d2c6-11eb-83ff-db279a50cdf3.jpg)







### Note:
- Webapp can handle concurrency upto some extent but can be scaled.

