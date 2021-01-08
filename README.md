# Microsoft Box Office Insights

**Author:** Jeffrey Hanif Watson
***

## Overview

This project provides a broad overview of the contemporary film industry as well as recommendations with regards to the probable initial capital requirements and film genres that will offer a high probability to maximize profit and return on investment. Descriptive analysis was performed on data obtained from the [The Numbers](https://www.the-numbers.com/), [Rotten Tomatoes](https://www.rottentomatoes.com/), and the [IMDb](https://www.imdb.com/) to arrive at the following conclusions: 

- The estimated cost for production and marketing in the first year: 3,881,250,000 USD.
- The bulk of film revenue will come from the international market.
- The Big Five genres of Action, SciFi, Drama, Family, and Comedy offer the best chances to maximize  profits.
- The Hidden Value genres of Comedy, Horror, Mystery, and Drama have the highest probability for optimal return on investment.


## Business Problem

According to data from [The Numbers](https://www.the-numbers.com/), the US box office has increased  from 5.3 billion USD in 1995 to 11.3 billion USD in  2019. Identifying opportunities with the highest probability for profit and ROI in this steadily growing market is the strategic priority. Variables highlighted for analysis include production cost, gross profit, net profit, return on investment, and the ratio of domestic to foreign box office receipts.


## Data

Data aggregated from [Rotten Tomatoes](https://www.rottentomatoes.com/) provided a solid foundation to analyze overall box office trends, genre trends, and individual films. [IMDb](https://www.imdb.com/) data was better formatted to research actors, directors, writers, and producers. Numerical data from [The Numbers](https://www.the-numbers.com/) was joined with the datasets above to create a data frame of 4,776 films and a complimentary data frame of 32,088 individuals. 

## Methods

SQLite, Python, Pandas, and Seaborn were used for data preparation, analysis and visualization.

## Results



Here is an example of how to embed images from your sub-folder:

### Distribution of the Top 100 Grossing Films
![graph1](./images/1_100_grossing_films.png)

### Mean Budget For a Top 100 Grossing Film
![graph2](./images/2_average_budgets.png)

### Statistics for the Top 100 Grossing Films
![graph3](./images/3_100_gross_stats_slim.png)

### Mean Share of Gross From Outside US
![graph4](./images/5_percent_international.png)

### The Big Five Genres
![graph5](./images/6_100_genre_counts.png)

### Hidden Value Genres
![graph6](./images/8_roi_genres.png)

### Hidden Value Genres
![graph6](./images/18_comedy_stats.png)

## Conclusions

**Recap:**
- Estimated initial cost: 3,881,250,000 USD.
- Most revenue will come from the international market.
- The Big Five genres increase the chance of maximum gross profits.
- Hidden Value genres have a increase probability of a high ROI.
**Next Steps:**
- Analysis of creative talent was performed and is available upon request.
- Incorporate the streaming market into the analysis.
-Research purchase of a production company rather than starting from scratch.


## For More Information

Please review our full analysis in [our Jupyter Notebook](MS_Box_Office_Insights.ipynb) or our [presentation](./presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── MS_Box_Office_Insights.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
