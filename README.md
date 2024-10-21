# An Analysis of Content Performance and Strategy at Netflix

### Project Overview
From this project, I gained valuable insights into the global landscape of Netflix content. I analyzed the distribution of content across different countries, identifying the most common types and genres specific to each region. I also explored trends in content production over the years, highlighting countries that produce the most content for Netflix. This analysis provided a deeper understanding of how Netflix tailors its offerings based on regional preferences and the evolving nature of content production over time.

### Objective
The goal of this analysis is to explore Netflix's content library to identify trends in content production, genre preferences, and geographical distribution, with the aim of providing insights to enhance Netflix’s content strategy and audience engagement.

### Data Source
Kaggle [Download here](https://www.kaggle.com/datasets/shivamb/netflix-shows)

### Methodology
1. Data Loading: Imported the necessary libraries (e.g., pandas, matplotlib) and read the Netflix dataset into a pandas DataFrame for analysis.
2. Data Inspection: Reviewed the dataset's structure by checking formats, inspecting data types, and identifying key columns for analysis. Made appropriate data type conversions to ensure consistency, especially for date and categorical fields.
3. Data Cleaning:
- Identified missing values and handled them by filling with appropriate placeholder strings or removing unnecessary data.
- Cleaned columns like country and listed_in by splitting multiple values and standardizing entries.
- Created a new column, genre, by exploding the listed_in column, which contained multiple genres separated by commas. This allowed for more granular analysis of genres across different titles.
4. Data Analysis: Performed exploratory data analysis (EDA) through statistical analysis and visualizations. Focused on trends in content release over the years, the distribution of content by type and genre, and the top content-producing countries. Also analyzed regional content preferences to identify potential focus areas for Netflix.

### Tools Used
Python

### Libraries
- Numpy
- Pandas
- Matplotlib
- Seaborn

### Key insights
 - The analysis revealed that Netflix has consistently released more movies than TV shows over time. A significant spike in content production (both movies and TV shows) occurred between 2017 and 2019, with 2018 standing out as a peak year.
 - Across all countries, the most common genres include international movies, dramas, comedies, and action & adventure.
 - The top content-producing countries are the United States, India, and the United Kingdom, while South Korea and Japan focus more on TV shows compared to movies.
 - Content ratings analysis showed that TV-MA (Mature Audiences) and TV-14 are the most common ratings, with genres like international movies, thrillers, and dramas being highly rated under TV-MA.
 - Comparing production by country, the U.S. and India predominantly produce movies, while South Korea and Japan tend to produce more TV shows.
 - The analysis of genres that top countries should focus on suggests that genres like international movies and thrillers resonate well, particularly under mature content ratings like TV-MA.

### Project Link
Analysis [View the analysis on Jupyter Notebook](https://github.com/KENE508/Netflix-Content-Strategy-Project/blob/main/Netflix_Content_Strategy_Project.ipynb)

### Recommendations
#### 1. Focus on Popular Genres:
 - Netflix should prioritize producing content in genres that are widely appreciated, such as international movies, dramas, and comedies, as these genres consistently perform well across multiple regions.
#### 2. Leverage High-Rated Genres in Key Markets:
 - In countries like the United States, where movies dominate, Netflix should continue focusing on highly rated genres like documentaries and dramas, especially those rated TV-MA and TV-14.
 - Netflix could also experiment with creating TV shows within these genres, which could attract audiences and diversify its content portfolio, potentially driving long-term growth in TV show consumption.
#### 3. Expand TV Show Production in Countries Favoring TV Shows:
 - In regions like South Korea and Japan, where the audience preference leans heavily toward TV shows, Netflix should continue producing more TV series to meet local demand.
 - In Japan, where anime is a popular genre, Netflix could explore creating anime movies in addition to anime TV shows. This dual approach could increase engagement in both the TV and movie categories, maximizing content impact in this market.
#### 4. Tailor Regional Content Strategies:
 - By analyzing country-specific preferences, Netflix can adjust its content strategy in each market. For example, focusing on international movies in markets where global content resonates and aligning content ratings with the preferences of local audiences can help maintain viewer engagement.

### Suggestions
1. Data-Driven Localization: Netflix could consider localized content strategies that not only focus on genres but also incorporate regional cultural elements to further enhance viewer connection.
2. Experiment with Content Length: As part of the strategy, Netflix could experiment with varying content durations (e.g., shorter episodes or mini-series) to see if audience engagement improves, especially for TV shows in countries like South Korea and Japan.

### References
 - Geeks for geeks: what does it mean to split and explode string entries and how [link](https://www.geeksforgeeks.org/how-to-split-explode-pandas-dataframe-string-entry-to-separate-rows/)
 - Stack overflow: How to split and explode in pandas dataframe [link](https://stackoverflow.com/questions/12680754/split-explode-pandas-dataframe-string-entry-to-separate-rows)

### Acknowledgment
 -  I am deeply grateful to my data community friends for their invaluable ideas and insights. This project wouldn't have been possible without their support.







