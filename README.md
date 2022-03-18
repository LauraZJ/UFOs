# UFOs
## Purpose
The purpose of this project is to use JavaScript, html, css and bootstrap to create a web page.  The process includes:
* creating multiple filters
* creating an event listener to detect changes to each filter
* looping through the data for each filter to retrieve data that matches the filter values
* displaying filtered data on the web page

## Results
A visitor to this web page would use the filters to obtain specific data rather than read through the entire page.  The filter opportunities are displayed in the image below and include examples of text entry for each filter:
![web page image]()

### Filter by Date
The image below is the data filtered by a singe date.
![datefilter]()

### Filter by City
The image below is the data filtered by a chosen city.
![cityfilter]()

### Filter by State
The image below is the data filtered by a selected state.
![statefilter]()

### Filter by Country
Given that our dataset only has US entries any filter choice of another country returns no data.  Otherwise, all the data is US data so nothing is filtered out.
### Filter by Shape
The image below is the data filtered by a chosen shape.
![shapefilter]()

### Multiple Filters
In addition to the single filter options (displayed above), the user may use multiple filters to further narrow the data search.  In the example below, I have filtered by date, state, and shape.  A true UFO investigator would use this data to map out the data to determine potential for multiple sightings of the same UFO.

![multipfilters]()

## Summary
### Drawbacks
There are multiple drawbacks of this web page:  
* The filters are case-sensitive and there is no guidance to advise the user to use lower case when entering text in the filters.
* There are no instruction on how to clear the filters. 
* Some of the data in the 'shapes' field, aren't actually shapes.   

### Recommendations
To improve this page, I would make a few modifications.
1. I would either add instructions that all filter entries should be lower case - or develop the filters so that they are not case-sensitive.
2. I would add a 'clear filters' button.
3. I would consider changing the date filter to a date-range filter to enable a better data capture.
4. I would change the city, state, country, and shape filters to drop down lists so that the user will know what the filter options are.
5. Given that the current data set only has US entries, I would remove the country filter.
