# Recommendation-system

# Anime Recommendation System

## Objective
The objective of this project is to implement a recommendation system using cosine similarity on an anime dataset.

## Dataset
The dataset contains information about various anime, including their titles, genres, number of episodes, user ratings, and more.

## Tasks

1. **Data Preprocessing**
   - Handle missing values.
   - Encode categorical features as numerical values.
   - Normalize numerical features.

2. **Feature Extraction**
   - Select relevant features for similarity calculation.

3. **Recommendation System**
   - Compute cosine similarity between anime features.
   - Recommend similar anime based on a target anime ID.

4. **Evaluation**
   - Split the dataset into training and testing sets.
   - Evaluate the system using metrics like precision, recall, and F1-score.

## How to Run
1. Place the `anime.csv` file in the same directory as this script.
2. Run the script using Python.
3. Update the `target_anime` variable with the desired anime ID to get recommendations.

## Requirements
- pandas
- numpy
- scikit-learn

## Future Improvements
- Incorporate user-based collaborative filtering.
- Add support for hybrid recommendation systems.
- Enhance the evaluation process with additional metrics.

"""
