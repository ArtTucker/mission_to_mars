# Mission to Mars
Web scraping with python, Flask, and MongoDB

## Overview

This project used a variety of tools to scrape data from a few different websites and present a condensed collection of Mars-related data and images on a single site. The tools used consisted of:
- python as the primary language;
- BeautifulSoup for webscraping;
- pandas for carrying over tabular data into a dataframe;
- MongoDB to store and retreive scraped data;
- HTML to present the data;
- Bootstrap and CSS styling to make things pretty;
- Flask as the framework to tie everything together.

Sites used for scraping included:
- [NASA's Mars Exploration Program News Feed](https://mars.nasa.gov/news/)
- An archived version of [NASA's JPL Mars image repository](https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html)
- The Mars page from [Space-Facts.com](http://space-facts.com/mars/)
- Mars hemispheric image search results from [USGS's Astropedia](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars)
