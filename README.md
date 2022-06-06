# UFOs Webpage & Dynamic Table
## Overview of Project
> Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape. 

1. ***Deliverable 1***: Filter UFO sightings on multiple criteria
2. ***Deliverable 2***: A written report on the UFO analysis [`README.md`](https://github.com/DataJew/UFOs). 


# Deliverable 1:  
## Filter UFO sightings on multiple criteria
### Deliverable Requirements:
Using JavaScript and HTML, you’ll modify the code in your `index.html` file to create more table filters. In addition to the date filter you created in this module, you’ll add filters for the city, state, country, and shape, as shown in the following image:

(image placeholder)

Using JavaScript, you’ll replace the handleClick() function in your app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".


1. The list element that creates the button is removed, and there are five list elements for filtering in the `index.html` file. 
2. The event listener is modified to detect changes to each filter in the `app.js` file.
3. The `updateFilters()` function saves the element, value, and the id of the filter that was changed.
4. The filterTable() function loops through all of the filters and keeps any data that matches the filter values.
5. The webpage filters the table correctly based on user input.


# Deliverable 2: 
## A written report on the UFO analysis
### Deliverable Requirements:
For your written analysis, be sure to use complete and coherent sentences. Your written analysis should contain three sections, which cover the following:

1. **Overview of Project:** Explain the purpose of this analysis. 
2. **Results:** Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
3. **Summary:** In a summary statement, describe one drawback of this new design and two recommendations for further development.


 
### Results with detail analysis:


1. **Overview of Project:** Our UFOs Project has a single mission, and is to enhance our webpage with capability adding filters with multiple factors.
D3 functionality makes an instance listener for multiple changes in our search, displaying needed datasets on the result table.



2. **Results:** 
(image placeholder)

3. **Summary:** In a summary statement, describe one drawback of this new design and two recommendations for further development.


> Drawback:

During the project we realized that we needed to publicly expose the information, so it was necessary to use GitHub Pages to bring everything in one place.

> Recommendations:

1. **Link to external database for automated updates**

If there was a website that logged UFO sightings, this webpage could be improved by linking the dynamic table, providing the most updated data.


2. **Update `HTML`, `CSS`, and `JavaScript` to include various form of media**

Although our webpage presents that data in a consise format that can be filtered by user, providing external links or additional media files would improve the UI & UX. This could include sourcing of data utilized, deeper analysis of results, as well as reference resources regarding said results.
