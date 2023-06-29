# Python-Project on Web-Scrapping ICC Most Test Runs

This project aims to scrape data from the website "https://www.espncricinfo.com/records/most-runs-in-career-223646" and extract information about the most runs scored in cricket careers. The code retrieves the HTML content of the web page, parses it using BeautifulSoup, and then extracts data from the table on the page.

The extracted data includes various statistics related to the players' career runs, such as their names, playing spans, number of matches played, innings batted, number of not outs, total runs scored, highest innings scores, batting averages, balls faced, strike rates, number of centuries scored, number of half-centuries scored, number of ducks, number of fours, and number of sixes.

The code organizes the extracted data into separate lists for each statistic, and then creates a pandas DataFrame called Most_Runs using the Record_Runs dictionary. Finally, the DataFrame is saved as a CSV file named "Most_Runs_Records.csv" using the to_csv function, with the index parameter set to False to exclude the index column from the CSV file.

In summary, this project demonstrates web scraping using Python and BeautifulSoup to extract cricket career run statistics and stores them in a CSV file for further analysis or use.
