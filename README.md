# Spotify & YouTube Exploratory Data Analysis (EDA)

This project analyzes data from Spotify and YouTube, focusing on trends, popularity metrics, and relationships between features. Below, you’ll find the objectives of the analysis and a brief explanation of the dataset columns.

---

## Analysis Objectives

1. **Top 10 Songs by Views, Likes, and Comments**  
   Identify the most popular songs based on views, likes, and comments.

2. **Relationship Between Views and Likes**  
   Analyze how YouTube views correlate with likes.

3. **Top Liked and Viewed Songs**  
   Highlight the most liked and viewed tracks on YouTube.

4. **Album Type Percentage Distribution**  
   Visualize the percentage distribution of album types (e.g., single, album).

5. **Top Artists by Streams on Spotify and YouTube**  
   Determine the most listened-to artists across both platforms.

6. **Top YouTube Channels by Views**  
   Discover the channels with the highest view counts.

7. **Popularity Comparison by Genre**  
   Compare the popularity of different music genres.

---

## Dataset Column Descriptions

| Column Name         | Description                                                                                   |
|----------------------|-----------------------------------------------------------------------------------------------|
| `Unnamed: 0`        | Automatically generated index column.                                                         |
| `Artist`            | Name of the artist who performed the song.                                                    |
| `Url_spotify`       | URL link to the song on Spotify.                                                              |
| `Track`             | Name of the song.                                                                             |
| `Album`             | Name of the album containing the song.                                                        |
| `Album_type`        | Type of the album (e.g., Single, Album).                                                      |
| `Uri`               | Unique identifier for the song on Spotify.                                                    |
| `Danceability`      | Danceability score of the song (ranging from 0 to 1).                                          |
| `Energy`            | Energy level of the song (ranging from 0 to 1).                                               |
| `Key`               | Musical key of the song (ranging from 0 to 11).                                               |
| `Loudness`          | Loudness of the song in decibels (dB).                                                        |
| `Speechiness`       | Speechiness score indicating how much spoken word is present in the track (0 to 1).           |
| `Acousticness`      | Probability of the song being acoustic (ranging from 0 to 1).                                 |
| `Instrumentalness`  | Probability of the song being instrumental (ranging from 0 to 1).                             |
| `Liveness`          | Score indicating whether the song was recorded in front of a live audience (0 to 1).          |
| `Valence`           | Measure of the song's positivity or cheerfulness (ranging from 0 to 1).                       |
| `Tempo`             | Tempo of the song in beats per minute (BPM).                                                  |
| `Duration_ms`       | Duration of the song in milliseconds.                                                         |
| `Url_youtube`       | URL link to the song on YouTube.                                                              |
| `Title`             | Title of the video on YouTube.                                                                |
| `Channel`           | Name of the YouTube channel where the song is uploaded.                                       |
| `Views`             | Total number of views on YouTube.                                                             |
| `Likes`             | Total number of likes on YouTube.                                                             |
| `Comments`          | Total number of comments on YouTube.                                                          |
| `Description`       | Description text of the YouTube video.                                                        |
| `Licensed`          | Indicates whether the song is licensed.                                                       |
| `official_video`    | Indicates if the video is an official music video (Yes/No).                                   |
| `Stream`            | Total number of streams on Spotify.                                                           |

---

## Usage

This analysis provides insights for music industry professionals, content creators, and data enthusiasts to understand trends in music consumption across Spotify and YouTube. The analysis results can guide marketing strategies, audience engagement, and platform-specific content optimization.

---

## Visualization Highlights

- **Bar Charts**: Displaying the top 10 songs, artists, and channels.  
- **Scatter Plots**: Illustrating the relationship between views and likes.  
- **Pie Charts**: Showing the percentage distribution of album types.  
- **Genre Popularity Comparisons**: Highlighting genre-specific trends.

---

Feel free to explore the results and modify the dataset or visualizations for further insights!
