IMDb Movie Sentiment Analysis

This project analyzes audience opinions from IMDb reviews and summarizes them at the movie level. Using NLP tools like TextBlob, each review is scored for sentiment (positive, neutral, or negative), then aggregated by movie title to reveal which films are most loved or criticized.

Project Overview
Dataset: IMDb Dataset (50,000 reviews)
Tools: Python, Pandas, TextBlob, Matplotlib
Goal: Identify overall audience sentiment for each movie

Steps
Clean and preprocess review text (remove HTML, punctuation, lowercase).
Compute sentiment polarity using TextBlob and a lexicon fallback.
Assign 15 well-known movie titles (e.g., Inception, Joker, Titanic).
Aggregate reviews by movie to calculate average sentiment.
Visualize results using bar and pie charts.

Visuals Included
Top 10 Positive Movies
Top 10 Negative Movies
Overall Sentiment Distribution
Review Count Share per Movie

Insights
Emotionally rich or inspiring language yields higher scores.
Larger review counts tend to moderate sentiment extremes.

Outputs
Movie_Sentiment_Detailed_Report_With_Charts.docx — Full report with visuals
.png charts — Bar and pie visualizations

.csv file — Movie-level sentiment summary

✅ Conclusion

This analysis demonstrates how individual text reviews can be aggregated to reveal broader audience trends. Future enhancements can use advanced NLP models like BERT for deeper contextual understanding.
