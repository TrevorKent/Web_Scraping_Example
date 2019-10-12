!# Web_Scrapping_PythonApp
Web scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.

# Scrape and Append Data to Dictionary
* Scrape the [NASA Mars News Site](https://mars.nasa.gov/news/) and collect the latest News Title and Paragraph Text. Assign text to variable that can be referenced later.
* Visit the USGS Astrogeology site [here](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) to obtain high resolution images for each of Mar's hemispheres. and assign the url string to a variable.
* Use splinter to navigate the site and find the image url for the current Featured Mars Image and assign the url string to a variable.
* Visit the Mars Weather twitter account [here](https://twitter.com/marswxreport?lang=en) and scrape the latest Mars weather tweet from the page. Save the tweet text for the weather report as a variable.
* Visit the Mars Facts webpage [here](https://space-facts.com/mars/) and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.
* Use a Python dictionary to store the data using keys.

# MongoDB and Flask
* Use MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.
* Create a template HTML file that will take the mars data dictionary and display all of the data in the appropriate HTML elements.

# Sample Results:
Part 1
![final_app_part1.png](Images/final_app_part1.png)
Part 2
![final_app_part2.png](Images/final_app_part2.png)
