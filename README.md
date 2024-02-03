# World Population Data Scraper

## Overview
This Python script extracts data about the population and land area of countries from the Worldometer website and saves it into an Excel file. It utilizes the requests library to fetch the web page and BeautifulSoup for HTML parsing. The extracted data is then structured into a Pandas DataFrame and saved as an Excel file.

## Dependencies

- Python 3.x
- 'requests' library
- 'BeautifulSoup' library
- 'pandas' library

## Output

The script generates an Excel file ('countries_data.xlsx') with the following columns:

- 'Country': The name of the country.
- 'Population 2023': The estimated population of the country in the year 2023.
- 'Land Area': The land area of the country.