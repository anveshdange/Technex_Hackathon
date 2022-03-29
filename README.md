# Problem Statement:
The Minister of Health has further informed the upper house of the Parliament that the doctor-patient ratio in India is 1:834, which means that there is a doctor serving for 834 patients in India. Looking at those numbers, not every patient is treated fairly. 
So our aim was to build a tool for doctors which could predict diseases in Humans as accurately as a phd doctor.

# Technex Hackthon 2022 

We are Team Alter Dime and this is our Project which caters to predicting Disease by the use of Artificial Neural Networks.

=> Alter Dime Team Members :
1. Anvesh Dange
2. Utkarsh Sinha
3. Anvesh Khambatkar
4. Aditya Maurya

Personal machine learning project on building a Diabetes disease prediction model with implementation of a web application.

web app: https://share.streamlit.io/group4day2019/ml_internship2021/main/merged.py

This Web App is a combination of 2 individual python scripts which is trained and equipped with Artificial Intelligence and Machine learning ,specifically using Support Vector Machines (SVMs) and an AI  model exported module "Pickle".

Below is the description for both the Scripts.

#  Early Stage Diabetes Prediction.

About Data

This dataset contains the sign and symptpom data of newly diabetic or would be diabetic patient.This has been collected using direct questionnaires from the patients of Sylhet Diabetes Hospital in Sylhet, Bangladesh and approved by a doctor.

Features of the dataset: Diabetes_data_upload.csv

The dataset consist of total 15 features and one target variable named class.

1. Age: Age in years ranging from (20years to 65 years)
2. Gender: Male / Female
3. Polyuria: Yes / No
4. Polydipsia: Yes/ No
5. Sudden weight loss: Yes/ No
6. Weakness: Yes/ No
7. Polyphagia: Yes/ No
8. Genital Thrush: Yes/ No
9. Visual blurring: Yes/ No
10. Itching: Yes/ No
11. Irritability: Yes/No
12. Delayed healing: Yes/ No
13. Partial Paresis: Yes/ No
14. Muscle stiffness: yes/ No
15. Alopecia: Yes/ No
16. Obesity: Yes/ No

Class: Positive / Negative

# Pima Indians dataset.

Diabetes.csv
Our SVM AI Model is trained by using the below Dataset.

Source: https://www.kaggle.com/uciml/pima-indians-diabetes-database.


Data description: The Pima Indians Diabetes Dataset consists of several medical parameters and
one dependent parameter (outcome) of binary values. The data-set is mainly for Female gender of at
least 21 years old of Pima Indian heritage and the description of the data-set is as follows;
* 9 columns with 8 independent parameters, 1 outcome parameter with uniquely identified 768
observations having 268 positive for diabetes (1) and 500 negative for diabetes (0).
The 9 columns are the following.
Pregnancies: Number of times pregnant.
Glucose: Oral glucose tolerant test result.
Blood pressure: Diastolic blood pressure values in mmHg
skin thickness: triceps skin fold thickness in mmInsulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index.
DiabetesPedigreeFunction : Diabetes Pedigree function.
Age: Age in years.
Outcome: Class 1 indicates person with diabetes, 0 indicates other.

# How to run the App.

step1: Clone this Github Repository by using the command "git clone repo_name" .
step2: Navigate in this Repository in your local machine
step3: run the command "python3 -m pip install -r requirements.txt" 
// This will install all the requirements for your app to run.
step4: Run the command "streamlit run main.py" in the command line interface of your local machine.








