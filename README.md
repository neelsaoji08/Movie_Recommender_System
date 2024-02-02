# Movie Recommender System

Welcome to the Movie Recommender System! This system uses collaborative filtering to recommend movies based on user preferences. Follow the instructions below to run the system and get personalized movie recommendations.

## Getting Started

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/movie-recommender-system.git
    cd movie-recommender-system
    ```

## Running the Movie Recommender System

1. Open and run the `movie_recommender_system.ipynb` notebook. This notebook trains the collaborative filtering model and saves it in a pickle file.

2. The trained model is saved in the following pickle files:
   - `user_movie_ratings.pkl`: User-movie ratings matrix
   - `movie_similarity.pkl`: Movie similarity matrix

## Finding Recommended Movies

1. After running the notebook, you can find recommended movies by running the `app.py` file.

    ```bash
    streanlit run app.py
    ```

2. Visit the url provided by the terminal in your web browser.

3. Enter A movie and click on the "Get Recommendations" button.

4. The system will provide a list
