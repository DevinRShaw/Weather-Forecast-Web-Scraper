# Weather Forecast Web Scraper

This script is a simple weather forecast web scraper that retrieves weather data from the National Weather Service website using Python and the BeautifulSoup library.

## Requirements
- `bs4` (BeautifulSoup)
- `requests`
- `pandas`

## Usage
The script does the following steps:
1. Sends a GET request to the National Weather Service website to retrieve the HTML page.
2. Parses the HTML page using the BeautifulSoup library.
3. Finds the relevant tags in the HTML page that contain the weather information and extracts the data.
4. Stores the extracted data in a Pandas DataFrame for analysis.

## Results
The script returns the mean temperature from the extracted weather data.
