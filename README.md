# Instagram Reach Analysis & Engagement Forecasting

This project explores the mechanics of organic reach and engagement on Instagram using a dataset centered on content performance and hashtag strategy. Developed in Google Colab, it combines exploratory data analysis with Power BI to visualize the factors that drive impressions and profile growth.

## Project Overview

The objective is to understand how different traffic sources (Home, Hashtags, Explore, and Others) contribute to total impressions and how specific hashtags influence engagement rates. The project identifies patterns in user interaction—such as saves, shares, and follows—to help content creators optimize their reach.

## Key Features

- Traffic Source Attribution: Analysis of where impressions originate, comparing the effectiveness of the Instagram Feed (Home) versus discovery features (Explore/Hashtags).  
- Engagement Metrics: Deep dive into the relationship between likes, comments, shares, and saves to calculate a holistic engagement rate.  
- Hashtag Strategy: Evaluation of hashtag counts and specific tags to determine their impact on discoverability and profile visits.  
- Interactive Power BI Dashboard: A visual report featuring:
  - Performance summaries by content type or caption theme.  
  - Scatter plots correlating impressions with profile visits and follows.  
  - Funnel charts showing the conversion from Reach → Engagement → Follows.

## Tech Stack

- Environment: Google Colab  
- Language: Python (Pandas, Matplotlib, Seaborn)  
- Visualization: Power BI Desktop  
- Data fields: Impressions, From Home, From Hashtags, From Explore, Saves, Comments, Shares, Likes, Profile Visits, Follows, Hashtags

## File Structure

- Instagram_hashtag_analysis.ipynb – Google Colab notebook with code for data cleaning, distribution analysis, and correlation matrices.  
- instagram_cleaned_data.csv – Processed dataset with calculated fields for engagement rate and hashtag counts.  
- Instagram_hashtag_analysis_dashboard.pbix – Power BI file for dynamic exploration of reach metrics.

## Key Insights

- Discovery Analysis: Identification of which content types successfully “break out” into the Explore page versus those that mainly reach existing followers.  
- Conversion Rates: Measuring how efficiently Profile Visits lead to new Follows.  
- Save‑to‑Reach Ratio: Highlighting the importance of Saves as a high‑intent engagement metric that signals content value to the Instagram algorithm.

## How to Use

- Analyze: Open Instagram_hashtag_analysis.ipynb in Google Colab to view the data processing and statistical visualizations.  
- Interact: Open Instagram_hashtag_analysis_dashboard.pbix in Power BI Desktop to filter performance by specific hashtags or reach milestones.

This project demonstrates a specialized Data Analyst workflow: Social Media Analytics → Feature Engineering (Python) → Impact Visualization (Power BI).
