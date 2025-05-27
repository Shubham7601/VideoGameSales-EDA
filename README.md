# VideoGameSales-EDA

Here's a quick overview of what I worked on:

🔍 Exploratory Data Analysis (EDA)

Cleaned the dataset by handling missing values — replaced nulls using mean (for numerical) and mode (for categorical).

Visualized total global sales and number of games per genre using bar plots.

Compared sales trends across North America, Europe, and Japan using line plots for deeper regional insights.

Identified the Top 10 globally selling video games for a quick performance benchmark.

Created a heatmap to analyze the relationship between top publishers and game genres.

📊 Data Visualization Highlights

Used pie charts to showcase the regional distribution of global sales — providing a clear view of market share.

Emphasized actionable insights with clean, interactive visuals.

🤖 Machine Learning & Prediction

Trained a Random Forest Regressor and a Linear Regression model to predict global sales.

Evaluated both models using Root Mean Squared Error (RMSE) and R² score to measure performance.

Compared actual vs predicted sales to assess model accuracy.

Key Insights:

1. Platform: Some platforms (like PlayStation or Xbox) have significantly higher global sales compared to others.

2. Genre: Certain genres (such as Action or Sports) have higher sales than others like Puzzle or Adventure.

1. Publisher: Some publishers (like EA or Activision) have games with significantly higher sales compared to others. Large publishers have larger budgets for marketing and game development, allowing them to create more widely recognized games, which leads to higher sales.

2. Year of Release: Sales of video games show fluctuations based on the year they were released.

3. Global Sales: There is a clear correlation between global sales and features like genre and platform. Games on popular platforms and in widely loved genres tend to perform better globally.

Suggestions:

1. Since certain platforms (like PlayStation or Xbox) tend to have higher global sales, game publishers can create platform-specific marketing campaigns to capitalize on their popularity.

2. Publishers should focus on developing more games within popular genres such as Action, Sports, or Shooter, which tend to have higher sales.

3. Smaller developers or publishers could consider partnerships with larger publishers like EA or Activision to leverage their marketing.

4. Game developers should plan releases strategically, especially around the time new consoles are launched, as these periods tend to show higher sales for games.

Conclusion:

Through this analysis, I identified that Linear Regression With 99% Accuracy also as Gradient Boosting With 99% Accuracy is an effective model for predicting global sales based on the dataset's features. Key factors such as Platform, Genre, and Publisher.
