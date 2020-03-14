# Amazon-Web_Scrape
Amazon Web Scraper

This pulls up an Amazon page for the search result "soap+bars"

The script will then attempt to find all instances of the html tag <a> ( a link tag) where the "class" attribute is "a-size-base"
  
Problems: The script seems to open the page and return a different amount of tags for each time it is run:

LOG:
3/14/2020 - 2:30pm EDT Length Results for 10 runs:
0 / 20 / 55 / 25 / 57 / 55 / 6 / 59 / 54 / 39
