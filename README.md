# Imdb_webscrapping
 IMDB page titled "List of Movies and castings".
scrapping-imdb
IMDb Top 250 Movies Scrapping

Introduction
This project involves scraping the IMDb website to gather information about the top 250 movies. The script extracts relevant data such as the movie title, duration, IMDb score, and release year, and presents it in a structured format.

Features
Scrapes the IMDb Top 250 movies list. Extracts essential information including title, duration, score, and year. Saves the data in a structured format (e.g., CSV, JSON).

Data Structure
The scraped data includes the following fields:

Title: The title of the movie. Duration: The duration of the movie in minutes. Score: The IMDb score of the movie. Year: The release year of the movie.

#Dependencies This project requires the following Python libraries:

requests beautifulsoup4 pandas re selenium

Examples
Here's a brief example of what the output might look like in CSV format:

Title Duration Score Year The Shawshank Redemption 142 9.3 1994 The Godfather 175 9.2 1972 ... ... ... ...
