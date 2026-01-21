Overview

This repository contains a case study on predictive modeling and clustering for football player performance. Using a mock dataset, the goal is to explore how player statistics relate to goal scoring and to experiment with regression and clustering models in Python.

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

Regression Pipeline: Built a pipeline combining:

StandardScaler for feature scaling

Ridge Regression for linear prediction

Clustering: Applied KMeans clustering to group players based on their statistics and identify performance patterns.

Training & Prediction: Model trained on training data and predictions generated on test data.

Evaluation: Performance evaluated using:

Mean Squared Error (MSE)

R² score

Cluster analysis visualization

Results

Regression Coefficients: Show the effect of each feature on goal scoring.

Model Performance: Predictive power is limited (expected due to mock data).

Clustering Insights: KMeans helped identify groups of players with similar performance patterns.

Overall Insights: The exercise demonstrates how features influence goal scoring, how regression pipelines work, and how clustering can reveal underlying patterns in player statistics.
