<h1>Movie Recommendation System</h1>

<h3>Introduction</h3>
This project implements a movie recommendation system using various techniques, including Content-Based, K-Nearest Neighbors (KNN), and Genre-Based approaches. The system analyzes user preferences and suggests movies based on different factors such as content similarity, user behaviour, and genre preferences.

<h3>Dependencies</h3>
Make sure you have the following dependencies installed before running the code:

Python 3.x
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
TensorFlow
Keras
Joblib
You can install the required libraries using the following command:

pip install -r requirements.txt

<h3>Dataset</h3>
The movie recommendation system uses the <a href="https://www.kaggle.com/datasets/shubhammehta21/movie-lens-small-latest-dataset">Dataset</a> for movies and ratings. Please refer to the dataset documentation for more details.

<h3>Code Structure</h3>
The project is structured as follows:

Models
1. Content-Based Recommendation
This model suggests movies based on the content similarity of movie genres. It utilizes a CountVectorizer for tokenizing and creating a matrix of movie genres.

2. K-Nearest Neighbors (KNN) Recommendation
The KNN model recommends movies by calculating cosine similarity between movies. It uses a pivot matrix with user ratings to find similar movies.

3. Genre-Based Recommendation
This model suggests movies based on the similarity of movie genres. It calculates the Euclidean distance between the genres of a selected movie and others.

<h3>Performance Analysis</h3>
The best-performing model is Content-Based.

<h3>Usage</h3>
Clone the repository:
```git clone https://github.com/your-username/movie-recommendation-system.git```
```cd movie-recommendation-system```
Run the collab file
Follow the instructions in the notebook to execute and test the recommendation system.

<h3>Future Work</h3>
This project can be further enhanced by:

Incorporating user feedback for more personalized recommendations.
Implementing collaborative filtering for a hybrid recommendation system.
Scaling the system to handle larger datasets.


