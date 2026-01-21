Overview

This repository contains a case study on predictive modeling for football player performance. Using a mock dataset, the goal is to explore how player statistics relate to goal scoring and to experiment with regression models in Python.

⚠️ Note: The dataset is simulated for educational purposes. Results are for exploration only and do not reflect real-world football statistics.

Dataset

The dataset includes the following player statistics:

MinutesPlayed – Total minutes played by the player

ShotsOnTarget – Number of shots on target

Assists – Number of assists made

Goals – Target variable: number of goals scored

All data is artificially generated to demonstrate the modeling process.

Modeling Approach

The workflow includes:

Feature Selection: Selected relevant features (MinutesPlayed, ShotsOnTarget, Assists) to predict goals.

Train/Test Split: Split data into training (80%) and testing (20%) sets.

Pipeline: Built a pipeline combining:

StandardScaler for feature scaling

Ridge Regression for linear prediction

Training & Prediction: Model trained on training data and used to generate predictions on test data.

Evaluation: Model performance measured using:

Mean Squared Error (MSE)

R² score

Results

Coefficients: Show the effect of each feature on goal scoring.

Model Performance: Predictive power is limited (expected due to mock data).

Insights: Despite low accuracy, the exercise demonstrates the impact of features on the target variable and how a regression pipeline works.
