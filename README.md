# UFOs

## Overview of Project:
__________________________________

The goal of this project was to build a dynamic webpage that filters results based on input from users. We will develop the functunality of the site by inserting JavaScript into our HTML page. We will enhance this site using CSS and Bootstrap and do our testing using Chrome dev tools. The site will hold a table that pulls in data based on user preferences within specific criteria selection supplied to the user. We allows usuers to refine their search and filter the data provided to be presented in a visually appealing website.

I have been tasked to work with Dana a data journalist who is writing about her hometown McMinnville, Oregon. Dana is excited to write about her hometown but for a unique reason. McMinnville is famous for UFO sightings and has festival held annualy by UFO fans. For this task Dana has provided a Javascript  file that provides sighting information.Our goal is to create an interactive webpage that allows readers to parse the data around UFO sightings. We will store the data in our webpage in a table but to make it more user friendly we will use Javascript to allow the data to be filtered based on the user prefrences. The webpage will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript).


________________________________________

## Results: 
______________________________________________

This new site allows users to seach for UFO sighting data based on multiple criteria below.

* Date
* City
* State
* Country
* Shape
* Duration
* Comments

Once data is entered the site will filter and display results refined to user prefrences.

### Five list elements for filtering in the index.
______________________________________________________________




### Modified event listener to detect changes to each filter in the app.js file.
____________________________________________________________________




### The updateFilters() function saves the element, value, and the id of the filter that was changed.
__________________________________________________________________________



### FilterTable() function loops through all of the filters and keeps any data that matches the filter values.
__________________________________________________________________________________




### The webpage filters the table correctly based on user input.
__________________________________________________________________




### Summary: Drawback of this new design and two recommendations for further development.

In summary we were able to build a dynamic webpage that filters results based on input from users. We developed our interactive site by inserting JavaScript into our HTML page and enhacned the features using CSS and Bootstrap. During testing of our new tool I encountered a few opportunities to enhance our site and make it more beneficial to the users. The first draw back I find with  the website is that the data used comes from a static source. As time progresses the website data will become obselete and will be out of date. My first recommendation would be to use a source that is maintained regulary to capture up to date information to be displayed for users. I believe the search criteria for date can be changed to include a date span to provide more results. I believe dynamic and more flexible data presents to be more useful that static and allows users to gain a more personal experience.