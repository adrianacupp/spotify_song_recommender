# spotify_song_recommender
ironhack
Adriana Cuppuleri

Data Analytics, Berlin 2022


# Project Description
A key feature of Spotify is the song recommendations that populate your homepage, but in fact, every music streaming service has some kind of music recommendation algorithm. Each music service provider is competing to give their listeners the joy of discovering new music, and there are a wide array of algorithmic approaches companies are taking. This third project of the bootcamp got me familiar with Machine Learning, through the use of web scraping techniques, APIs and modelling methods such as the K-Means method.

# Database
In order to create a large dataset to base the recommendations on, the Spotify API has been used in order to retreive data, covering the following parameters of the song: Title, URI, Artist, Popularity and its audio features (danceability, energy, key, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duratin in ms and time signature.

# Workflow
Web scraping the Hot 100 Billboard and creating a dataframe with the current hot 100 songs.
Using Spotify API to create a large dataset with almost 60k songs and its audio features.
Normalizing the data from the previous dataset and creating eight different clusters depending on the song audio features, with the K-means method.
Creating the final prototype of the program, which checks if the user's choice is in the Hot 100 Billboard list and gives a hot recommendation if so. On the other side, if the song is not hot anymore, the program will recommend another song from Spotify based on the song audio features of the user's choice. Flowchart of the program
![alt text](https://github.com/annafonte/spotify-song-recommender/blob/main/Images/workflow.png)
