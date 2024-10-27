# Workout Recommendation System

## Overview

This project implements a workout recommendation system using a dataset of various exercises. The system leverages machine learning techniques, specifically the k-Nearest Neighbors (k-NN) algorithm, to recommend workouts based on user preferences and exercise characteristics.

## Features

- **Data Cleaning**: Removes irrelevant columns and handles missing values.
- **Visualization**: Displays a bar chart of exercise counts by body part.
- **One-Hot Encoding**: Transforms categorical features into a format suitable for machine learning.
- **Recommendation System**: Suggests workouts based on user-defined inputs.
- **Recommendation Evaluation**: Utilizes fuzzy matching to evaluate the quality of recommendations.

## Requirements

Ensure you have the following libraries installed:

- `pandas`
- `plotly`
- `scikit-learn`
- `fuzzywuzzy`

You can install these libraries using pip:

```bash
pip install pandas plotly scikit-learn fuzzywuzzy
