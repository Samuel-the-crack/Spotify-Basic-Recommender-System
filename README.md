# Spotify-Recommender-System
Making a recommendation system using cosine similarities 
</p>
<p align = 'center'><img src = 'https://github.com/Samuel-the-crack/Spotify-Recommender-System/blob/main/Picture/Spotify_Logo_CMYK_Green.png', width = 450>
  
## A. Background 
Recommendation system has been an important technology in a digital streaming platform specifically music streaming platform, and based on my experience spotify has the  best reccomendation system compared to other competitor. In this project I used cosine similarity, the input of this model was song title (string) and the output was a dataframe of top 10 recommendation songs. I used the spotify_data.csv for complete information about the data you can check it [here](https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset/data).

**Requirement: Numpy, Pandas, Matplotlip, Seaborn, sklearn.**
 
## B. Overview
First thing to do on this project was doing a preprocessing based on it's basic statsistical information (outliers and distribution). Column that I analyse was 'acousticness', 'danceability', 'energy', 'instrumentalness', 'liveness', 'loudness', 'speechiness', 'tempo', and 'valence'. After the data was preprocessed I applied the cosine similarity, and made a function to show the simillar songs based on the input. 
The image below was the result of this model.
<p align = 'center'><img src = 'https://github.com/Samuel-the-crack/Spotify-Recommender-System/blob/main/Picture/recommender%20system%20output%20input.JPG', width = 275>

For further informations and source code you can see it on this [link](https://github.com/Samuel-the-crack/Spotify-Recommender-System/blob/main/Spotify%20Recommender%20.ipynb).
