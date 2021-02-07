# JavaScript - UFOS
## Project Overview 
The purpose of this project is to provide a webpage that hosts a dynamic table of data. The project uses JavaScript and HTML to filter the data for city, state, country, and UFO sighting shapes, in addition to styling how the data is presented.  

## Results
Upon opening, the webpage displays all data. 

![default](/readme_images/default.png)

The filters on the left side are text input fields, where users can enter a criteria to filter the data. The example below shows the data filtered by date, namedly 1/13/2010.

![filters](/readme_images/filters.png)

Data can be filtered by more than one criteria. The table is filtered once the desired criteria has been input. 

## Summary
**Drawback of Webpage** 
One disadvantage of this webpage is that the search criteria must be input exactly as it appears in the data. For example, if the user wants to filter the data by sightings in California, the data will only filter if "ca" is input into the "State" text field. It will not filter is "California" is entered. 

**Recommendations** 
1. Due to the previously mentioned point, a recommendation for further development would be to allow for less strict filters to account for different ways search criteria can be entered. 

2. If the above recommendation cannot be incorporated, another way to resolve this issue would be to add a dropdown menu of allowable searches to each filter. This way users would be limited to filters that exist within the data. 