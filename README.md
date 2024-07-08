
---

## Project Overview

### Movie Recommendation System

Our project focuses on developing a sophisticated movie recommendation system by leveraging advanced machine learning algorithms. The system integrates both content-based and collaborative filtering methods to form a hybrid model, significantly enhancing the accuracy of recommendations. This report details the methodologies and algorithms employed in our project, including BERT, NCF, SVD, and TF-IDF, leading to exceptional performance.

For an in-depth understanding of the project and the algorithms utilized, please refer to our [Project Report](https://github.com/Karna4571/MovieRecommendationSystem/blob/main/Project%20Report.pdf).

### Website: AI Film-Finder

We have also implemented a user-friendly website, **AI Film-Finder**, which allows users to search for a movie and receive the top 10 similar movies based on our hybrid recommendation model.

**Key Features of AI Film-Finder:**
- **Movie Search:** Users can search for any movie and receive a list of the top 10 similar movies.
- **Detailed Movie Information:** The website fetches comprehensive movie details including title, genre, runtime, rating, and poster, using the [TMDB API](https://www.themoviedb.org/documentation/api).
- **User Reviews and Sentiment Analysis:** By leveraging the IMDB ID of the movie, we perform web scraping to gather user reviews from the IMDB site. These reviews undergo sentiment analysis to provide additional insights into audience reception.

### Methodologies and Algorithms

1. **Content-Based Filtering:**
   - **TF-IDF (Term Frequency-Inverse Document Frequency):** This algorithm analyzes the text descriptions of movies to understand their content and compute similarity scores.

2. **Collaborative Filtering:**
   - **SVD (Singular Value Decomposition):** SVD is utilized to decompose the user-movie interaction matrix, facilitating the prediction of user preferences for unseen movies.
   - **NCF (Neural Collaborative Filtering):** NCF employs neural networks to model complex interactions between users and items, enhancing the prediction accuracy.

3. **Hybrid Model:**
   - **BERT (Bidirectional Encoder Representations from Transformers):** BERT is used to understand the contextual meaning of movie descriptions, improving the content-based recommendations.
   - The hybrid model combines the strengths of both content-based and collaborative filtering approaches, providing more accurate and personalized movie recommendations.

### Conclusion

The integration of these advanced algorithms has resulted in a highly accurate movie recommendation system. AI Film-Finder offers a seamless and insightful experience for users seeking personalized movie recommendations. For a comprehensive understanding of our project and the detailed methodologies, please refer to our [Project Report](https://github.com/Karna4571/MovieRecommendationSystem/blob/main/Project%20Report.pdf).

Explore **AI Film-Finder** and discover movies that match your preferences with precision!

---

Feel free to modify any part of the text to better suit your needs.
