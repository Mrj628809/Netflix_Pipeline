# Netflix Data Analysis Pipeline
## Overview
This data pipeline analyzes the Netflix dataset to identify the most popular genres for TV shows and movies. It utilizes Python libraries such as Pandas, Seaborn, and Matplotlib to load, clean, analyze, and visualize the data.

## Steps:
1. Load the Dataset: The Netflix dataset is loaded into a Pandas DataFrame. Unnecessary columns such as 'date_added', 'cast', 'director', 'duration', 'description', and 'listed_in' are dropped.

2. Handle Missing Values: Any missing values in the dataset are filled with "Unknown".

3. Preprocess Genre Information: The 'listed_in' column, containing genre information, is split into separate columns for each genre. The resulting DataFrame is concatenated with the original one.

4. Split Data into TV Shows and Movies: The dataset is divided into two separate DataFrames: one for TV shows and one for movies.

5. Analyze TV Shows and Movies: For both TV shows and movies, the pipeline calculates the frequency of each genre.

6. Visualize the Results: The top 10 most popular genres for TV shows and movies are visualized using Seaborn barplots.

## Libraries Used:
* Pandas: For data manipulation and analysis.
* Seaborn: For statistical data visualization.
* Matplotlib: For creating static, animated, and interactive visualizations in Python.
## Conclusion
This pipeline provides insights into the popularity of genres for TV shows and movies on Netflix. The visualizations generated help in understanding the distribution of genres and their popularity trends.
