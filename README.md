# Real Estate Web Scraping Bot
This bot scrapes available property listing data from real estate website zillow.com in user provided city and saves in an excel file. It performs following:
- Asks for a city name in user input dialog.
- Opens website zillow.com in a browser.
- Types location, applys filters and click done button.
- Extracts listing data by using data scraping and saves the information in data table variable.
- Loops through the data for each row in data table.
- Gets all required data and adds it in another data table.
- Sorts data and writes it into the output excel file.