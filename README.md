# LetterboxdMovieRec


- Imported data set from Kaggle and generated movie titles that are similar.
- Created a ratio that returned not extremeley popular but highly rated movies to find "undiscovered gems" and expand to niche sub genres.
**LetterboxdMovieRec - Movie Recommendation System**

The LetterboxdMovieRec is a movie recommendation system that utilizes data from Kaggle to generate movie recommendations based on similarity. The system aims to provide users with movie suggestions that are not extremely popular but highly rated, uncovering hidden gems, and exploring niche sub-genres.

**Key Features:**

- **Data Import:** The system imports movie data from Kaggle, which includes a vast collection of movie titles, ratings, and other relevant information.

- **Similarity Calculation:** By employing advanced similarity calculation algorithms, the system identifies movies that share similar attributes such as genre, director, actors, and user ratings.

- **Undiscovered Gems:** A specialized ratio is used to filter out extremely popular movies and instead focus on highly rated movies that might not have received as much mainstream attention, leading to the discovery of hidden gems.

- **Niche Sub-Genres:** The recommendation system goes beyond mainstream genres to explore niche sub-genres, catering to users with diverse and specific movie preferences.

**How It Works:**

1. **Data Preprocessing:** The imported data is preprocessed to remove any inconsistencies, missing values, or irrelevant information.

2. **Similarity Calculation:** The system employs sophisticated algorithms to calculate the similarity between movies based on various attributes, creating a matrix of movie similarities.

3. **Undiscovered Gems Ratio:** A special ratio is applied to rank the movies based on both ratings and popularity. This ratio ensures that movies with high ratings but not overwhelming popularity are prioritized in the recommendations.

4. **Niche Sub-Genres Exploration:** The recommendation system allows users to explore niche sub-genres that might align with their unique movie tastes, uncovering lesser-known movies that fit their preferences.

**Usage:**

1. Install the required dependencies by running `pip install -r requirements.txt`.

2. Run the system by executing `python main.py`.

3. The system will prompt the user to input movie preferences, and based on the provided data, it will generate a list of personalized movie recommendations.

**Benefits:**

- **Diverse Movie Recommendations:** The LetterboxdMovieRec system offers a wide range of movie recommendations, catering to various user preferences and interests.

- **Exploration of Hidden Gems:** By prioritizing highly rated but less popular movies, the system helps users discover lesser-known movies that might have gone unnoticed otherwise.

- **Personalized Experience:** Users can customize their movie preferences, allowing the system to provide more tailored and relevant recommendations.

**Future Enhancements:**

- **Collaborative Filtering:** Implementing collaborative filtering techniques to enhance recommendation accuracy based on user preferences and similarities.

- **Enhanced UI/UX:** Improving the user interface to provide a seamless and intuitive experience for movie browsing and selection.

- **Real-Time Data:** Integrating real-time movie data to ensure that the recommendation system remains up-to-date with the latest movie releases and ratings.

Author: Hannah Hardy + classmates in Data Structures course
- was used to show case our depth vs breadth search
