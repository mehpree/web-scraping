# Mars Web Scraping and Data Analysis Project

## Introduction

Welcome to the Mars Web Scraping and Data Analysis project! In this assignment, I have conducted a comprehensive web scraping and data analysis project focused on Mars-related data. I've utilized web scraping techniques, automated browsing, and data analysis to gather and analyze Mars news articles and Mars weather data.

## Part 1: Scrape Titles and Preview Text from Mars News

In this section, I have scraped titles and preview text from Mars news articles. Here are the key steps I've followed:

1.  **Automated Browsing:** I used automated browsing techniques to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html) and identified the elements to scrape.
    
2.  **Beautiful Soup:** I created a Beautiful Soup object to parse the website's HTML and extracted relevant text elements from the page.
    
3.  **Data Storage:** I stored the scraped data in Python dictionaries, each containing the title and preview text of a news article. These dictionaries were then stored in a Python list.
    
4.  **Data Display:** I printed the list of scraped data in the Jupyter Notebook for easy viewing.
    
5.  **Optional Export:** Optionally, I provided the functionality to export the scraped data to a JSON file for sharing purposes.
    

## Part 2: Scrape and Analyze Mars Weather Data

In this section, I have scraped and analyzed Mars weather data, which exists in an HTML table. Here are the key steps I've followed:

1.  **Automated Browsing:** I used automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and identified the elements within the HTML table to scrape.
    
2.  **Beautiful Soup for Data Extraction:** I created a Beautiful Soup object to extract data from the HTML table. Instead of using Pandas' `read_html` function, I continued honing my web scraping skills.
    
3.  **Data Conversion and Cleaning:** I assembled the scraped data into a Pandas DataFrame, ensuring that data types were appropriate for each column. I converted data to datetime, int, or float where necessary.
    
4.  **Data Analysis:** I conducted data analysis using Pandas to answer various questions about Mars weather data. This included finding the number of months on Mars, Martian days worth of data, identifying the coldest and warmest months, determining months with the lowest and highest atmospheric pressure, and estimating terrestrial days in a Martian year.
    
5.  **Data Export:** Finally, I exported the cleaned and analyzed DataFrame to a CSV file for further use.
    

This project showcases my web scraping and data analysis skills, providing valuable insights into Mars news and weather data. Enjoy exploring the wonders of Mars!

### References
[The Mars News websiteLinks to an external site.](https://static.bc-edx.com/data/web/mars_news/index.html)  is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from  [NASA's Mars NewsLinks to an external site.](https://mars.nasa.gov/)  website in November 2022. Images are used according to the  [JPL Image Use PolicyLinks to an external site.](https://www.jpl.nasa.gov/jpl-image-use-policy), courtesy NASA/JPL-Caltech.
