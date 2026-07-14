
 Spotify Trends & Opportunities Dashboard

An interactive Tableau dashboard analyzing 230,000+ Spotify tracks across 26 genres to uncover what drives track popularity — built to surface insights an organisation could use for content strategy, catalogue planning, and artist scouting.

**[ View the live dashboard on Tableau Public] https://public.tableau.com/views/SpotifyTrendandOppertunities/SpotifyTrendsOpportunities?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

![Dashboard Preview]<img width="1912" height="920" alt="Screenshot 2026-07-11 184827" src="https://github.com/user-attachments/assets/77d26da1-fa88-47fd-9abc-8d4745eec279" />


---

 ## Overview

This project explores the [Spotify Tracks Dataset](#) (232,725 tracks, 18 audio/metadata features per track) to answer a core question: **what audio and structural characteristics are associated with higher track popularity, and how does this vary by genre?**

The dashboard combines genre-level comparisons, feature correlation analysis, and artist-level rankings into a single interactive view.

 ## Tools & Skills

- **Tableau Public Desktop** — dashboard design, calculated fields, dual-axis charts, Top N filtering, context filters, heatmaps
- **Data cleaning** — resolving encoding inconsistencies (duplicate genre labels), correcting Excel auto-formatting corruption in categorical fields, handling nulls
- **Exploratory data analysis** — correlation analysis, genre segmentation, outlier identification
- **Data storytelling** — translating statistical findings into a clear, non-technical dashboard narrative

## Key Insights

- **Loudness (+0.36) and acousticness (−0.38)** are the two strongest correlates with popularity — louder, less acoustic tracks trend more popular across the dataset.
- **Danceability and energy** show a moderate positive relationship with popularity, but genre membership itself is a stronger predictor than any single audio feature — tracks cluster into distinct popularity "bands" primarily by genre.
- **Track duration has a sweet spot**: popularity peaks for tracks 3–5 minutes long, dropping off for very short (<2 min) or long (6+ min) tracks.
- **4/4 time signature dominates** the catalogue and outperforms less common time signatures on average popularity.
- **Genres have distinct "audio fingerprints"** — e.g. Classical and Soundtrack score high on acousticness/instrumentalness and low on danceability/energy, while Rap/Hip-Hop score high on speechiness.
- **Popularity and catalogue volume are not correlated at the artist level** — some of the most prolific artists in the dataset (by track count) have low average popularity, while smaller, high-impact artists (e.g. Billie Eilish, Post Malone) lead on average popularity.

## Dashboard Contents

| Sheet | What it shows |
|---|---|
| Genre vs. Average Popularity | Which genres perform best/worst |
| Loudness vs. Popularity by Genre | Feature-level correlation with popularity, colored by genre |
| Genre Audio Fingerprint Heatmap | Comparative audio profile across six key features |
| Popularity by Track Duration | The duration "sweet spot" for popularity |
| Popularity by Key and Mode | Minor vs. major key performance |
| Time Signature: Popularity vs. Track Count | Catalogue composition and its relationship to popularity |
| Top Artists by Average Popularity | Highest-performing artists (min. 20 tracks) |

##  Repository Contents

```
├── SpotifyFeatures.csv          # source dataset
├── Spotify_Trends_Opportunities.twbx   # Tableau packaged workbook
├── Spotify_Trends_Opportunities_Analysis.md   # full written analysis
└── README.md
```

##  How to View

1. Download `Spotify_Trends_Opportunities.twbx`
2. Open with [Tableau Public Desktop](https://public.tableau.com/) (free)
3. Or view the interactive version directly via the published link above

##  Contact

*www.linkedin.com/in/niroshajayasundara
