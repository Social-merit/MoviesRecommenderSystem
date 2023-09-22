### Content-Based Movie Recommendation System with Sentiment Analysis

#### Overview:

This advanced movie recommendation system leverages multiple technologies like Python, Flask, and various APIs to provide a nuanced recommendation. It gathers comprehensive information about a range of movies and uses both metadata and sentiment analysis of user reviews for personalized suggestions.

#### Technologies Used:

- **Python**: Core programming language for data processing and analytics.
- **Flask**: Web framework for deploying the recommendation system.
- **themoviedb.org API**: For fetching movie details like title, runtime, rating, and poster images.
- **Wikipedia API**: For additional movie context and details.
- **Scikit-learn**: For building the content-based recommendation model.
- **Natural Language Toolkit (NLTK)**: For sentiment analysis on user reviews.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **JavaScript, HTML, CSS**: For frontend development.

#### How it Works:

1. **Data Extraction**:
    - Movie details are fetched from themoviedb.org API.
    - Additional information is pulled from Wikipedia using its API.

2. **Feature Compilation**:
    - Creates a 'feature vector' for each movie, including genres, director, main actors, etc.
    - User reviews are fetched and sentiment analysis is performed.

3. **Content-Based Filtering**:
    - A cosine similarity matrix is generated using Scikit-learn.
    - Sentiment scores from user reviews are integrated into this similarity matrix.

4. **Recommendation**:
    - The system finds the most similar movies based on the modified cosine similarity matrix.
    - It returns a list of recommended movies sorted by their similarity scores.

#### Additional Features:

- **Auto-Suggest**: Suggests possible matches while typing a movie name.
- **Interactive UI**: Displays each recommended movie with its poster, and more details upon clicking.

#### Benefits:

- **Personalized**: Sentiment analysis adds an emotional tone to the recommendations.
- **Comprehensive**: Multi-source data gathering for well-rounded recommendations.
- **Dynamic**: Constantly evolving recommendations based on new user reviews.
### Screenshot

![Image](/static/MoviesRecommendationSystem.gif)


## Running Flask Tests

To run a Flask deployment tests, run the following command

```bash
python -m venv env  ==== to create venv

.\venv\Scripts\Activate ==== to active env

 Flask run  == python main.py

```

## Deployment

### Steps To Deploy The App:

Prepare your dataset:

        1. Data Extraction
        2. Exploratory Data Analysis(EDA)
        3. Feature Engineering
        4. Model Building and Tuning
        5. Building Flask API
        6. Pushing code to Github
        7. Connecting to your Heroku account 
        8. Deploy App








## 🛠 Skills
- Python  
- Data Science
- Statistics  
- Machine Learning 
- Deep Learning
- Project Management





