# UFOs

## Overview
This analysis was created to add and test the ability to filter multiple criteria on UFO sighting data. Functions to update the filter and table data were added to previously written HTML code resulting in date, city, state, country, and state filters. 

## Results
In order to use the newly implimented filters, the users must enter search values in their entirety and click out of the search box for the code to recognize a change. It is possible to use multiple search parameters, making it much easier for the user to narrow down UFO sighting data.

For example: 

We want to view all sightings in California that were triangle shaped. To do so, filter parameters will need to be typed exactly as the data table lists them - ca and triangle. These filters are also case sensitive, so be sure to double check case.

Output from the entered parameters will be populated as the below image shows. 
![image](https://user-images.githubusercontent.com/90646961/144138259-5846e842-f807-420c-8cf6-51f5dbd944ab.png)

## Summary

A significant drawback to this design is the inability to type in just part of a word. If the data set is large and the user is unsure of spelling or case, they will not be able to search by the pieces that they do know. My recommendation for further simplification would be to ensure that fields are not case sensitive and that they will accept partial words. 
