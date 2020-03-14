# Amazon-Web_Scrape
Amazon Web Scraper

This python code pulls up an Amazon page for the search result "soap+bars"

The script will then attempt to find all instances of the html tag <a> (a link tag), where the "class" attribute is "a-size-base"
  
Problems: (1) The script opens the page but returns a different amount of tags for each time it is run:

LOG:
3/14/2020 - 2:30pm EDT Length Results for 10 runs:
0 / 20 / 55 / 25 / 57 / 55 / 6 / 59 / 54 / 39


Notes:

Python Version: 3.8.1 (updated 12/18/2019)

Modules in use:
(1) Bs4 (updated 12/18/2019)
(2) Selenium (updated 12/18/2019)
