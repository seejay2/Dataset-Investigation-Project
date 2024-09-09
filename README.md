# Investigate a Dataset: TMDb Movies Dataset

## Dataset Description
This project investigates the TMDb Movies dataset, which contains metadata on approximately 5,000 movies from The Movie Database (TMDb). The dataset offers a variety of information about each movie, such as genres, release date, runtime, budget, popularity, revenue, and more. This rich data provides numerous opportunities for analysis and insights into the film industry.

## Questions for Analysis
* What movies had the most and least profit?
* What is the median runtime of all movies?
* How does the movie runtime relate to its revenue?
  
## Exploratory Data Analysis
The exploratory data analysis (EDA) involved visualizing and analyzing the data to answer the research questions:

1. **Movies with the Most and Least Profit**

By calculating the profit for each movie (Revenue - Budget), it was determined that Avatar had the highest profit, while The Lone Ranger had the lowest profit in the dataset.
The results highlight how certain movies can outperform others based on a variety of factors such as popularity, genre, and production companies. Further analysis could explore what factors led to these movies earning what they did.
2. **Median Runtime of All Movies**

After removing outliers, the median runtime of the movies was found to be 106 minutes. This metric provides a useful baseline for understanding typical movie lengths.

3. **Relationship Between Movie Runtime and Revenue**

An analysis of how runtime relates to movie revenue showed no strong correlation between the two variables. While longer movies tended to earn slightly less on average, this trend was not conclusive. More data and additional variables, such as genre or production quality, could provide deeper insights.

## Conclusions

*  Highest and Lowest Earning Movies: Avatar was identified as the highest-earning movie, while The Lone Ranger had the lowest earnings in the dataset. Further analysis could delve into the factors that contribute to such disparities in earnings.
*  Median Runtime: The median runtime of movies was found to be 106 minutes. Understanding runtime patterns could inform future analyses, such as investigating genre-specific runtime preferences.
*  Runtime vs. Revenue Relationship: While no definitive relationship between runtime and revenue was found, the trend suggested that longer movies may not necessarily lead to higher earnings. This could be an area for future exploration, especially when combined with additional factors like popularity, production companies, or genres.

## Future Work

* Investigating Additional Factors: Explore how other variables, such as genre, popularity, and production company, impact movie profitability.
* More Comprehensive Analysis: Analyze trends over multiple years or compare the success of movies from different regions.
* Feature Engineering: Create new features, such as profit margins, to provide more nuanced insights into movie performance.
