# Investigating Netflix Movies
*This is my solution to project from DataCamp.* 

![Popcorn image](https://github.com/jwiekiera/DataCamp/blob/main/Projects/NetflixMovies/redpopcorn.jpg)

Your friend suspects that movies are getting shorter and they've found some initial evidence of this. Having peaked your interest, you will perform exploratory data analysis on the `netflix_data.csv` data to understand what may be contributing to movies getting shorter over time. Your analysis will follow these steps:

* Load the CSV file and store as `netflix_df`.
* Filter the data to remove TV shows and store as `netflix_subset`.
* Investigate and subset the Netflix movie data, keeping only the columns `"title"`, `"country"`, `"genre"`, `"release_year"`, `"duration"`, and saving this into a new DataFrame called `netflix_movies`.
* Filter `netflix_movies` to find the movies that are strictly shorter than 60 minutes, saving the resulting DataFrame as `short_movies`; inspect the result to find possible contributing factors.
* Using a for loop and if/elif statements, iterate through the rows of `netflix_movies` and assign colors of your choice to four genre groups ("Children", "Documentaries", "Stand-Up", and "Other" for everything else). Save the results in a `colors` list. Initialize a matplotlib figure object called `fig` and create a scatter plot for movie duration by release year using the colors list to color the points and using the labels `"Release year"` for the x-axis, `"Duration (min)"` for the y-axis, and the title `"Movie Duration by Year of Release"`.
* After inspecting the plot, answer the question "Are we certain that movies are getting shorter?" by assigning either `"yes"` or `"no"` to the variable answer.
* Click the "Submit Project" button to check your solution.
