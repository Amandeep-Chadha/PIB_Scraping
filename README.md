# PIB_Scraping
WebScraper for downloading all articles from Press Information Bureau

## Working Procedure
The web scraper relies on Selenium and BeautifulSoup for accessing the website and reading data from it respectively. It select all articles from a month using the given drop down on the website and further scraps linkusing selenium. Which are parsed through beautifulsoup to extract the necessary information. This informtion is then added to a DataFrame and shiften to a csv at the end.

## Functions
It has two main functions. Website visiting and Data Extraction.

### 1. Main funciton
The main function consists of a for loop which iterates through a range of numbers to select the month for which we need to download all data. The program then selects the required month and date using Selenium. After selecting, the data extraction function is called which extracts necessary data in a DataFrame which is later appended in this funciton.

### 2. Data Extraction
This function involves using beautiful soup to scrape data of each article, ine at a time and calls formatting function to tailor the data accordinf to the requirement. The data collected is then appended to the dataframe passed as an argument.

Adding the CSV file of downloading First Three months articles of 2024.
