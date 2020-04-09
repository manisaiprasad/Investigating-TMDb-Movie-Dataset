# Investigating-TMDb-Movie-Dataset
Analyzing a dataset and then communicate findings about it. using the Python libraries NumPy, pandas, and Matplotlib to make your analysis easier

Conclusions Found after Investigating-TMDb-Movie-Dataset

Q1 "Which genres are most popular from year to year?"

As shown surprising results, as the most popular genre differed a lot. To the authors surprise, only in 11 occasions best genre by the users was also voted asthe most frequent produced genres. In all remaining 40 occasions the two values differed.

Q2 "What kinds of properties are associated with movies that have high revenues?"

shows interesting result. The numeric columns of "popularity, budget and vote_count" show the highest correlations. One can argue that movies with higher budgets are able to receive higher revenues, nevertheless, the correlation is not on a very high level. Vote_count is indicating that the more people vote for a movie, the higher the revenue is. Most probably, this is not a good indicator for high revenue movies. High revenue movies indicate that they are most commonly directed by Matt Damon, cast Tom Cruise as actor and contain the genre Action.

Q3 "Did movies with higher vote count received a better rating?"

does not indicate that movies with a higher vote_count receive a higher vote_average. Also by considering columns with more than 2000 vote_count does not change the impression. Furthermore, the corralation does not indicate that higher vote counts result in higher vote averages.

Q4 "What were the most popular produced genres in 2000 compared to 2015?"

indicate that in the year 2015 dramas were by far the most frequent produced movies, followed by thrillers and action. In 2000 the most frequent produced genre was thriller, followed by action and comedies. The bar chart indicates that in 2015 much more movies were produced compared to the year 2000.

Q5 "How did the amount of produced films changed over time?"

reveals that the amount of produced films significantly increased from 1960 to 2015. Up to 1983 not more than 100 movies were prodcued per year, while in 2014 700 movies were produced. A strong increase in movie production can be obsorved between 1997-2009. One has to consider that the line chart does not show accurate results, as many rows from the original dataset were dropped.
