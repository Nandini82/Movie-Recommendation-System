# Movie Recommendation System

This repository contains the code for a Movie Recommendation System. The system recommends movies to users based on their past viewing history and ratings. The system uses a Machine Learning technique called cosine similarity to generate recommendations.

## Data

The dataset contains information about movies, including their budget, genre, ID, language, title, and more. It also includes user ratings for movies.

## Model

The recommendation system uses a Machine Learning model based on cosine similarity. Cosine similarity is a measure of the similarity between two non-zero vectors of an inner product space that measures the cosine of the angle between them. In this case, the vectors represent the movies and the ratings for each user. The model then generates recommendations based on the similarity between the user's ratings and the ratings of other users.

## Usage

To use the recommendation system, follow these steps:

1. Install the required packages.

3. Open the `Movie_Recommendation.ipynb` file.

5. Run the file. This will generate recommendations for each user in the dataset. It generates pkl file for further deployment.

5. The pkl file is deployed using Streamlit framework.

## Output

The output of the recommendation system is a list of recommended movies for each user in the dataset.

## Conclusion

This Movie Recommendation System demonstrates how Machine Learning techniques can be used to generate recommendations based on user data. By using cosine similarity, the system is able to generate accurate and personalized recommendations for each user. With further development and optimization, this recommendation system could be used in a variety of applications, such as streaming services or movie review websites.

