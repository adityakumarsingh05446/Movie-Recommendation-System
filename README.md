# Movie-Recommendation-System

## Introduction : 
- It is a content based recommender system with Heroku deployment.
- This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations.
- The general idea behind these recommender systems is that if a person likes a particular item, he or she will also like an item that is similar to it.
- Broad idea of NLP and Text-Vectorization using Bag of Words.


## Working

- Each movie consist of { MOVIE_ID , MOVIE_NAME , MOVIE_DESCRIPTION }
- Use the idea of Text-Vectorization convert MOVIE_DESCRIPTION into vectors of matrix.
- The similar recommendation for movies is made by calculating cosine distance between the vectors and fetching out 5 possible nearest vectors.

 
## Tools Used

Python , Pandas , NumPy , Seaborn , Matplotlib , streamlit , NLP, Count Vectorizer,  wordcloud , urlextract , RegEx , pickle , collections , Heroku , requests .


# Deployment Link
Live Project Link : https://movie-recommender-system-101.herokuapp.com/
(Please click the link to checkout the application.)


## Future Work :
- Using the generic techniques , will try to find out the sentiments for a selected user.
- Using more advance streamlit functions to make this web app more faster and more responsive.
- Will be trying to host this application on AWS.

## Related Usage :
- The idea behind this project can be used to make similar recommender system like books recommender system , TV series recommender system and much more.
- On large scale it can be used on fintech websites to give insights to potential users like on Meta : feeds recommender system and much more.

## Video
https://user-images.githubusercontent.com/83591758/139529773-c92ca204-d19c-4dee-9c8b-ccd77b9ff341.mp4




