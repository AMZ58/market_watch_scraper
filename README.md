# market_watch_scraper

This webscraper crawls marketwatch.com by ticker and iterates over the financial statements. It then downloads the statements and relevant data and organizes the data under new directorys by the industry you selected to analyze. The finincial statements are of a 5 year history. Other relevant data downloaded are financial ratios, margin percentages, current price/volume, and a list of the company's top executives and their biography.  All tickers fed into the webscraper are selected by the highest market cap of their industry. 

For this code to work for you, you will need to edit the path to where you wish to store the data and read the ticker list from. It is currently configured to paths on my OS. If your connection to the remote host drops out just restart the script. In the future I will implement an error handling that retries the connection. For now just restart the script and it will pick up where it left off.
