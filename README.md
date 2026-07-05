# Fitness Calorie Expenditure Analysis

## Project Overview

This project was completed as part of my Data Analytics studies at Noroff.

The objective was to investigate which factors have the greatest impact on calorie expenditure during exercise using exploratory data analysis (EDA) and Power BI.

The project simulates a real-world business case where a fitness organisation wants to better understand member workout behaviour in order to improve training recommendations and customer outcomes.

---

## Business Problem

Fitness organisations collect large amounts of workout data but often struggle to identify which variables truly influence calorie expenditure.

The goal of this project was to answer questions such as:

- Does workout duration affect calories burned?
- Does heart rate explain calorie expenditure?
- Which workout types are most efficient?
- How do gender, body weight and experience level influence workout outcomes?

---

## Dataset

- **Source:** Kaggle
- **Observations:** 972 workout sessions
- **Data type:** Simulated (fictional) workout data
- **Format:** CSV

The dataset was created to simulate realistic fitness tracking data. No real personal information is included.

---

# Exploratory Data Analysis

## 1. Workout Duration vs Calories Burned

The strongest relationship observed in the dataset was between workout duration and total calorie expenditure.

Longer workout sessions consistently resulted in higher calorie burn.

![Workout Duration](images/Relationship_Between_Workout_Duration_and_Calorie_Expenditure.png)

---

## 2. Heart Rate vs Calories Burned

Average heart rate showed a positive relationship with calorie expenditure, although considerably weaker than workout duration.

![Heart Rate](images/figure2-heart-rate-vs-calories.png)

---

## 3. Calories Burned per Workout Type

To compare workout efficiency fairly, a new variable (**Calories_Per_Hour**) was created.

Strength training and cardio showed the highest calorie expenditure per hour.

![Workout Type](images/figure3-workout-type.png)

---

## 4. Gender Differences

Male participants demonstrated a higher average calorie expenditure per hour than female participants within this dataset.

![Gender](images/figure4-gender.png)

---

## Feature Engineering

To improve the analysis, a new variable called **Calories_Per_Hour** was created.

This standardized calorie expenditure across workouts of different lengths and enabled fair comparisons between workout types.

---

## Tools Used

- Power BI
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering

---

## Key Findings

- Workout duration was the strongest predictor of calorie expenditure.
- Heart rate had a positive but weaker relationship with calorie burn.
- Strength training showed the highest average calorie expenditure per hour.
- Experience level appeared strongly associated with total calorie expenditure.
- HIIT produced lower calorie expenditure per hour than expected.

---

## What I Learned

This project strengthened my skills in:

- Exploratory Data Analysis
- Data storytelling
- Power BI
- Feature engineering
- Business-oriented analysis
- Communicating insights from data

---

## Full Report

The complete report can be found here:

📄 **Report/Exam Project Noroff Trond Einar Myrvold.pdf**

---

## Disclaimer

This project was completed as part of my studies at Noroff.

The dataset consists entirely of simulated fitness data and contains no real personal information.
