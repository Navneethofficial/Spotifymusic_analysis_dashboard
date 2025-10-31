# Spotify Music Analysis Dashboard 2023

## Description
The Spotify Music Analysis dashboard offers a detailed visual summary of streaming data for tracks, showcasing total streams, top artists, most-streamed songs and musical features such as energy and danceability. It also highlights playlist placements across Spotify, Apple Music, and Deezer, along with trends in daily and monthly streaming patterns, providing a complete picture of listener behavior and music performance over time.
<br><br>

## Project Overview
### 1. Objective:
- To analyze and understand music streaming trends and audience behavior for strategic decision-making in the music industry.
<br><br>
### 2. Problem Statement
- With the exponential growth of music streaming platforms, understanding user listening behavior, identifying top-performing tracks, and analyzing streaming trends across time and platforms has become crucial. However, raw data alone does not provide clear insights. There is a need for a consolidated, visual dashboard that transforms complex streaming data into actionable insights, helping artists, producers, and music marketers make informed decisions regarding content creation, promotion, and release strategies.
<br><br>
### 3. Tools:
- Power BI
<br><br>

## Data Discription
### 1. Data Source
Data Download- https://docs.google.com/spreadsheets/d/11eiH_HurRXnbymNc4pskPdKhnCtC79Tg/edit?gid=183885892#gid=183885892
<br><br>
### 2. Data Cleaning and Transformation
In Power BI's Power Query Editor, the dataset was cleaned and transformed using the following steps:
- Removed Duplicates:
   - Duplicate rows based on track names or artist-track combinations were identified and removed to maintain data accuracy.
- Handled Missing Values:
   - Columns with null values—especially in streams, release dates, or platform fields—were either filled, replaced with default values, or removed if not essential.
- Changed Data Types:
   - Ensured each column had the correct data type (e.g., date columns converted to Date, stream counts to Whole Number, and categorical fields to Text).
- Renamed Columns:
   - Renamed columns to more readable and consistent formats for better understanding and visualization.
- Filtered Rows:
   - Filtered out irrelevant or incomplete records, such as tracks with zero streams or missing artist names.
<br><br>
### 3. Data Analysis
The data analysis focused on extracting key insights from the Spotify Most Streamed Songs 2023 dataset. Using Power BI, the cleaned and transformed data was analyzed to identify the top-streamed tracks, artists, and overall streaming trends. 
- Key metrics such as total streams, average streams per track, and streams across platforms (Spotify, Apple, Deezer) were calculated. Musical attributes such as danceability, energy, valence, and speechiness were analyzed to understand the characteristics of popular tracks.
- Temporal patterns were explored by analyzing streaming performance by release year, weekday, and month, revealing trends in listener behavior.
- The top 5 most-streamed songs and their attributes were compared, and platform-specific playlist counts were assessed to evaluate cross-platform visibility.
This analysis provided a comprehensive view of what makes a song successful on streaming platforms and offered insights for strategic decisions in music promotion and production.
<br><br>

## Target Audience
The primary target audience for this dashboard includes music industry professionals such as record label executives, music producers, marketing teams, and artist managers who need data-driven insights to guide strategic decisions. Additionally, it caters to data analysts and researchers studying music trends, as well as streaming platform curators aiming to optimize playlist selections based on listener behavior and track performance.
<br><br>

## Key Features
### KPIs
Primary KPIs
- Total Streams: The overall number of streams across all tracks and artists.
- Most Streamed Track: Identifies the top-performing track.
- Average Streams per Track: The average popularity level of tracks.

Secondary KPIs
- Number of Tracks Analyzed: Shows the dataset scale.
- Top 5 Most Streamed Tracks — Compares high-performing songs.
- Track-Level Metrics: Energy %, Speechiness %, Liveness %, Danceability % — used for music characteristic insights.
- Streams by Release Date & Day: Shows trends over time and by week.
- Monthly Streaming Trends: Displays average streams and number of releases per month.
- Platform Playlist Count (Apple, Deezer, Spotify): Measures playlist popularity across platforms.
<br><br>

## Skills Showcased in this Dashboard
- Data Cleaning & Transformation in Power Query Editor.
- Data Modeling and Relationship Management.
- DAX Measures for Aggregation.
- Interactive Visualizations using Filters, Slicers, Charts, and Cards.
- Time Series Analysis (Release Year Trends, Monthly/Weekly Streams).
- Comparative Analysis (Track-level, Artist-level, Platform-level).
- Layout, color consistency, and intuitive navigation.
<br><br>

## Data Visualization
Dashboard Development

The dashboard was developed using Power BI, leveraging its data modeling and visualization capabilities. The process began with importing the cleaned dataset into Power BI, followed by creating relationships and calculated measures (like total streams, average streams, etc.) using DAX. A combination of card visuals (for KPIs), line and bar charts (for temporal trends), tables (for top tracks and playlist data), and donut charts (for distribution across platforms) was used. Interactive slicers were added for track name, artist, and date range to allow dynamic filtering. Consistent color themes, clear labels, and intuitive layout design were maintained throughout to enhance readability and insight extraction.

<p align="center">
<img width="674" alt="Spotify 2023 Dashboard 1" src="https://github.com/user-attachments/assets/d201e2e7-d8f3-4d87-b16e-c42d09ed6fcf" />
</p>

<p align="center">
<img width="675" alt="Spotify 2023 Dashboard 2" src="https://github.com/user-attachments/assets/24fccf90-79c5-4baa-9a37-5eaaa1f6434a" />
</p>

<p align="center">
<img width="673" alt="Spotify 2023 Dashboard 3" src="https://github.com/user-attachments/assets/604e6ef8-3ed4-4b5b-9b9a-66d16ae42a64" />
</p>
<br><br>

## Key Insights
- Blinding Lights by The Weeknd emerged as the most streamed track with over 3.7 billion streams and appeared on 43,899 Spotify playlists, showcasing its massive global popularity.

- The total number of streams across all tracks is 489 billion, with an average of 514 million streams per track, indicating consistently high engagement across the dataset.
  
- Friday saw the highest number of daily streams, suggesting that user engagement peaks towards the weekend, likely due to leisure time and new music releases.
  
- September recorded the highest average streams (734.64M), followed by January and August, highlighting seasonal streaming trends and possibly correlating with release schedules or holiday listening habits.

- The Top 5 streamed tracks include global hits like Dance Monkey, Shape of You, and Someone You Loved, each with significant presence across multiple streaming platforms (Apple, Deezer, Spotify).

- Donut charts indicate Blinding Lights also dominates the Apple and Spotify charts, reinforcing its cross-platform appeal.

These insights help understand user behavior, peak engagement periods, and track performance across streaming platforms.
<br><br>

## Strategic Recommendations
Optimize Release Timing: 
- Since Fridays and months like September, January, and August show peak streaming activity, artists and record labels should target these periods for major releases to maximize visibility and engagement.

Playlist Placement Strategy: 
- Given the strong correlation between playlist inclusions and stream count (e.g., Blinding Lights appearing in 43,899 Spotify playlists), artists should prioritize getting featured in popular and algorithmically driven playlists across platforms like Spotify, Apple Music, and Deezer.

Focus on High-Performing Genres and Features:
- The top tracks often feature high energy and danceability scores. Artists should consider incorporating these musical traits to align with listener preferences and trends.

Cross-Platform Promotion:
- To ensure broader reach, tracks should be strategically promoted across multiple streaming platforms. High-performing songs like Shape of You and Dance Monkey have wide presence across Spotify, Apple, and Deezer.

Leverage Data for Marketing Campaigns: 
- Use insights such as top streaming days, peak months, and most engaged tracks to design targeted social media and advertising campaigns that align with listener behavior.

Explore Seasonal and Event-Based Opportunities: 
- Seasonal spikes suggest potential in aligning releases or promotions with holidays, events, or school breaks to boost engagement.
<br><br>

## Project Scope and Limitations
### 1. Scope:
This project focuses on analyzing the most streamed songs on Spotify in 2023 using a dataset containing 952 tracks. It covers key performance metrics such as total and average streams, musical attributes (energy, danceability, etc.), top-performing tracks and artists, and platform-wise playlist presence (Spotify, Apple, Deezer). The dashboard provides interactive visualizations to explore daily, monthly, and yearly streaming trends, supporting decision-making in music marketing and content strategy.
<br><br>
### 2. Limitations:
- The dataset is limited to only 952 tracks, which may not represent the complete spectrum of streamed music globally.
- Platform data is partially available; some insights rely more heavily on Spotify than Apple or Deezer.
- Listener demographic data (age, region, etc.) is not included, restricting audience-specific analysis.
- The analysis is based on historical data and does not predict future trends or include real-time updates.
- Musical features like energy, valence, or speechiness are subjective and derived from algorithms, which may not capture the full artistic context.
<br><br>

## Conclusion
The Spotify 2023 Dashboard provides a comprehensive and visually engaging analysis of streaming trends, track performance, and listener behavior across major music platforms. It highlights key metrics such as total streams, top artists, and the impact of playlist placements, while also uncovering valuable patterns in daily and monthly listener activity. By combining data-driven insights with intuitive visualizations, the dashboard serves as a strategic tool for music industry stakeholders to make informed decisions on release timing, promotion, and content creation. While limited by dataset scope and absence of demographic data, the analysis successfully delivers actionable insights into the evolving landscape of music streaming.
