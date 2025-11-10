# Spotify-Data-Analysis
The Top-50-World Power BI project analyzes Spotify’s Global Top 50 chart to uncover trends in song popularity, artist rankings and album performance. Using DAX measures, it visualizes insights on duration, explicit content and release trends, revealing what makes songs and artists rise to the top.


📂 Dataset Columns
Column	Description
date	Date when the song appeared on the chart
position	Chart rank (1–50)
song	Song name
artist	Artist name
popularity	Popularity score (0–100)
duration_ms	Duration of song in milliseconds
album_type	Type of album (single, album, compilation)
total_tracks	Total number of tracks in that album
release_date	Date when the song/album was released
is_explicit	Indicates if song has explicit content
album_cover_url	Album art URL (used for visuals)


⚙️ Tech Stack

Tool: Power BI Desktop

Language: DAX (Data Analysis Expressions)

Data Source: Spotify Global Top 50 Dataset (CSV)

Visualization Tools: Power BI Charts, Cards, KPIs, and Custom Visuals


📈 Key DAX Measures

Some of the measures defined in this project:

Total Songs

Distinct Artists

Average Popularity

Average Chart Position

Avg Duration (mins)

Explicit %

Avg Total Tracks per Album

Weighted Popularity by Duration

Avg Popularity per Artist

Popularity Change %

Average Release Year

👉 All measures are defined in DEFINE MEASURE format for easy integration into Tabular Editor or DAX Studio.


💡 Insights Gained

Identify the most popular artists and songs globally.

Discover how song duration and explicit content influence popularity.

Explore release trends — are newer songs dominating charts?

Understand how album type impacts average chart position.

Visualize popularity trends over time using the date field.


📊 Power BI Dashboard Highlights

🎤 Top Artists Overview: Popularity, chart positions, and song counts.

🎵 Song Analytics: Duration, explicit ratio, and track distribution.

📅 Time-Based Analysis: Popularity trend lines by date or release year.

💿 Album Insights: Breakdown of singles vs full albums.

🧩 Interactive Filters: Explore by artist, album type, or release period.


🚀 How to Run

Load the dataset (Top-50-World.csv) into Power BI Desktop.

Open the DAX script (provided as .dax or .txt) and paste it into Tabular Editor or DAX Studio.

Refresh visuals and explore interactive charts.

Optional: Publish the dashboard to Power BI Service for online access.


📁 Project Structure
Top-50-World/

│
├── data/
│   └── Top-50-World.csv

│
├── dax/
│   └── measures_top50world.dax

│
├── reports/
│   └── Top-50-World.pbix

│
├── README.md
│   └── visuals/
    └── dashboard_screenshots.png

🧠 Future Enhancements

Add genre-based analysis (if dataset expanded).

Integrate with Spotify API for live chart updates.

Build AI-driven song recommendation dashboard using Power BI + Python.

🏷️ Tags

#PowerBI #DAX #SpotifyData #DataAnalytics #MusicInsights #DataVisualization #Top50World
