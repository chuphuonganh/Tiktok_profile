TikTok Engagement and Content Analysis
A data science project focused on analyzing and comparing TikTok accounts to understand engagement patterns, content strategies, and the impact of educational vs. entertainment content on the platform.

## Project Overview
This project analyzes the TikTok account "Dòng Máu Việt" (focused on Vietnamese history and patriotism) and compares it with "Công Ken" (focused on modern entertainment). The goal is to determine how different content styles influence user interaction and to explore if historical content can effectively "touch" the younger generation through social media.

### Key Research Questions:
How do video length and posting frequency affect engagement?

What are the distribution patterns of likes, shares, and comments?

Is there a significant difference in performance between historical/educational content and modern entertainment?

## Team Members (SG-AI Group)
Chu Thị Phương Anh - 23020324

Phạm Hà Anh - 23020330

Tô Tiến Đạt - 23020353

## Tech Stack
Language: Python

Libraries: * pandas & numpy: Data cleaning and manipulation.

matplotlib & seaborn: Statistical data visualization.

requests: Data fetching.

hashlib & ast: Data processing.

## Data Workflow
1. Data Cleaning
Handling missing values and duplicates.

Converting data types (e.g., timestamps, numerical strings).

Filtering outliers in video duration and engagement metrics.

2. Exploratory Data Analysis (EDA)
Engagement Distribution: Analyzing the skewness of likes and views.

Temporal Analysis: Identifying peak posting times and their correlation with viral success.

Comparative Analysis: Side-by-side comparison between "Dòng Máu Việt" and "Công Ken".

3. Key Findings
Content Length: "Công Ken" tends to produce longer, more consistent videos, while "Dòng Máu Việt" focuses on shorter bursts of content (mostly under 60s).

Engagement: Modern entertainment topics still generally achieve higher raw engagement numbers compared to historical topics.

Consistency: "Công Ken" shows higher consistency in video duration, whereas "Dòng Máu Việt" exhibits more variance.

## Main Results
The analysis suggests that while historical content ("Dòng Máu Việt") has a dedicated following, it requires specific optimization in video length and narrative structure to compete with entertainment-heavy channels.

"The challenge is to make history 'touch' the youth through optimized social media strategies."

## Limitations and Improvements
Data Privacy: Limited access to demographic data (age, gender, location) due to TikTok's security policies.

Scope: Future improvements involve implementing predictive models to forecast video performance based on metadata.
