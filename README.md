# Mission-to-Mars
Web-scraping and Data Analysis project for the mission to Mars

## Data Analysis 

Using Web-scraping (with Splinter and HTML parsing with Beautiful Soup) the main goal of this project is to collect news items about Mars missions and scrape, organize, analyze, visualize Mars climate data.
In this Analysis automated browser was used to scrape, or extract, data about the [National Aeronautics and Space Administration (NASA) Mars exploration.](https://github.com/MilosPopov007/-Mission-to-Mars-/blob/main/part_1_mars_news.ipynb)





![This is an image](https://github.com/MilosPopov007/-Mission-to-Mars-/blob/main/Mars_scraping%20.png)


Web scraping automates the tedious tasks of extracting online data for analysis. Instead of a person manually visiting each website, copying the data, and then pasting that data into a file, a web-scraping script automatically performs all those actions and, if necessary, organizes the data for analysis. That is, instead of us manually collecting and formatting the data, web scraping automates the process for us. 

To obtain Mars weather data for the  [Analysis](https://github.com/MilosPopov007/-Mission-to-Mars-/blob/main/part_2_mars_weather.ipynb) several steps were taken :

*  Use automated browsing to visit the Mars Temperature Data Site Links to an external site
*  Inspect the page to identify which elements to scrape
*  Create a Beautiful Soup object and use it to scrape the data in the HTML table
*  Assemble the scraped data into a Pandas DataFrame
*  Analyze dataset by using Pandas functions
*  Export the DataFrame to a CSV file


![This is an image](https://github.com/MilosPopov007/-Mission-to-Mars-/blob/main/Mars_table.png)


### Mars Weather Data Summary

On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!

Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.

A visual estimate of the terrestrial days ( The distance from peak to peak is roughly 1425-750, or 675 days ), confirms that a year on Mars appears to be about 675 days from the plot. Internet search confirms also that a Mars year is equivalent to 687 earth days.







