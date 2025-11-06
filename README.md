# Spotify_Tracks_Analysis_Dashboard_PowerBI
<img width="957" height="707" alt="Screenshot 2025-11-06 172754" src="https://github.com/user-attachments/assets/04b8e892-dfbe-4e0b-b00f-b0150acf91ee" />
## Project Overview
This project uses the Spotify dataset, which contains detailed information about songs, artists, genres, popularity, and audio features. Using Power BI (or Excel), the objective is to analyse music trends, artist performance, and track characteristics to understand what drives song popularity and listener engagement.
## Dataset Description
The dataset includes song-level and artist-level data containing:
•	Track ID and Track Name
•	Artist Name and Genre
•	Album Name
•	Duration (min)
## Business Objectives
The primary goals of this analysis are:
•	Analyse popularity trends across genres and years.
•	Identify top-performing artists and albums.
•	Understand the correlation between audio features (e.g., energy, danceability) and popularity.
•	Build an interactive Power BI (or Excel) dashboard summarizing insights using charts and filters.
## Tools & Techniques
Microsoft Power BI / Excel
•	Data Cleaning: Handle missing or inconsistent values in popularity, genre, and tempo.
•	Measures & DAX (in Power BI):
o	Average Popularity = AVERAGE(Popularity)
## Visualizations:
•	  Duration Wise Popularity (Scatter chart).
•	Artist Wise Average Popularity (Line chart).
•	Album Wise Total Tracks (Decomposition Tree).
•	Genre Wise Average Popularity (Bar chart).
•	Genre Wise Total Tracks (Pie chart).
•	Genre (Slicer).
## Multivariate Analysis:
 *Bar chart to find Top 10 average popularity by genre and name.
 *Decomposition tree to compare Sum of duration(min), Sum of Popularity, Artist,   Name and Album by name.
## Deliverables
•	Cleaned Spotify dataset (Excel/CSV).
•	Power BI Dashboard showcasing insights.
•	Analytical summary report in Word format.
•	Visual insights with trend analysis and key metrics.
## Future Enhancements
•	Predict Future Popularity:
Use regression analysis or machine learning to predict song popularity based on audio features.
•	Listener Segmentation:
Integrate user data (if available) to cluster listeners by genre preference or engagement time.
•	Playlist Optimization:
Suggest songs for playlists based on tempo, mood, and popularity similarity.
•	Artist Growth Analysis:
Compare how artists’ popularity changes across years and albums.
•	Regional Insights:
Combine with location-based streaming data to analyse genre preferences by country or region.
•	Automated Reporting:
Schedule Power BI refreshes to pull live Spotify data via API for real-time dashboards.
