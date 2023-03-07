# Web-Scraping

## Objectives

Scrape data using BeautifulSoup, Splinter, Pandas, and WebDriver_Manager:

Latest News Title and Paragraph Text from Mars News Site
Featured Mars Image URL from JPL Mars Space Images
Mars Facts Table from Mars Facts
Mars Hemisphere Titles and Full Resolution Image URLs from Mars Hemispheres

Use MongoDB and Flask templating to create a webpage that:

Runs the Python script to scrape data at the click of a button
Stores the scraped data into MongoDB
Retrieves the most recent MongoDB entry
Displays all collected information in a clean webpage on the index route

## Part 1: Scraping

Complete your initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.

Create a Jupyter Notebook file called mission_to_mars.ipynb. Use this file to complete all your scraping and analysis tasks. The following information outlines what you need to scrape.


## NASA Mars News


Scrape the Mars News Site and collect the latest News Title and Paragraph Text. Assign the text to variables that you can reference later.
# Example:
news_title = "NASA's Next Mars Mission to Investigate Interior of Red Planet"

news_p = "Preparation of NASA's next spacecraft to Mars, InSight, has ramped up this summer, on course for launch next May from Vandenberg Air Force Base in central California -- the first interplanetary launch in history from America's West Coast."
JPL Mars Space Images—Featured Image
Visit the URL for the Featured Space Image site here.

Use Splinter to navigate the site and find the image URL for the current Featured Mars Image, then assign the URL string to a variable called featured_image_url.

Be sure to find the image URL to the full-sized .jpg image.

Be sure to save a complete URL string for this image.

# Example:

featured_image_url = 'https://spaceimages-mars.com/image/featured/mars2.jpg'

## Mars Facts

Visit the Mars Facts webpage and use Pandas to scrape the table containing facts about the planet including diameter, mass, etc.

Use Pandas to convert the data to a HTML table string.

## Mars Hemispheres

Visit the astrogeology site to obtain high-resolution images for each hemisphere of Mars.

You will need to click each of the links to the hemispheres in order to find the image URL to the full-resolution image.

Save the image URL string for the full resolution hemisphere image and the hemisphere title containing the hemisphere name. Use a Python dictionary to store the data using the keys img_url and title.

Append the dictionary with the image URL string and the hemisphere title to a list. This list will contain one dictionary for each hemisphere.


## References

The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
