# YouTube Trending Analysis Dashboard

An end-to-end data analytics project analyzing YouTube trending videos using **Python, Pandas, SQLite, VADER Sentiment Analysis, and Tableau**.

## Project Overview

This project explores patterns in YouTube video popularity, audience engagement, title sentiment, publishing country, content category, and trending duration.

The workflow covers:

- Data preparation and exploratory analysis using Python and Pandas
- Structured data storage and analysis using SQLite
- Sentiment analysis of video titles using VADER
- Performance analysis using views, likes, and comments
- Interactive visualization and dashboard development in Tableau

## Dataset

The dataset contains YouTube trending-video information including:

- `video_id`
- `trending_date`
- `title`
- `channel_title`
- `category_id`
- `publish_date`
- `time_frame`
- `published_day_of_week`
- `publish_country`
- `tags`
- `views`
- `likes`
- `dislikes`
- `comment_count`
- `comments_disabled`
- `ratings_disabled`
- `video_error_or_removed`

Additional analytical columns created during the project:

- `title_sentiment_score`
- `title_sentiment`

### Time Period

- **Trending period:** November 2017 – June 2018
- **Publishing period:** July 2006 – June 2018

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and aggregation |
| SQLite | Database storage and SQL analysis |
| VADER | Video-title sentiment analysis |
| Tableau | Interactive visualization and dashboard |

## Analysis Performed

### 1. Category Analysis

Analyzed video volume and average performance across YouTube category IDs using:

- Video count
- Average views
- Average likes
- Average comments

### 2. Country Analysis

Compared publishing countries based on:

- Number of videos
- Average views
- Average likes
- Average comments
- Average trending duration

### 3. Title Sentiment Analysis

Video titles were classified into:

- **Neutral**
- **Positive**
- **Negative**

The overall sentiment distribution was:

| Sentiment | Percentage |
|---|---:|
| Neutral | 63.24% |
| Positive | 20.06% |
| Negative | 16.70% |

### 4. Sentiment vs Performance

Average views observed in the analysis:

| Sentiment | Average Views |
|---|---:|
| Negative | ~3.59M |
| Positive | ~2.45M |
| Neutral | ~2.10M |

These results represent associations in the analyzed dataset and do not establish causation.

### 5. Trending Duration

Average trending duration by publishing country:

| Country | Average Trending Days |
|---|---:|
| GB | ~10.95 |
| US | ~7.91 |
| CANADA | ~1.53 |
| FRANCE | ~1.38 |

## Tableau Dashboard

The final Tableau dashboard includes visualizations such as:

- **Videos by Category**
- **Average Views by Country**
- **Videos by Publishing Country**
- **Title Sentiment Distribution**
- **Average Views by Title Sentiment**
- **Average Trending Duration by Country**

Interactive filters can be used to explore the dataset by:

- Publishing country
- Category
- Title sentiment

## Project Structure

```text
youtube-trending-analysis-dashboard/
│
├── data/
│   └── youtube.csv
│
├── notebooks/
│   └── youtube_analysis.ipynb
│
├── tableau/
│   └── youtube_trending_dashboard.twbx
│
├── database/
│   └── youtube_analysis.db
│
├── report/
│   └── YouTube_Trending_Analysis_Project_Report.pdf
│
└── README.md
```

> File and folder names can be adjusted to match the final repository structure.

## Key Insights

- Neutral titles represent the largest share of the analyzed videos.
- Average views vary substantially across title-sentiment groups.
- Publishing countries differ considerably in both video volume and average views.
- GB and US showed higher average views in the country-level analysis.
- Trending duration also varied considerably across countries.
- Combining Python analysis with Tableau provides both detailed analysis and an interactive way to communicate findings.

## Future Scope

- Add time-series analysis of trending behavior.
- Replace category IDs with readable category names.
- Build predictive models for views or trending duration.
- Add channel-level performance analysis.
- Add engagement-rate analysis.
- Expand Tableau drill-downs and interactive tooltips.

## Project Report

A two-page project report is included with the repository covering the methodology, technologies, findings, dashboard, conclusion, and future scope.

## Author

**Geetesh Ramsri**

---

### Project Focus

**Data Analysis | Exploratory Data Analysis | Sentiment Analysis | SQL/SQLite | Tableau | Data Visualization**
