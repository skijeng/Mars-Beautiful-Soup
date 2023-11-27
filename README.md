# Mars-Beautiful-Soup

For the this project, the first, and most difficult aspect was aligning my chrome and cromedriver version and location. I found the best way to assure the correct path was to specify in the Browser argument. After this, I did the following:

This project involves scraping and analyzing data related to Mars.

Scrape Titles and Preview Text:

Automated browsing was used with splinter Browser to visit the Mars news site, and the HTML code was extracted with Beautiful Soup.

The information was then scraped and stored in a Python list, where each dictionary contained 'title' and 'preview'.

Then, Splinter Chrome Driver was used to visit the Mars Temperature data site.

The HTML table on the website was extracted using Beautiful Soup.
The data was then extracted into a pandas dataframe.

After this, the data was analyzed to answer the followuing questions:

How many months exist on Mars and how much data do we have for each month? There are a total of 12 months on Mars.

How many Martian days' worth of data exist in the scraped dataset? There are 1867 Martian days' worth of data in the dataset.

Which month, on average, has the lowest temperature? The highest? The month with the lowest average temperature is month 3, with an average low temperature of -83.3°C. The month with the highest average temperature is month 8, with an average low temperature of -68.3°C.

Which month, on average, has the lowest atmospheric pressure? The highest? The month with the lowest average atmospheric pressure is month 6, with an average pressure of 745.05. The month with the highest average atmospheric pressure is month 9, with an average pressure of 913.31.

About how many Earth days exist in a Martian year? There are approximately 705.8 terrestrial days in a Martian year.

Technologies Used:
Python, 
Jupyter Notebook, 
Beautiful Soup, 
Splinter, 
Pandas, 
Matplotlib, 
Selenium
