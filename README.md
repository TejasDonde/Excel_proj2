**Excel: Netflix Movies And TV Shows Dataset**

This dataset contains metadata for thousands of Netflix shows and movies, including title, type, cast, genres, release year, duration, ratings and country of origin.

Dataset Overview
●       Rows: 8808
●       Columns: 12
●       Column Description
○       show_id: Unique ID for every movie or tv show.
○       type: Identifier for movie or tv show.
○       title: Title of the movie or tv show.
○       director: Director of the movie or tv show.
○       cast: Actors involved in the movie or tv show.
○       country: Country where the movie or tv show was produced.
○       date_added: Date it was added on Netflix.
○       release_year: Actual release year of the movie or tv show.
○       rating: Rating of the movie or tv show.
○       duration: Total duration in minutes or number of seasons.
○       listed_in: Genre the movie or tv show was listed in.
○       description: A summary description of the movie or tv show.

**Actions**
●       Data Cleaning And Preprocessing
○       Parse and standardize date format in date_added.
○       Split listed_in into multiple genres.
○       Use PROPER() and TRIM() to clean the director, cast and genres fields.
○       Handle missing values in cast and director fields.

●       Data Analysis And Calculations
○       Count the number of movies versus tv shows per year.
○       Identify the most common genre for each country.
○       Find top 10 most frequent directors.
○       Average duration by content type.
○       Count how many shows were added per month.

●       Advanced Excel Concepts
○       Create a dropdown to filter by country and list all shows from there.
○       Use VLOOKUP() to fetch director name by title.
○       Pivot Table: Number of releases per rating.
○       Conditional Formatting: Highlight entries from before 2010.

●       Visualization And Dashboard
○       Bar Chart: Shows per year.
○       Pie Chart: Movie versus tv distribution.
○       Line Chart: Release trend over time.
○       Slicer: Filter by genre, year and country.

