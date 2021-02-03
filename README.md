# soup_follow_scraper
 Scrapes a single URL for internal links

This scraper uses the Python library BeautifulSoup to scrape a GitHub page for its internal links.


The function internal_links finds all webpages that end with .html in the anchor elements. 

The __main__ loop appends all pages to the site_links list so that they do not repeat, and then prints them.

TODO: Implement a function that scrapes and prints external links on the site. 