# Workout Data Analysis

This project analyzes a two-month dataset of workout activity logs. The goal is to uncover trends in calorie expenditure, time efficiency, and heart rate intensity across different workout types.

## Objectives

- Identify which workout types burn the most total calories
- Calculate and compare workout efficiency using a custom `CaloriesPerMinute` metric
- Analyze pulse and max pulse averages to assess intensity by workout type

## Files

- `workout_analysis.ipynb` – Full analysis notebook with data cleaning, transformation, and visualizations
- `cleaned_workout_data.csv` – Processed dataset including the engineered `CaloriesPerMinute` column

## Key Findings

- HIIT workouts burned the most calories per minute, indicating high intensity in short sessions
- Strength workouts were the most time-efficient overall
- Yoga sessions showed the lowest pulse rates and calorie output, aligning with lower-intensity expectations

## Tools Used

- Python (Pandas, NumPy)
- Seaborn and Matplotlib for data visualization
- Jupyter/Colab for exploratory analysis
