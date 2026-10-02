# Google Play Store Apps – Exploratory Data Analysis

## Overview
This project explores the Google Play Store dataset to understand app ratings, installations, pricing, reviews, categories, and update trends. The analysis uses Python to identify patterns in app performance and user engagement.

## Requirements
- Python 3.x
- Jupyter Notebook

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preparation
- Removed duplicate app records and invalid entries.
- Converted installs, reviews, price, and app size into appropriate numeric formats.
- Standardized category, genre, and content rating values.
- Handled missing values and validated rating ranges.
- Converted the last updated column into a date format.

## Analysis
The analysis focused on:
- Average app ratings and category distribution.
- Free vs. paid applications.
- Most installed and most reviewed apps.
- Ratings across categories and genres.
- Relationship between app size, price, reviews, and ratings.
- Content ratings and app types.
- Monthly app update trends.

## Key Insights
- The dataset contains **9,658 apps** across **33 categories**.
- The average app rating is approximately **4.17**.
- Free apps account for the majority of applications.
- Games and Communication have the highest total installations.
- Events and Education are among the highest-rated categories.
- Reviews and installations show a positive correlation of approximately **0.63**.

## Challenges
- Handling inconsistent formats in installs, price, and size.
- Managing missing values and duplicate app records.
- Cleaning invalid entries while preserving useful data.
- Comparing ratings across categories with different numbers of apps.

## Recommendations
- Developers should consider user feedback and review patterns when improving apps.
- App performance should be evaluated using installations, ratings, and reviews together.
- Regular updates and attention to user experience can help maintain app quality.
- Category-level analysis can help identify areas of user interest.

## Conclusion
This project demonstrates how exploratory data analysis can turn raw app-store data into meaningful insights. It helped identify patterns in app popularity, ratings, and user engagement while strengthening practical skills in Python-based data cleaning and visualization.
