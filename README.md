# MuseHub-A-Comprehensive-Music-Analytics-and-Recommendation-Framework
An Analytical Approach to Music Insights, Personalization, Visualization, and Recommendation Engin: focuses on exploring music data to uncover patterns in popularity, acoustic features, and artist trends. It integrates Python, SQL Server, and Power BI to deliver insights, visual dashboards, and personalized song recommendations.


## Workflows 


**Data Structure**

Data/
├── metadata/
│   ├── songs/           # Song-level metadata (title, duration, atrist, type, etc.)
│   ├── albums/          # Album-level details (name, release date, etc.)
│   ├── artists/         # Artist profiles (name, genre, followers, etc.)
│   ├── releases/        # Release events (album ID, dates, precision)
│   └── tracks/          # Track-level metadata (song ID, album ID, track number)
│
├── popularity/
│   ├── songs_pop/       # Song popularity scores
│   ├── artists_pop/     # Artist popularity metrics
│   ├── album_pop/       # Album popularity data
│   ├── songs_chart/     # Song chart positions over time
│   ├── artists_chart/   # Artist rankings across time
│   └── album_chart/     # Album charting history
│
└── features/
    ├── features/        # Audio features (tempo, energy, danceability, etc.)
    └── lyrics/          # Full song lyrics

### Data Preprocess
**Power Quary**
1. songs.csv, albums.csv, artists.csv data cleaning completed. 
2. songs.txt, albums.txt, artists.txt tab separated flat text file created.
3. popularity and ranking files created for songs, albums and artists.
4. lyrics file completed.
5. tracks and songs in album files cleaning completed.
6. song effect file completed.
7. genres mapping completed and added to artists data
8. release date addred to both albums and songs data from releases and tracks
9. duration added to songs from features









