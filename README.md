# UFOs
Creating a dynamic, interactive website to display UFO sighting data

## Overview
The purpose of this analysis is to create a functional dynamic website that includes an interactive dashboard for users to explore and search for specific UFO sighting data by location, date, and/or shape. 

## Results
How to use the webpage:

** main_page.png

1) The main page will load with all of the unfiltered data displayed for the user to scroll through. 

** filter_search.png

2) To search for specific criteria, the user may input text into any of the fields within the "Filter Search" box on the middle-left of the page.

** city_filter.png

3) Once a user has input text into the desired field(s), they should press enter to update the table. If there is no matching data, the table will be blank.

** city_state_filter.png

4) Note that when entering text in more than one field, the table will display entries matching EITHER filter.

5) To reload the original table, the user should refresh the page. 

## Summary

**Drawbacks:**

This design is a very simple webpage that has some drawbacks and definite potential for further development. One drawback is the relatively small dataset currently available for the user to explore and filter. Another drawback is the simplicity of the filtering tool. Inputing text into more than one filter expands the resulting data rather than narrowing it down further. If a larger dataset were to be used for this site it could make the search process confusing. This could be solved by re-writing the script to display the data that matches BOTH filters rather than either filter. 

**Further Development:**

In addition to curating a larger dataset to use and modifying the filtering tool, more adjustments can be made to the code to create more ease of use. A 'reset' button could be added to empty any applied filters and re-load the original data table so the user no longer has to refresh the page. Additional filters can also be added to search by Duration or other features that can be added when transforming a larger dataset of UFO sightings. Finally, this design can easily be refactored to a variety of topics and datasets that have nothing to do with aliens. 