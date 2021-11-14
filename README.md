# <img width="750" alt="UFO_Title" src="https://user-images.githubusercontent.com/88467263/141687384-a445c622-e5b1-41ca-9ed9-350cb130b452.PNG">


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

<img width="444" alt="five_list_elements_for_filtering" src="https://user-images.githubusercontent.com/88467263/141687341-d4b12825-d458-4618-8a94-e9575d7ff650.PNG">



### Modified event listener to detect changes to each filter in the app.js file.
____________________________________________________________________

<img width="441" alt="Event_listener" src="https://user-images.githubusercontent.com/88467263/141687366-d46cc58a-18fe-4f45-8bad-56f5abca7bc0.PNG">




### The updateFilters() function saves the element, value, and the id of the filter that was changed.
__________________________________________________________________________

<img width="490" alt="Update_filters" src="https://user-images.githubusercontent.com/88467263/141687357-328d3bec-2268-4cb2-9623-b5e5bb092429.PNG">


### FilterTable() function loops through all of the filters and keeps any data that matches the filter values.
__________________________________________________________________________________

<img width="461" alt="Filter_table_loop" src="https://user-images.githubusercontent.com/88467263/141687373-a5e98d0e-db57-4cc3-8c82-bce7b510bccf.PNG">



### The webpage filters the table correctly based on user input.
__________________________________________________________________

<img width="942" alt="Filtered_webpage" src="https://user-images.githubusercontent.com/88467263/141687379-718e2adb-a3cd-4d22-9cb8-7579128373f9.PNG">



### Summary: Drawback of this new design and two recommendations for further development.

In summary we were able to build a dynamic webpage that filters results based on input from users. We developed our interactive site by inserting JavaScript into our HTML page and enhacned the features using CSS and Bootstrap. During testing of our new tool I encountered a few opportunities to enhance our site and make it more beneficial to the users. The first draw back I find with  the website is that the data used comes from a static source. As time progresses the website data will become obselete and will be out of date. My first recommendation would be to use a source that is maintained regulary to capture up to date information to be displayed for users. I believe the search criteria for date can be changed to include a date span to provide more results. I believe dynamic and more flexible data presents to be more useful that static and allows users to gain a more personal experience.
