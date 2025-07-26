# Social Media Engagement Analysis Dashboard

This Power BI project presents an interactive dashboard for analyzing engagement trends across various social media platforms.

**Average Sentiment Score**: Categorized as Positive, Negative, or Neutral based on textual sentiment analysis.
- **Engagement per Post**: Calculates total interactions (likes + comments + shares) per post.
- **Post Type Comparison**: Compares sentiment and engagement across post types such as image, video, and text.
- **Temporal Insights**: Visualizations showing sentiment and engagement trends by day of the week.
- **Smart KPIs**: Custom cards to highlight key metrics like:
  - % of Positive vs. Negative Sentiment
  - Average Engagement per Post
  - Most Engaging Post Type

## File Included
- `Social_Media.pbix` – Power BI Desktop file containing visuals, DAX measures, interactions, bookmarks, and page styling

## Dataset Overview
- Post-level data including:
  - Platform
  - Post Type
  - Sentiment (numeric encoding: –1, 0, +1)
  - Total Engagement (sum of likes, comments, and shares)
- Data is not time-series based; engagement is aggregated per post

## Tools & Techniques
- Power BI Desktop
- DAX for calculated KPIs and sentiment metrics
- Bookmarks and visual interactions for toggled views
- Custom formatting and styling for consistent design

## Objective
To build a clear and insightful dashboard that enables users to:
- Explore content performance by platform, sentiment, and post type
- Identify patterns in high vs. low engagement
- Make informed decisions based on content effectiveness

---

**Note**: This dashboard is intended for interactive exploration inside Power BI Desktop.
