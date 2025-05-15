Netflix Data Visualization
This repository contains a Jupyter notebook that performs exploratory data analysis and visualization on a dataset of Netflix titles.

Project Description
The project analyzes the content available on Netflix, specifically focusing on the distribution of movies and TV shows, content ratings, and content release over the years. The analysis is performed using Python with the pandas library for data manipulation and matplotlib for creating visualizations.

Technologies Used
Python
pandas
matplotlib
Jupyter Notebook

Data Source
The analysis is based on the netflix_titles.csv dataset, which contains information about movies and TV shows available on Netflix.

Analysis Performed
Data Loading and Cleaning: The notebook loads the netflix_titles.csv file into a pandas DataFrame. Rows with missing values in key columns (type, release_year, rating, country, duration) are removed to ensure data quality.
Movie vs. TV Show Comparison: The distribution of content types (movies and TV shows) in the dataset is analyzed.
Content Rating Analysis: The counts of different content ratings are calculated to understand the distribution of ratings among Netflix titles.
Content Release Over Time: The trend of movie and TV show releases over the years is analyzed to visualize the growth of content on Netflix.
Visualizations

The notebook generates the following visualizations:
Number of Movies VS TV shows on Netflix: A bar plot comparing the counts of movies and TV shows.
Distribution of content ratings: A visualization showing the frequency of each content rating.
Comparison of Movies and TV Shows Released Over Year: A plot illustrating the number of movies and TV shows released each year.

How to Run
Clone this repository to your local machine.
Make sure you have Python, pandas, and matplotlib installed.
Download the netflix_titles.csv dataset.
Open the netflix_data_visualization.ipynb notebook in a Jupyter environment (like Jupyter Notebook or JupyterLab).
Update the path to the netflix_titles.csv file in the notebook if necessary.
Run the cells in the notebook to execute the analysis and generate the visualizations.
The generated plots will be saved as movies_vs_tvshows.png and movies_tv_shows_comparison.png in the same directory as the notebook.

