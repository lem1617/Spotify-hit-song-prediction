# Spotify-hit-song-prediction

## INTRODUCTION
What features contribute to a popular song? How can a song, although newly released, become a hit. In this study, I attempt to use a machine learning model to classify a song as hit or non-hit with 4242 tracks. Since the rise of the internet changed the way people listen to music, data were chosen within the recent decade to have an insight on the transition of people favors. Spotify provides us an opportunity to explore these questions by collecting data via their API. With the Spotify Developer Platform, we are able to read calculated audio features of tracks to learn about their danceability, energy, valence, and more. For more advanced use cases, it is
possible to obtain in-depth analysis about tracks such as the audio features.

This project will focus on specific parts of a song to dig out the characteristics which benefit both industry and musicians. Not only will this help musicians to exaggerate some parts of songs to maximize their potential popularity, but it could also be useful for the industry to decide which songs should be invested in an advertisement.

## DATA SETS
The first dataset includes Global Top 200 songs weekly from Spotify which has 4242 songs collected from 2017 to 2021. 
The second data set is the additional data, including 1.2 million random songs. Using Spotify's Audio Features & Analysis API, the following features were collected for each song:

● Mood: `Danceability`, `Valence`, `Energy`, `Tempo`

● Properties: `Loudness`, `Speechiness`, `Instrumentalness`

● Context: `Liveness`, `Acousticness`

In additional, populatiry score was collected to to enrich the feature

## EDA
#### Radar Plot
![image](https://user-images.githubusercontent.com/89247170/214058640-ccd94604-1e77-477c-aa75-997417ab9c9e.png)

#### Boxplot & Violinplot
![image](https://user-images.githubusercontent.com/89247170/214058908-eb239e77-b197-442a-9fc6-e7affa8d28e1.png)

#### Histogram
![image](https://user-images.githubusercontent.com/89247170/214059003-397ad80c-d2ad-4907-9e25-37ae946e386e.png)

## DATA SOURCE
The data set used comes from Kaggle source:
https://www.kaggle.com/bartomiejczyewski/spotify-top-200-weekly-global-20172021
https://www.kaggle.com/rodolfofigueroa/spotify-12m-songs
