## Movie Recommendation System
It is a content-based movie recommendation system that uses cosine similarity. <br>
In this, I use [streamlit](https://streamlit.io/), which is an open-source app framework in Python language, which turns data scripts into shareable web apps in minutes. <br>
## How to use
Firstly, download the [training data from Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download). It will be a zip file. Unzip it and place it in the **Movie Recommendation System** folder. <br>
Now, to train the model, run the [modelTraining.ipynb](https://github.com/Bhavik1603/Movie-and-Book-Recommendation-System/blob/main/Movie%20Recommendation%20System/modelTraining.ipynb) file. It will create two pickle files: **movie_list.pkl** and **similarity.pkl**. <br>
Now, simply run **app.py**.
