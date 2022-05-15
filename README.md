# data-vis-spotify-songs-dataset

This project was developed for Data Visualization course's project.

## Dataset Selection
We chose a dataset on a subject which all team's members were excied to explore and in the same time could give us a diversification in the number of plot types that we could build.

The subject we all agreed on was music. We looked over the internet and found some interesting dataset provided by the well-known music platform, Spotify.
The dataset contains more *.csv* files in which we can find a lot of characteriscs for a song.

In this list of features we have:

*data.csv* file:
Name Column Type
*   valence - *float* \[0, 1] interval
*   year - *int* \[1921, 2020] interval
*   acousticness - *float* \[0, 1] interval
*   artists - *string* list of the song's artists
*   danceability - *float* \[0, 1] interval
*   duration_ms - *int*
*   energy - *float* \[0, 1] interval
*   explicit - possible values: {0, 1}
*   id - *string*
*   instrumentalness - *float* \[0, 1] interval
*   key - possible values: from 0 to 11
*   liveness - *float* \[0, 1] interval
*   loudness - *float* \[0, 1] interval
*   mode - possible values: {0, 1}
*   popularity - possible values: from 0 to 100
*   release_date - *date*
*   speechiness - *float* \[0, 1] interval
*   tempo - *float* \[0, 1] interval

*genre_music.csv* file - has in general the same song features, but it also includes the music *genre* of the songs 


## Data Preprocessing
In this section we did a little preprocessing of the main working dataset file, *data.csv*. We excluded the columns that did not present any interest, like the *song's id*, representing only an identification string and also *song's release_date* since we already had the *year* column.
