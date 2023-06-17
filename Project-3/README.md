# Project-3
Diabetes Visualization and Prediction Model

## What is Diabetes ?
* Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. 
* Insulin is a hormone that regulates blood glucose. Hyperglycaemia, also called raised blood glucose or raised blood sugar, is a common effect of uncontrolled diabetes and over time leads to serious damage to many of the body's systems, especially the nerves and blood vessels.

## AIM OF PROJECT
* To predict whether a patient has diabetes based on his features such as age, gender, bmi, hypertension, smoking history, hba1c level and blood glucose level.
* To infer the general diabetes positive rate in a sample size.

## DATA DESCRIPTION
#### Context
* The diabetes_prediction_dataset.csv file contains medical and demographic data of patients along with their diabetes status, whether positive or negative. 
* It consists of various features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level.  
* It contains 100K rows and 9 feature columns

Click for [Dataset Source](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)

#### DATASET COLUMNS

* gender <br>
Gender refers to the biological sex of the individual, which can have an impact on their susceptibility to diabetes. There are three categories in it male ,female and other.

* age<br>
Age is an important factor as diabetes is more commonly diagnosed in older adults.Age ranges from 0-80 in our dataset.

* hypertension<br>
Hypertension is a medical condition in which the blood pressure in the arteries is persistently elevated. It has values a 0 or 1 where 0 indicates they don’t have hypertension and for 1 it means they have hypertension.

* heart_disease<br>
Heart disease is another medical condition that is associated with an increased risk of developing diabetes. It has values a 0 or 1 where 0 indicates they don’t have heart disease and for 1 it means they have heart disease.

* smoking_history<br>
Smoking history is also considered a risk factor for diabetes and can exacerbate the complications associated with diabetes.In our dataset we have 5 categories i.e not current,former,No Info,current,never and ever.

* bmi<br>
BMI (Body Mass Index) is a measure of body fat based on weight and height. Higher BMI values are linked to a higher risk of diabetes. The range of BMI in the dataset is from 10.16 to 71.55. BMI less than 18.5 is underweight, 18.5-24.9 is normal, 25-29.9 is overweight, and 30 or more is obese.

* HbA1c_level<br>
HbA1c (Hemoglobin A1c) level is a measure of a person's average blood sugar level over the past 2-3 months. Higher levels indicate a greater risk of developing diabetes. Mostly more than 6.5% of HbA1c Level indicates diabetes.

* blood_glucose_level<br>
Blood glucose level refers to the amount of glucose in the bloodstream at a given time. High blood glucose levels are a key indicator of diabetes.

* diabetes<br>
Diabetes is the target variable being predicted, with values of 1 indicating the presence of diabetes and 0 indicating the

## This project shows:

* ability to write structured Python codes.
* bility to use existing libraries to process and analyze data.
* ability to use data pre-processing skills.
* ability to use exploratory analysis skills.
* ability to manupulate data.
* ability to build a ML model for diabetes prediction using various techniques and finding the best among them w.r.t accuracy
* ability to analyse a dataset and frame questions on why, when and how

#### LIBRARIES USED
* Pandas
* Numpy
* Matplotlib
* Sklearn
* Seaborn
* Imblearn
