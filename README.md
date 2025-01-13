# Top 10000 Songs Case Study

---

 Author: Pedro Bettencourt
 
 Date: January 13, 2025
 
---


# Scenario

Both Billboard and the Australian Recording Industry Association (ARIA) record which songs are the most popular at any given moment.
This information can then be analyzed to find patterns.


### Objectives

* Find patterns within the top songs.

---

# Dataset

The dataset was obtained from [kaggle](https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now/data).
It consists of data from Billboard and ARIA charts the 10000 most popular songs from the 1950s to the present day.
The songs contain information about their release date, length, genre, and spotify metrics, like popularity, danceability, and tempo.
A problem with the dataset is that the date of some songs is not the release date of the actual song, but of an album, which can be a compilation album, that is released much later.


---

# Data preparation

Data preparation was all done using Python's pandas library.
Some columns were irrelevant, such as URLs, so they were dropped.
7 Tracks without information, like track name or spotify metrics, were dropped.


---

# Analysis

The analysis was made with pandas.
Categories analyzed were:
 * Artists with the most hits
 * Genres with the most songs
 * Popularity relative to danceability and other similar metrics
 * Most popular genres
 * Evolution of the number of pop songs

---

# Visualization

The visualizations were done with matplotlib and are mainly bar plots.

---


# Conclusions

We can see that:
 * Pop is the biggest genre in terms of number of hits.
 * Popularity is not correlated with danceability and other spotify metrics.
 * Although pop is the most common genre, other genres have a bigger popularity on spotify, mainly uk dance.
 * Pop saw an increase in the share of top songs throughout the decades, but the 2020s have a significant decrease of pop songs.
 * The ammount of hits increases throughout the decades, indicating either a lesser longevity of hits, or a problem with the dataset that privileged newer songs.

