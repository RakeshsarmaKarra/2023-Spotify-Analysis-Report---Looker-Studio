
[![Image](https://github.com/RakeshsarmaKarra/2023-Spotify-Analysis-Report---Looker-Studio/blob/main/2023_Spotify_Analysis_Report.jpg)](https://lookerstudio.google.com/s/vvDidkNoPIQ)

## Dataset Overview

The **2023 Spotify Analysis Dataset** is a comprehensive collection of music streaming data that captures key attributes and performance metrics for popular tracks across various streaming platforms. The dataset includes **645 unique artists** and tracks detailed information about **489,458.83 million total streams**. [lookerstudio.google](https://lookerstudio.google.com/reporting/eda6b4e0-2bcf-423d-84f4-309054169b28/page/LETgF?s=ukskrVg_e-g)

### Dataset Structure

The dataset contains the following key dimensions:

**Track & Artist Information:**
- Track name and artist(s) details
- Artist count (solo or collaborative tracks)
- Release date information (year, month, day)

**Streaming Platform Metrics:**
- Spotify playlist inclusions and chart presence
- Apple Music playlist and chart appearances  
- Deezer playlist and chart rankings
- Shazam chart performance

**Audio Features (Technical Attributes):**
- BPM (Beats Per Minute)
- Musical key and mode
- Danceability score
- Valence (musical positivity)
- Energy level
- Acousticness percentage
- Instrumentalness
- Liveness
- Speechiness

**Performance Metrics:**
- Total streams (in millions)

This rich dataset enables multi-dimensional analysis of music trends, artist popularity, audio characteristics, and cross-platform performance patterns.

***

## Dashboard Analysis

The **Looker Studio dashboard** provides an interactive visual exploration of the 2023 Spotify dataset through four primary analytical components: [lookerstudio.google](https://lookerstudio.google.com/reporting/eda6b4e0-2bcf-423d-84f4-309054169b28/page/LETgF?s=ukskrVg_e-g)

### 1. **Interactive Filters**
The dashboard offers two control filters at the top:
- **Select Artist Name**: Allows users to drill down into specific artist performance
- **Select Date Range**: Enables temporal analysis of release patterns

### 2. **Key Performance Indicators**
Two summary metrics provide immediate insight:
- **Total Artists**: 645 unique artists represented in the dataset
- **Total Streams**: 489,458.83 million streams across all tracks

### 3. **Singer Name's - # of Songs**
A ranked table highlighting the most prolific artists in the dataset:
- **Taylor Swift** leads with 34 songs
- **The Weeknd** follows with 21 tracks
- **SZA** and **Bad Bunny** each have 19 songs
- Other top contributors include Harry Styles (17), Kendrick Lamar (12), Morgan Wallen (11), and Ed Sheeran (9)

This visualization helps identify which artists have the strongest catalog presence in 2023's popular music landscape.

### 4. **Year-wise - # of Songs**
A time-series line chart showing the distribution of track releases from 1930 to 2018+. The chart reveals:
- Minimal releases before 2000
- Gradual increase starting in the early 2000s
- **Dramatic spike after 2018**, indicating that the vast majority of popular tracks in 2023 were released in recent years
- This pattern aligns with streaming platform growth and the shift in music consumption habits

### 5. **Audio Feature Comparison**
A horizontal stacked bar chart comparing three key audio characteristics across popular songs:
- **Acousticness %** (Green): Presence of acoustic elements
- **Energy %** (Orange): Intensity and activity level
- **Danceability %** (Blue): Suitability for dancing

Sample insights from the visualization:
- **"Miss You"** shows balanced characteristics with moderate acousticness (127), energy (108), and high danceability (153)
- **"Prohibidox"** has high acousticness (97) but negative energy (-134), suggesting a mellower sound profile
- **"Ferxxo 100"** demonstrates high acousticness (92), moderate energy (46), and moderate danceability (56)

This comparison helps understand the sonic diversity and production trends of popular tracks.

### 6. **Playlists Comparison**
A horizontal stacked bar chart displaying cross-platform playlist presence:
- **Apple Playlists** (Green)
- **Deezer Playlists** (Orange)  
- **Apple Playlists** (Blue - appears to be a duplicate label)

Key findings:
- **"Blinding Lights"** demonstrates strong cross-platform presence (672 Apple, 3,421 Deezer, 672 Apple)
- **"One Dance"** shows particularly high Deezer engagement (3,631 playlists)
- **"Dance Monkey"** maintains consistent presence across platforms (533 Apple, 3,595 Deezer, 533 Apple)

This visualization highlights which tracks achieved broader distribution and curator support across multiple streaming ecosystems, indicating marketing reach and organic discovery potential.

***

## Key Insights

1. **Recent Music Dominance**: The dataset heavily features tracks released after 2018, reflecting contemporary listening preferences and the recency bias of streaming platforms.

2. **Artist Concentration**: A small group of prolific artists (Taylor Swift, The Weeknd, SZA) contribute a significant portion of the popular catalog, suggesting strong fan engagement and consistent output.

3. **Audio Diversity**: Popular tracks exhibit varying audio profiles—from high-energy dance tracks to acoustic ballads—indicating that multiple genres and styles can achieve streaming success.

4. **Cross-Platform Strategy**: Tracks with the highest stream counts typically maintain strong presence across multiple platforms (Spotify, Apple Music, Deezer), underscoring the importance of multi-platform distribution strategies.

***

## Technical Implementation

- **Visualization Tool**: Google Looker Studio
- **Data Source**: CSV file containing 2023 Spotify track data
- **Dashboard Features**: Interactive filters, KPI cards, tables, time-series charts, and comparative horizontal bar charts
- **Last Updated**: 1/17/2024, 1:13 AM

This dashboard enables stakeholders whether music analysts, artists, or industry professionals to explore streaming trends, understand audio characteristics that drive popularity, and benchmark artist performance in the competitive 2023 music landscape.
