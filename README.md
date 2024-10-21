# Play Store Apps Data Analysis

**Overview**

This project explores the data from the Play Store, aiming to uncover factors contributing to the success and engagement of Android applications. The analysis utilizes two datasets:

Play Store apps dataset containing features like category, rating, size, installs, etc.

User reviews dataset, which includes customer reviews with sentiment analysis.

The objective is to understand the factors that drive app success and engagement to assist developers in making informed decisions.

**Objective**

Discover key factors influencing app success and engagement.

Determine the prominence of each factor in driving app success.

Identify correlations between user reviews, app ratings, installs, and other variables.

Provide actionable insights for app developers to capture the Android market effectively.

**Datasets**

The project uses two datasets:

Play Store Apps Data:

Number of rows: 10,841

Number of columns: 13

Columns include: App, Category, Rating, Size, Installs, Type, Price, etc.

User Reviews Data:

Number of rows: 64,295

Number of columns: 5

Columns include: App, Translated_Review, Sentiment, Sentiment_Polarity, Sentiment_Subjectivity

Data Cleaning and Preprocessing

Removed duplicate and irrelevant records.

Handled missing values in columns like Rating, Type, Genres, and Reviews.

Cleaned and converted fields like Size, Installs, and Price to numerical formats.

Addressed inconsistencies in categories and other app attributes.

**Key Insights from Analysis**

Category-wise Distribution:

Most apps belong to the Family, Game, and Tools categories.

Games and Communication apps have the highest number of installs.

App Types:

Majority of apps are free (around 92%).

Paid apps are more prevalent in categories like Family, Medical, and Tools.

Impact of Reviews on Installs:

Strong correlation between the number of reviews and installs, indicating that user feedback significantly impacts app downloads.

App Size:

Apps in the size range of 0-20MB are the most common.

Size does not have a significant impact on the number of installs.

User Sentiments:

Most apps receive positive reviews, particularly in categories like Games and Communication.

Negative reviews tend to mention issues with app updates, performance, and ads.

App Updates:

Apps that are frequently updated tend to have more installs, as users prefer the latest versions with fewer bugs.

**Visualizations**

Several graphs and charts were created to support the analysis:

Bar plots for category-wise distribution of apps and installs.

Pie charts for type distribution (free vs paid).

Scatter plots to visualize the relationship between ratings, reviews, installs, and app size.

Sentiment analysis using word clouds for positive, negative, and neutral reviews.

**Conclusion**

Factors contributing to app success: App size, reviews, category, last update, and whether the app is free or paid.

**Key findings:**

Free apps dominate the Play Store.

Games, Communication, and Tools apps attract the most users.

Apps with higher ratings and frequent updates are more successful in driving installs.

**Technologies Used**

Python: Data analysis and visualization

Libraries: Pandas, NumPy, Matplotlib, Seaborn, WordCloud

Tools: Google Colab for development and analysis
