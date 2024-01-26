# SQL-Power-BI-Google-Play-Store-analysis-End-to-End-Portfolio-Project
## Introduction
### Business Problem Statement:
The goal of this project is to analyze the Google Play Store Apps dataset to derive insights into the app market. We aim to understand the factors that contribute to an app's success, including user ratings, reviews, and category. Exploring user sentiments towards apps through the analysis of user reviews dataset will provide insights into the popularity of app categories based on total installs and the sentiment polarity of user reviews. The ultimate objective is to offer recommendations for app developers to enhance their app's performance and user satisfaction.

### Overview of Dataset:
* Total unique apps and categories in the dataset.
### Explore App Categories and Counts
* Retrieve the unique app categories and the count of apps in each category.
### Top-rated Free Apps
* Identify the top-rated free apps.
### Most Reviewed Apps
* Find the apps with the highest number of reviews.
### Average Rating by Category
* Calculate the average rating for each app category.
### Top Categories by Number of Installs
* Identify the app categories with the highest total number of installs.
### Average Sentiment Polarity by App Category
* Analyze the average sentiment polarity of user reviews for each app category.
### Sentiment Reviews by App Category
* Provide the distribution of sentiments across different app categories.
### Column Names and Descriptions
## googleplaystore Dataset
* **App:** Application name
* **Category:** The category the app belongs to
* **Rating:** Overall user rating of the app (as when scraped)
* **Reviews:** Number of user reviews for the app (as when scraped)
* **Size:** Size of the app (as when scraped)
* **Installs:** Number of user downloads/installs for the app (as when scraped)
* **Type:** Paid or Free
* **Price:** Price of the app (as when scraped)
* **Content Rating:** The age group the app is targeted at - Children / Mature 21+ / Adult
* **Genres:** An app can belong to multiple genres
* **Last Updated:** Date when the app was last updated on Play Store (as when scraped)
* **Current Ver:** Current version of the app available on Play Store (as when scraped)
* **Android Ver:** Min required Android version (as when scraped)
### googleplaystore_user_reviews Dataset
* **App:** Application name
* **Sentiment:** Sentiment of the review
* **Sentiment Polarity:** Polarity of the sentiment
* **Sentiment Subjectivity:** Subjectivity of the sentiment
* **Translated Review:** Translated review text

## Tools Used in Project
* **SQL** for analyzing the business problem statement.
* **Power BI** for visualization of business problems.
* **MS Word** for documentation.

## Key Insights
* These insights are based on a total of 8K apps in the Google Play Store:
* Family and Games are the top categories with the most apps.
* Personalization and Games are the top two categories with the highest ratings.
* Games and Communication emerge as the two leading categories with the highest number of installations.
## Thank You Note
Thank you for reading! For more interesting insights, check the SQL and Power BI files. Feel free to explore and analyze the data further.
