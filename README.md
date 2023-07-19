# web-scraping

Instructions
### Part 1: Scrape Titles and Preview Text from Mars News
Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

1.	Use automated browsing to visit the [Mars new site] (https://static.bc-edx.com/data/web/mars_news/index.html) Links to an external site.. Inspect the page to identify which elements to scrape.
2.	Create a Beautiful Soup object and use it to extract text elements from the website.
3.	Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
o	Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:

![image](https://github.com/mehpree/web-scraping/assets/131678606/a2f81913-6467-4fb6-88fb-80ae55d24aab)

o	Store all the dictionaries in a Python list.

o	Print the list in your notebook.

4.	Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)

### Part 2: Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
1.	Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
2.	Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
3.	Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
o	id: the identification number of a single transmission from the Curiosity rover
o	terrestrial_date: the date on Earth
o	sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
o	ls: the solar longitude
o	month: the Martian month
o	min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
o	pressure: The atmospheric pressure at Curiosity's location
4.	Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
5.	Analyze your dataset by using Pandas functions to answer the following questions:
o	How many months exist on Mars?
o	How many Martian (and not Earth) days worth of data exist in the scraped dataset?
o	What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
	Find the average minimum daily temperature for all of the months.
	Plot the results as a bar chart.
o	Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
	Find the average daily atmospheric pressure of all the months.
	Plot the results as a bar chart.
o	About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
	Consider how many days elapse on Earth in the time that Mars circles the Sun once.
	Visually estimate the result by plotting the daily minimum temperature.
6.	Export the DataFrame to a CSV file.

### References
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
