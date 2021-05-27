# Spotify Streaming Data Visualization

This was a personal project to create a custom music streaming visualization. 

The focus was on the entirety of music streaming data from 2020.  Given 'Artist', 'Track', and playtime ('endTime' and 'msPlayed') I engineered new features to sum the time played for each artist per day.  

Then connecting to Spotify's API, I collected the artist metadata (i.e. associated genres) to sum the total time spent listening to particular genres.

_NOTE: spotify claims there is more granular genre data per song, but in nearly every example I tried it was an empty array (even for extremely popular songs/artists)._
## Motivation
- Streamgraph / stackgraph paper
  -  ("Stacked Graphs – Geometry & Aesthetics" http://www.science.smith.edu/dftwiki/images/d/de/ThemeRiver_StackedGraphs.pdf)
- Spotify provides easy API access and semi-easy access to personal data
- Expansion beyond Spotify’s “End of Year” summary:
  - Spotify provides users with some “top” genres, songs, and artists they listened to
- Personalized, emotional connection to listening habits over the year
- Christmas/Birthday gift (asking someone to download their data)

## Data
- Users can request their personal data; however, it is somewhat “hidden” within settings – just google “download Spotify user data” to find it.  
  - Followed by a 2-step authentication, 2-3 day turnaround time and sent via email
-  Data files included:
  - User metadata
  - Followers/Following
  - Saved Library
  - Playlists
  - Search history
  - “inferences” – did not investigate too much but it looks to be tags for a user for advertisements
<img src="https://user-images.githubusercontent.com/26121178/119858361-66b5aa00-bee2-11eb-8349-e5de9cc4a739.jpeg" alt="Heatmap" width="400"/> 
