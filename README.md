# Movie Recommendation System

A **movie recommendation system** built on a dataset of 5,000 movies, designed to suggest films based on content analysis and cast & crew metadata. This project demonstrates data merging, preprocessing, feature engineering, and machine learning-powered recommendations using Python

## Dataset Overview

The project uses two primary datasets:
- **Movies Dataset:** Contains details about each movie such as title, overview, genres, etc.
- **Movie Credits Dataset:** Provides information about the cast and crew for every film.

## Data Processing Workflow

1. **Dataset Understanding & Column Selection**
   - Loaded both datasets and analyzed available columns.
   - Selected only the relevant columns needed for recommendations.
   - Merged both tables into a single dataset containing just the useful features.

2. **Data Preprocessing**
   - **Handled null values** by dropping or imputing as appropriate.
   - **Removed repeated (duplicate) values** to ensure data quality.

3. **Feature Engineering**
   - Used user-defined functions to clean and format columns.
   - Joined multiple feature columns (e.g., genres, cast, keywords) to create a unified **corpus** for each movie.

4. **Vectorization**
   - Applied vectorization techniques to the textual corpus to transform data into numerical features usable for similarity calculation and recommendations.
