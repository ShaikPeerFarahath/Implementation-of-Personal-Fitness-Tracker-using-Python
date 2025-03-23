# Implementation-of-Personal-Fitness-Tracker-using-Python

Overview

The Personal Fitness Tracker is a web-based application built using Streamlit and Machine Learning to predict calories burned based on user input parameters such as age, BMI, duration of exercise, heart rate, body temperature, and gender.

Features

User-friendly web application using Streamlit.

Takes input parameters: Age, BMI, Exercise Duration, Heart Rate, Body Temperature, Gender.

Uses Random Forest Regressor to predict the calories burned.

Data visualization to compare user statistics with others.

Uses calories.csv and exercise.csv datasets for training.

Technologies Used

Python (for backend logic)

Streamlit (for frontend UI)

Scikit-learn (for machine learning models)

Pandas & NumPy (for data manipulation)

Matplotlib & Seaborn (for visualization)

Installation

Prerequisites

Ensure you have Python installed on your system. Then, install the required dependencies:

'pip install streamlit pandas numpy scikit-learn matplotlib seaborn'

How to Run the Application

1. Clone the repository:

'git clone https://github.com/ShaikPeerFarahath/Implementation-of-Personal-Fitness-Tracker-using-python.git
cdImplementation-of-Personal-Fitness-Tracker-using-python'

2. Run the application:
  'streamlit run apps.py'

Dataset Description

calories.csv: Contains user IDs and corresponding calories burned.

exercise.csv: Contains user data including gender, age, height, weight, duration, heart rate, and body temperature.


Project Structure

Personal-Fitness-Tracker/
│-- apps.py             # Main application file
│-- calorie.csv         # Dataset with calorie data
│-- Exercise.csv        # Dataset with user exercise details
│-- README.md           # Project documentation

Future Enhancements

Implement a database for long-term user progress tracking.

Deploy the application as a mobile app.

Integrate with Google Fit or Apple Health.




