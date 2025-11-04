# Student Performance Prediction using Machine Learning
## Project Overview

This project applies machine learning techniques to predict student academic performance based on behavioral and study-related factors.
Using the Student Performance Dataset (Synthetic, Realistic), the project explores how self-study time, attendance, and class participation influence students’ total scores and final grades.

The goal is to support data-driven decision-making for educators by identifying students at risk of poor performance early enough for effective intervention.

## Objectives

**1.** Predict students’ final numeric scores using regression.

**2.** Classify students into letter grade categories (A–F) using classification models.

**3.** Identify the most important features influencing student performance.

**4.** Provide practical insights to help improve learning outcomes.

## Dataset Information

**Dataset:** Student Performance Dataset (Synthetic, Realistic)
**Source:** Kaggle
**Rows:** 1,000,000

## Feature	Description
**student_id**	Unique identifier for each student
**weekly_self_study_hours**	Average weekly self-study hours (0–40)
**attendance_percentage**	Attendance percentage (50–100)
**class_participation**	Class participation score (0–10)
**total_score**	Final performance score (0–100)
**grade**	Letter grade (A, B, C, D, F) derived from total_score

## Machine Learning Models
Model -- Type -- Purpose -- Key Metrics
Linear Regression	Regression	Predicts continuous total scores	MAE = 7.16, RMSE = 9.00, R² = 0.66
Random Forest Classifier	Classification	Predicts categorical letter grades	Accuracy = 64.5%, Balanced precision and recall

## Key Insights

**1.** Weekly self-study hours are the strongest predictor of student success.

**2.** Attendance percentage shows a clear positive correlation with performance.

**3.** Class participation contributes moderately to overall results.

**4.** The Linear Regression model explains 66% of score variation, while the Random Forest Classifier achieves 64.5% accuracy.

**5.** Both models confirm that consistent study habits and classroom engagement lead to better academic outcomes.

## Recommendations

Encourage consistent and structured self-study routines.

Monitor and improve attendance rates through active tracking and early intervention.

Increase student participation through discussions, projects, and collaborative learning.

Use predictive models to identify at-risk students early in the term for targeted support.

## Next Steps

Train advanced models such as XGBoost or Gradient Boosting to improve predictive accuracy.

Add more features, such as prior academic records and parental involvement, for better performance.

Deploy the model in a web dashboard (Streamlit or Flask) to enable real-time predictions.

Continuously update and retrain the model with new data to maintain accuracy.
