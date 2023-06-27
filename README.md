# IMDB-website-Scraping

Performed web scraping in Python using Beautiful Soup and Requests module. Python program to scrape the IMDB website and then load the desired data into an Excel file.

Web Scraping is the process of programmatically extracting some data from a website. In Python, we can easy write program to scrape website by using the Beautiful Soup and Requests module. Requests module can be used to access the desired website and Beautiful Soup module can be used to parse the HTML source code of the website. Beautiful soup makes it very easy to parse HTML content and then provides multiple methods which can be used to extract the data from any HTML tags. All the website are written in HTML language hence in order to perform web scrapping, our program needs to read the HTML content. This is were Beautiful Soup comes into picture to make it very easy to access the contents of HTML using very simple methods.

python program which will access the IMDB website and then fetch the top rated movies present in the IMDB website and then load this data into an excel file.
IMDB website contains movie ratings but in this program we are only interested in scraping the top rated movies of all time only.

In order to load data into an excel file, I will be using openpyxl module. Using openpyxl, it is very easy to create a new excel file and then rename the sheet name and then load data into the excel file. I won’t be explaining openpyxl in detail but will just cover enough to know how to create an excel file and then load data into an excel file.
