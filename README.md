# UFO Sightings
[Working Site](https://ian-t-dixon.github.io/UFOs/)
## Project Overview
For this project we are presenting a dataset of UFO sightings using JavaScript and HTML and allowing users to filter the data with various datapoints to narrow down the search results.

## Instructions for Use
From the main page of the site users are presented with a complete table of our data set. On the left hand side of the page, there is a filters form that allows for the input of multiple filters: Date, City, State, Country, and Shape. The filter requires an exact match for the table data (case sensitive)

![filters](https://github.com/Ian-T-Dixon/UFOs/blob/main/static/images/filters.PNG)

By inputting a matching value into any, several, or all of these filters, the user is able to show only the data that matches
their specific criteria.

![filter FL](https://github.com/Ian-T-Dixon/UFOs/blob/main/static/images/filter_fl.PNG)
![filters FL and Shape](https://github.com/Ian-T-Dixon/UFOs/blob/main/static/images/filters_fl_multiple.PNG)

## Summary:
While the filter works as designed, one of the shortfalls of this is that the user needs to know what criteria to search for. Without a thurough inspection of the data set,
the user may return blank tables if searching for a date or city that is not referenced in the table. Additionally, the filter is case sensitive and exact match only, which may cause problems for users who input criteria in the wrong format. To get around this, I would suggest that rather than utilizing a user
input for the search criteria, a drop down list of the available values within the table be used. This would ensure that the user can only filter for specific values that
are present within the dataset. Additionally, as there is one key not represented in the filter section (Duration), it may be helpful to add one more filter for this. 
