# Social Media Engagement Analysis Dashboard

This Power BI project presents an interactive dashboard for analyzing engagement trends across various social media platforms.

## Key Features
- Dynamic filters for platform, post type, sentiment, and post day
- KPI cards for:
  - Average Engagement per Post
  - Positive Sentiment Rate
  - Top Performing Platform
- Line chart visualizing average sentiment score over time
- Bookmark toggles to switch between high and low engagement posts
- Clean layout using a neutral color palette for a professional presentation

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
