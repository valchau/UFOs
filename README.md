# UFOs
Module 12 using JavaScript and bootstrap
# UFO Sightings with JavaScript

## Overview
In this module, the task is to create a table using JavaScript, allowing users quick access via a website to some UFO data. The JavaScript table will be accessed using JavaScript functions, allowing the user to perceive the website as being dynamic, and changing based on the user's input. 

### JavaScript and HTML 
The table was created using JavaScript, while HTML/CSS were used to modify the website's look and feel. To perform this analysis, we created a file structure for the website, where the main HTML file is in the UFOs folder, and there is a static subfolder here as well. Inside the static subfolder are folders for images, for css (the styple sheet), and the folder js to hold 2 JavaScript files,  one with the data in the table that will be presented to website users and the other JavaScript file contains js functions that provide the user's access to this data.  

### bootstrap library
The JavaSCript library D3 was used in the code, because it can produce sophisticated and highly dynamic graphics in an HTML webpage. It is often used by data professionals to create dashboards, or a collection of visual data (such as graphs and maps), for presentation. The bootstrap library of styles and JavaScript was used to make the website more interesting to the user as well to resize correctly for different size devices.

## Results:
### the Website
Welcome to UFO Sightings website. Once you view the website, you can see the data we use on the right and the selection fields each with their own textboxes on the left. The date is formatted as a 'date' and the other fields accept text. 
[How the website looks at the start](static/images/website_start.PNG) 

### How to choose a city 
If you review the data in the table on the right side of the webpage, you can enter the filters in the left side text boxes, and the filters result in returning 2 matches if you choose the filters correctly. Make sure to type everything in lower case letters and do not have spaces at the end of the text. Click off the input box or press enter to initiate the filter. To reset the filter criteria, click the UFO Sightings at the top left of the website.

[How the website looks once you choose a city](static/images/website_elcajon.PNG) 

### what the results look like 


## Summary:
One major drawback of this static data website is that the data is a very small subset of real world data. And the user must know specific dates, cities, or shapes to search for UFOs. Also some shapes such as "light" might not be intuitive to every user. And to use the filters, the user must already know something about the data values, especially for cities.  For cities, we usually start their names with capital letters, however, the data uses only lower case for city names. Therefore, since the filters to located a city require correct lowercase spellings and do not include spaces at the end. The city that was used as an initial placeholder in the form could not be typed as "sandiego", “san diego_”, or "San Diego". The only acceptable input would be "san diego". 
