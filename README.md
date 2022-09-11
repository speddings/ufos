# Unidentified Flying Objects (UFO's)

## Overview of UFO's
The purpose of this analysis is to create an interactive webpage that allows readers to parse the data around UFO sightings.  The webpage includes a form to filter the data.

## Resources
1. Javascript E6
2. Javascript libraries: D3
3. HTML
4. Bootstrap
5. CSS


## Results of UFO's
The final result is a working website that offers five different ways to filter the UFO data: date, city, state, country, and shape.

![website](/images/landing-page.png)

* The webiste is designed with HTML and Javascript and uses bootstrap and CSS for styling.
* The website displays the data in a structured table format
* The data can be easily filtered. Click on an input box and enter a search string. Search strings must match the data exactly.  Misspelling will result in an empty table. 
* The filter can be reset in one click. Use the title in the top left corner where it says **UFO Sightings** to reset the filters.

## Summary of UFO's
Overall, the website is easy to read and functions as intended.

### Drawback
Filter input search strings must be an exact match, meaning they require the input to match the data exactly. Using the city search as an example, 'Boca Raton' and 'boca' return zero results. only the search string 'boca raton' will return any results. Additionaly, the site dependes on a static data file rather than a data source that is dynamically updated with new data.

### Recommendations
1. Improve the filter input to accomodate variations like upper vs lower case, trailing spaces, and partial words.

*Search example that returns zero results*
![search-boca](/images/search-boca.png)

2. Find a 'live' data source.  A live data source will improve the website by offering new data. Scraping data will automate the data refresh, making it easier and more efficient to keep the website current.
