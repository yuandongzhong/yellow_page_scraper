# Description
This is a web scraping program that will extract business details based on a city and a category from Yellow Pages. 

# Installation Requirement
- python3
- requests
- unicodecsv
- lxml

# How to use
To use it, what we do is to simple provide a search keyword and a place name to the program. Like this:

```
python yellow_page_scraper.py [search keyword] [place]
```

For example, if we want to search for coffee shops from Boston, we just type this:

```
python yellow_page_scraper.py 'coffee shops' 'Boston,MA'
```

After the scraping is done, a csv file containing all the business datas will be generated. The csv file can be opened by Excel program like a normal Excel file.


# Data Demo
- coffee shop-Boston,MA-yellowpages-scraped_data.csv

