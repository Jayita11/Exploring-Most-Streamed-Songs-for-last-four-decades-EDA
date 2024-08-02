# Exploring-Most-Streamed-Songs-for-last-four-decades-EDA

## Project Overview

### 1. Introduction

This project performs an Exploratory Data Analysis (EDA) on a dataset containing information about the most streamed songs over the past four decades. The objective is to uncover insights and trends in streaming patterns, analyze the distribution of genres and artists, and perform hypothesis testing to understand significant aspects of the data.

![ee448741-8af7-4a25-a0ab-0a4d3a82861c](https://github.com/user-attachments/assets/5d74d780-4c27-4dc2-8ec3-4004c0834507)

### 2. Objectives

The primary objectives of this project are:
- To perform data cleaning and preparation.
- To explore the dataset and gain insights into streaming patterns across different decades.
- To analyze the distribution of genres and artists.
- To perform hypothesis testing to draw significant conclusions from the data.
- To visualize the data to better understand the underlying patterns and trends.

### 3. Dataset Description

The dataset used in this project contains various columns representing different attributes of the most streamed songs. Key columns in the dataset include:
- `Track`: Title of the song.
- `Album Name`: Name of the album.
- `Artist`: Name of the artist.
- `Release Date`: Year the song was released.
- `ISRC`: International Standard Recording Code.
- `All Time Rank`: Ranking of the song based on streams.
- `Track Score`: Score assigned to the track.
- `Spotify Streams`: Number of times the song has been streamed on Spotify.
- `Spotify Playlist Count`: Number of playlists the song is featured on Spotify.
- `Spotify Playlist Reach`: Reach of the playlists the song is featured on Spotify.
- `Spotify Popularity`: Popularity score on Spotify.
- `YouTube Views`: Number of views on YouTube.
- `YouTube Likes`: Number of likes on YouTube.
- `TikTok Posts`: Number of posts featuring the song on TikTok.
- `TikTok Likes`: Number of likes on TikTok.
- `TikTok Views`: Number of views on TikTok.
- `YouTube Playlist Reach`: Reach of the playlists the song is featured on YouTube.
- `Apple Music Playlist Count`: Number of playlists the song is featured on Apple Music.
- `AirPlay Spins`: Number of spins on AirPlay.
- `SiriusXM Spins`: Number of spins on SiriusXM.
- `Deezer Playlist Count`: Number of playlists the song is featured on Deezer.
- `Deezer Playlist Reach`: Reach of the playlists the song is featured on Deezer.
- `Amazon Playlist Count`: Number of playlists the song is featured on Amazon.
- `Pandora Streams`: Number of streams on Pandora.
- `Pandora Track Stations`: Number of stations featuring the track on Pandora.
- `Soundcloud Streams`: Number of streams on Soundcloud.
- `Shazam Counts`: Number of times the song has been Shazamed.
- `TIDAL Popularity`: Popularity score on TIDAL.
- `Explicit Track`: Indicates if the track is explicit.

### 4. Methodology

The project follows a structured approach to explore and analyze the dataset:

#### a. Data Cleaning
- Handling missing values.
- Ensuring consistency in data types.
- Removing duplicates.
- Creating New Data Fields

#### b. Data Exploration
-The data exploration phase involves multiple types of analysis to gain comprehensive insights into the dataset:

##### i. Univariate Analysis
- Analyzing individual columns to understand their distribution and identify any outliers.
- Example: Distribution of `Spotify Streams`, `YouTube Views`, etc.

##### ii. Bivariate Analysis
- Exploring the relationships between two variables.
- Example: Correlation between `Spotify Streams` and `YouTube Views` etc.

##### iii. Multivariate Analysis
- Examining the interactions between multiple variables.
- Example: Analyzing how `Spotify Streams`, `YouTube Views`, and `TikTok Posts` collectively impact the popularity of a song etc.

#### c. Visualization
- Creating visualizations to represent the data insights.
  - Bar plots, pie charts, line graphs, and bubble plots are used to illustrate key findings.

#### d. Hypothesis Testing
- Performing statistical tests to draw significant conclusions from the data.
  - Example Hypothesis: There is no significant difference in the average Spotify Streams between songs released in the first half of the year and those released in the second half.



### 5. Insights

Some of the key insights derived from the analysis include:
- **Missing Values:** Columns like `TIDAL Popularity`, `Soundcloud Streams`, and `SiriusXM Spins` have a high percentage of missing data. Prioritize analysis on the complete columns and consider imputing or addressing the substantial gaps in the others.
- **Data Correlation:** Strong positive correlations between TikTok metrics (Likes, Views, Posts) and moderate positive correlations between Spotify metrics (Streams, Playlist Count, Playlist Reach).
- **Explicit Content:** Non-explicit tracks dominate top positions in streams and likes. Artists like Bad Bunny, Doja Cat, Drake, and Kreepa are popular with explicit tracks.
- **Artist Popularity:** Drake has the highest total playlist count, with Bad Bunny, The Weeknd, and Travis Scott also highly popular.
- **Release Patterns:** The peak album release period is in May, with significant releases in March, April, and May. There is a noticeable decline in album releases in June.

### 6. Conclusion

The project highlights the transformative impact of streaming platforms on the music industry. By analyzing the most streamed songs over the last four decades, we gain a deeper understanding of how music consumption has evolved. The findings from this project can inform music producers, artists, and industry stakeholders about current trends and potential future directions.

### 7. Future Work

Potential areas for future work include:
- Expanding the dataset to include more recent streaming data.
- Analyzing the impact of external factors such as social media and marketing on streaming trends.
- Exploring the relationship between streaming numbers and other metrics like concert ticket sales and merchandise revenue.

## Project Structure

The repository contains the following files:
- `Exploring_Most_Streamed_Songs_for_last_four_decades_EDA.ipynb`: Jupyter notebook containing the entire exploratory data analysis.
- `most_streamed_songs.csv`: Dataset file (ensure it is placed in the specified directory).
- `README.md`: Project documentation file.

## Setup Instructions

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Exploring_Most_Streamed_Songs.git](https://github.com/Jayita11/Exploring-Most-Streamed-Songs-for-last-four-decades-EDA




