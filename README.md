# EDA_With_Google_Playstore

Problem Statement
With over 2.56 million apps available on the Google Play Store, this project aimed to explore and understand app distribution and user trends. The objectives included:
Identifying the most popular app categories,
Finding the app with the largest number of installs,
Analyzing the app with the largest size,
Uncovering other patterns that affect app popularity and visibility.

Dataset Overview
Rows: 10,841
Columns: 20
The dataset includes attributes like App, Category, Rating, Reviews, Size, Installs, Price, Type, Content Rating, Genres, Last Updated, etc.

EDA Workflow: 
1)Data Cleaning
  (a) Handled missing values.
  (b) Removed duplicate records.
  (c) Processed inconsistent entries in fields like Size, Price, and Installs.
2)Feature Engineering
  (a) Converted textual data into usable numeric formats.
  (b) Parsed and transformed Size, Installs, and Price into appropriate types.
  (c) Created new features where needed for better analysis.
3)Exploratory Data Analysis
  (a) Distribution Analysis: Found skewed distributions: Ratings and Year were left-skewed, while Reviews, Size, Installs, and Price were right-skewed.
  (b) Category-wise Exploration: Identified that Family, Games, and Tools were the most populated app categories, Beauty, Comics, and Art apps were among the least present.
  (c) Top Performing Apps: Detected apps with the highest installs and largest sizes, Compared app ratings by category and type (Free vs Paid).
  (d) Content Rating Trends: Analyzed which content ratings (Everyone, Teen, etc.) had the most installs.
  (e) Correlation Analysis: Explored the relationship between price, installs, size, and rating.

Key Observations:
  (a) Family category alone accounts for 18% of all apps, followed by Games at 11%.
  (b) Free apps dominate the store but paid apps tend to have higher ratings.
  (c) There is a positive correlation between number of reviews and installs.
  (d) Some apps have a surprisingly high install count despite lower ratings.
