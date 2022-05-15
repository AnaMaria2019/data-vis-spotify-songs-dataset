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


## Data Visualization
This section was dedicated completely to highlighting the look of our data by illustrating using either static or nice interactive plots.

We first started with some statiscs that interested us, for example how the music industry increased over the years and what are the most popular music genres.

Some of our plots are:
![nr-songs-per-year](https://user-images.githubusercontent.com/48510687/168493691-b22c5a04-03cd-47ed-b417-9e2fd443e4fa.PNG)

![music-genres-pie-plot-interactive](https://user-images.githubusercontent.com/48510687/168493710-9a2ae0ed-33aa-4784-aaef-7397553ad7bc.png)

Then we made progress in the direction of preparing and analyzing the data when it comes to solving a Machine Learning Task. For this matter, we were interested in the *features correlation* and *features distribution* in our dataset.

* Heatmap Correlation Matrix
![heatmap-correlation-matrix](https://user-images.githubusercontent.com/48510687/168493806-ea5abc40-2748-41e4-82f7-6e5dcc3d1a7f.PNG)

* Features Distribution Plot

![features-distribution](https://user-images.githubusercontent.com/48510687/168493871-16b9e915-cb50-47c5-b2e0-fba24eb52365.PNG)

* *danceability* feature distribution evolution over the years
![danceability-features-evolution](https://user-images.githubusercontent.com/48510687/168493929-5e6a778b-5ce1-44b8-ac75-0f29b53675e5.PNG)

* *key* feature pie plot and histogram plot:
![key-feature-subplots](https://user-images.githubusercontent.com/48510687/168493991-9e27788a-4fc0-492f-87fa-265ff5494b6f.png)
