Overview

This repository contains a case study exploring predictive modeling for football player performance. Using mock data, the goal was to understand how certain player statistics relate to goal scoring and to experiment with regression models in Python.

⚠️ Note: This is a mock dataset created for educational purposes. The results are for exploration only and do not reflect real-world football statistics.

Dataset

The dataset includes player statistics such as:

MinutesPlayed – Total minutes played by the player

ShotsOnTarget – Number of shots on target

Assists – Number of assists made

Goals – Target variable: number of goals scored

The data is entirely simulated to demonstrate the modeling process.

Modeling Approach

The workflow includes:

Feature Selection: Selected a subset of relevant features (MinutesPlayed, ShotsOnTarget, Assists) for predicting goals.

Train/Test Split: Split data into training (80%) and testing (20%) sets.

Pipeline: Built a pipeline combining:

StandardScaler for feature scaling

Ridge Regression for linear prediction

Training & Prediction: Model trained on training data and predictions generated on test data.

Evaluation: Performance evaluated using:

Mean Squared Error (MSE)

R² score

Results

Coefficients: Indicate the effect of each feature on goal scoring.

Model Performance: Limited predictive power (expected due to mock data).

Insights: Even with low accuracy, the exercise helped understand how features influence the target and how a regression pipeline works.
