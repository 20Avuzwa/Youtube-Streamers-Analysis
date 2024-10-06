# YouTube Streamer Analysis

## Overview

This project performs a comprehensive analysis of the **Top 1000 YouTubers** dataset, which contains valuable information about YouTube streamers, including their ranking, categories, subscribers, country, visits, likes, comments, and more. The goal of this analysis is to extract meaningful insights about top-performing content creators, audience preferences, and performance trends.

### Key Features:
- Analysis of performance metrics (subscribers, visits, likes, comments).
- Identification of trends in categories and popularity.
- Outlier detection and handling for more accurate analysis.
- Audience distribution study by country and content category.
- Benchmarking top-performing streamers with above-average metrics.

## Dataset
The dataset includes information about the top 1000 YouTubers, including:
- **Rank**
- **Streamer Name**
- **Subscribers**
- **Visits**
- **Likes**
- **Comments**
- **Country**
- **Content Category**

## Insights

### 1. **Trend Analysis**:
- **Popular Categories**: Categories like gaming, vlogging, and entertainment are among the most popular. These categories have the highest number of streamers, indicating a strong user base and viewership.
- **Correlation Analysis**: There is a noticeable correlation between the number of subscribers and the number of likes, showing that as a streamer's subscriber base grows, engagement in terms of likes also increases. However, the correlation between subscribers and comments is weaker, indicating varying audience engagement levels for commenting.

### 2. **Audience Study**:
- **Regional Preferences**: Certain content categories are more prevalent in specific regions. For example, gaming streamers dominate in North America and Europe, while entertainment categories show strong popularity in Asia.
  
### 3. **Performance Metrics**:
- **Top Streamers**: The streamers with the highest subscribers also tend to have higher visits and engagement metrics. However, there are some exceptions, where niche streamers with fewer subscribers still manage to generate significant audience engagement.
- **Average Metrics**: The average number of subscribers across the dataset is **X million**, while the average number of likes per streamer is **Y million**.

### 4. **Benchmarking**:
- **Top Performers**: Streamers with above-average performance metrics were identified using benchmarks. These top creators outperform the average streamer in terms of engagement (likes and comments), visits, and subscriber count.
  
## Technologies Used
- **Python**: Core programming language for analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib** & **Seaborn**: For data visualization and trend analysis.
- **Scikit-learn**: For statistical analysis and outlier detection.
- **Jupyter Notebook**: Used for developing and documenting the analysis.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/youtube-streamer-analysis.git
