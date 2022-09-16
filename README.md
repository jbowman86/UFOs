# UFOs Sightings

## Purpose

1. Explain the strengths and weaknesses of JavaScript and JavaScript version ES6+.
2. Describe JavaScript syntax used to explore UFO sightings.
3. Build and deploy JavaScript functions, including built-in functions.
4. Convert JavaScript functions to arrow functions.
5. Build and deploy forEach within JavaScript.
6. Create, populate, and filter a table using JavaScript and HTML

## Overview 

The request from a client was to present a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria, such as date, location, and shape of UFO, creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the visuals within the website. 

## Results:

### Website landing page

The front page of the website collating the data of UFOs sightings is displayed below:

![](https://github.com/jbowman86/UFOs/blob/main/static/images/UFO_sighting_landing_page.png)

### How the filters appear when first landing on the page:

The filters used to organize UFOs sighting data include filters for the following criteria:

1.	Date
2.	City
3.	State
4.	Country
5.	Shape

An image of the website filters prior to inputting search criteria can be seen below:

![](https://github.com/jbowman86/UFOs/blob/main/static/images/UFO_filters_default.png)

### How the filters appear after being used: 

To complete a search, type the search criteria within the provided text box beside each filter option.  It is noted that search terms need to be typed in lower case letters and without spaces at the end of the search.  This is due to the case sensitive nature of the search criteria within the website’s filters.  Searches are completed by pressing “Enter” or clicking off the text boxes. Furthermore, searches can be completed using all or some of the filters.  It is not necessary to provide inputs for all filter text boxes in order for a search to be completed.  Search filter criteria can be reset by clicking the UFO Sightings text at the top left of the website.  Searches completed by filter criteria are included below:

#### Filtering by date

The user enters the desired date (included day, month, and year).  The input is recorded and the table to updated to display the relevant UFO sightings.

![](https://github.com/jbowman86/UFOs/blob/main/static/images/UFO_filter_date.png)

#### Filtering by city

The user enters the desired city, the input is recorded and the table to updated to display the relevant UFO sightings.

![](https://github.com/jbowman86/UFOs/blob/main/static/images/UFO_filter_city.png)

#### Filtering by country

The user enters the desired country, the input is recorded and the table to updated to display the relevant UFO sightings.

![](https://github.com/jbowman86/UFOs/blob/main/static/images/UFO_filter_country.png)

#### Filtering by state

The user enters the desired state, the input is recorded and the table to updated to display the relevant UFO sightings.

![](https://github.com/jbowman86/UFOs/blob/main/static/images/UFO_filter_state_shape.png)

#### Filtering by shape

The user enters the desired UFO shape, the input is recorded and the table to updated to display the relevant UFO sightings.

![](https://github.com/jbowman86/UFOs/blob/main/static/images/UFO_filter_state_shape.png)

## Summary: 

### Drawback:

Although the UFOV sighting website is effective in displaying the filtered results, there are some drawbacks to the way the website currently functions.  In order the complete accurate searches, the user must know specific dates, cities, or shapes to search.  Additionally, some shapes like "light" might not be as intuitive and unless the user knows this specific term for classifying UFO sightings, they may not get all the desired results.  Furthermore, The filters require correct lower-case spellings and cannot include spaces at the end.  The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon".  The only accepted input would be "el cajon".

### Recommendations: 

1.	The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.
2.	Inclusion of a drop-down lists for each filter criteria instead of input text boxes would allow the website users to search for UFO sightings without having the remember to case specific terms.  These lists would update after the selection of each filter parameter is selected.
