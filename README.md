# html-challenge
# Author: Paul Keller
# Due Date: October 7, 2024

# This challenge takes skills from html and uses it to scrape data from websites and then interpret the scraped data.
# The first part uses a website that features news articles about the planet Mars. The objective was to scrape data
# from the website that showed the title and the preview of every article on the web page. Beautiful Soup was used
# to create a connection to the site and an html parser was used to traverse all the data on the page. Once the data was
# scraped, it was stored in a dictionary which was then appended to a list featuring all the articles. The list was
# then printed to prove its validity.
# The second part uses another website that features the id, terrestrial date, solar longitude, month, minimum 
# temperature, and pressure for data collection of over 1800 observed dates of the planet Mars. The objective was
# to scrape data from the website that was a copy of the data table to later be used for analysis. Again, Beautiful
# Soup was used to create a connection to the site and an html parser was used to traverse all the data on the page.
# Once the data was scraped, it was stored into a dataframe with the proper headings and was then used to answer five
# questions. The data types were then changed from object to more appropriate types for each column. All five questions,
# were answered in the code along with the presentation of five graphs corresponding to three of the questions. 
# Lastly, the dataframe was written to a csv and was exported, which is included in the folder as an Excel spreadsheet.