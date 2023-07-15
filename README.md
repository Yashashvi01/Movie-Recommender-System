# Movie Recommendation System

[Live Link](https://movie-recommender-system-6fyj1znh1s4.streamlit.app/)


This is a movie recommendation system implemented using a machine learning algorithm called Cosine Similarity. It provides personalized movie recommendations based on the user's preferences and the similarity between movies.

## Dataset

The dataset used for this recommendation system consists of 5000 movies. Each movie is described by several features such as title, genre, director, actors, and more. The dataset provides the necessary information to build a content-based recommendation system.

## Machine Learning Algorithm

The recommendation system utilizes the Cosine Similarity algorithm to measure the similarity between movies. Cosine Similarity calculates the cosine of the angle between two vectors, which in this case represents the movie's features. By comparing the features of different movies, the system can recommend movies that are similar to the ones the user likes.

## Live Demo

A live demo of the movie recommendation system can be accessed [here](https://movie-recommender-system-6fyj1znh1s4.streamlit.app/). The web application is built using Streamlit, a popular Python library for creating interactive data apps. The user interface is designed to be intuitive and user-friendly, allowing users to input their movie preferences and receive personalized recommendations.

## Usage

To run the recommendation system locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/Yashashvi01/Movie-Recommender-System.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Run the Streamlit app:

```
streamlit run app.py
```

4. Access the application in your web browser at `http://localhost:8501`.


## Contributing

Contributions to this movie recommendation system are welcome. If you encounter any issues, have suggestions for improvement, or want to add new features, please submit an issue or create a pull request.


Feel free to explore and enjoy the movie recommendation system!
