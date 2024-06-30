# IMDb Top 250 Movies Scraper

This project scrapes the top 250 movies from IMDb using BeautifulSoup and Pandas, and saves the data into a CSV file. The scraper reads HTML files from a directory, extracts movie details such as title, year, and rating, and creates a DataFrame to export as a CSV.


## Project Details

This script does the following:
1. Reads HTML files from the `data` directory.
2. Uses BeautifulSoup to parse the HTML content.
3. Extracts movie details such as title, year, and rating.
4. Cleans the extracted text to handle encoding issues.
5. Saves the extracted data into a CSV file using Pandas.
