# An Analysis of Content Performance and Strategy at Netflix

### Project Overview
From this project, I gained valuable insights into the global landscape of Netflix content. I analyzed the distribution of content across different countries, identifying the most common types and genres specific to each region. I also explored trends in content production over the years, highlighting countries that produce the most content for Netflix. This analysis provided a deeper understanding of how Netflix tailors its offerings based on regional preferences and the evolving nature of content production over time.

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





