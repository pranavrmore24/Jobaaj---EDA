# Google Play Store App Analysis – EDA Project

## Overview

This project focuses on Exploratory Data Analysis (EDA) of the Google Play Store dataset to uncover trends and patterns related to app ratings, installs, reviews, categories, genres, app sizes, pricing models, and update frequency.

The analysis aims to understand factors that contribute to app success and provide actionable business insights for developers, marketers, and businesses. Various visualizations and statistical techniques were used to identify user behavior, category performance, and app popularity trends.

---

## Objective

The main objectives of this project are:

• Analyze the distribution of applications across categories and genres.

• Understand the relationship between app ratings, installs, reviews, and app types.

• Compare free and paid applications.

• Identify the most popular and highly-rated applications.

• Explore category-wise and genre-wise performance.

• Analyze content rating distributions.

• Examine app update trends over time.

• Generate business insights and recommendations for app developers and stakeholders.

---

## Tools Used

### Programming Language
• Python

### Libraries
• Pandas
• NumPy
• Matplotlib
• Seaborn

### Environment
• Jupyter Notebook

### Techniques
• Data Cleaning
• Exploratory Data Analysis (EDA)
• Data Visualization
• Statistical Analysis
• Feature Engineering
• Business Insight Generation

---

## Process

### 1. Data Collection & Understanding

• Loaded the Google Play Store dataset.

• Explored dataset structure, shape, and columns.

• Identified missing values and incorrect data types.

---

### 2. Data Cleaning

• Removed duplicate records.

• Handled missing values.

• Converted Installs column into numeric format.

• Converted Reviews column into numeric datatype.

• Standardized Size column by converting KB values into MB.

• Converted Last Updated column into datetime format.

• Cleaned Rating, Price, and other relevant columns.

• Removed invalid and inconsistent records.

---

### 3. Exploratory Data Analysis (EDA)

#### Basic Analysis

• Distribution of App Categories

• Rating Distribution

• App Size Distribution

• Free vs Paid Apps

• Content Rating Distribution

• Top Installed Apps

• Apps Rated Above 4.0

• Average Reviews by App Type

• Average App Size by Category

• Apps Updated by Year

---

#### Intermediate Analysis

• Top Categories by Average Rating

• Top Genres with High Installs

• Most Reviewed Apps

• Content Rating Distribution (Free vs Paid)

• Categories with Highest Installs

• Update Trends Over Time

---

#### Advanced Analysis

• Relationship Between Installs and Ratings

• Genre-wise Rating Analysis

• Install Range Binning Analysis

• Trend Analysis of App Updates

• High-Performing App Segment Identification

---

### 4. Visualization

The following visualization techniques were used:

• Bar Charts

• Histograms

• Count Plots

• Horizontal Bar Charts

• Line Charts

• Comparative Analysis Charts

---

### 5. Business Insight Generation

Generated business recommendations based on app performance, user engagement, ratings, installs, and category trends.

---

## Key Insights

### App Popularity

• Free applications dominate the Google Play Store ecosystem.

• More than 89% of applications are free.

• Popular applications typically have millions of installs and maintain strong ratings.

---

### User Ratings

• Apps with higher install counts generally achieve higher average ratings.

• Applications with over 1 million installs consistently maintain ratings above 4.2.

• User trust and app quality appear to contribute to higher ratings.

---

### Reviews & User Engagement

• Facebook, WhatsApp Messenger, Instagram, and Messenger receive the highest number of reviews.

• High review counts indicate strong user engagement and active user communities.

• Reviews play a significant role in app credibility and discoverability.

---

### Category Performance

• GAME category generated the highest total installs.

• COMMUNICATION category ranked second in overall installs.

• SOCIAL, PRODUCTIVITY, and TOOLS categories also attracted significant user traffic.

---

### Content Rating Analysis

• Most applications belong to the "Everyone" content rating category.

• Teen-rated applications represent the second-largest user segment.

• Adult-only content represents a very small portion of the marketplace.

---

### App Size Analysis

• Most applications are lightweight and fall within smaller size ranges.

• Larger applications are concentrated in gaming and multimedia categories.

• Smaller app sizes may improve accessibility and download rates.

---

### Update Trends

• The number of app updates increased significantly after 2015.

• 2018 recorded the highest number of updates.

• Developers increasingly prioritize frequent updates to remain competitive and improve user satisfaction.

---

### Genre Analysis

• Several niche genres achieved the highest average ratings.

• Highly-rated genres often have fewer applications but more focused user bases.

• Specialized genres can generate strong user satisfaction despite lower market share.

---

### Install vs Rating Relationship

• Average ratings generally improve as install counts increase.

• Apps in the 10M–100M install range achieved some of the highest average ratings.

• Strong ratings help attract new users and sustain long-term growth.

---

## Business Recommendations

• Focus development efforts on high-demand categories such as Games, Communication, and Social.

• Maintain ratings above 4.0 through continuous quality improvements.

• Encourage user reviews and feedback to improve engagement.

• Release regular updates to retain users and remain competitive.

• Optimize application size to support users with limited storage and slower internet connections.

• Analyze successful competitors within top-performing categories and genres.

---

## Conclusion

This project provides a comprehensive analysis of the Google Play Store ecosystem. The findings reveal that app success is strongly influenced by user ratings, installs, reviews, category selection, and update frequency. Free applications dominate the platform, while categories such as Games and Communication generate the highest user engagement.

Developers who focus on user satisfaction, maintain frequent updates, optimize app performance, and encourage user interaction are more likely to achieve long-term success in the competitive mobile application market.
