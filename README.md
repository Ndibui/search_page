# search_page #
A responsive single page prototype of search results

###### How to Search
Enter Name, Age or Country in Search Page
Sample Countries to use: Somalia, Congo, South Sudan and Syria
After search, the user can refine the results using the Name, Age and Country - specific search boxes

###### Technology
AngularJS, Materialize CSS and HTML5

###### How it works
Used ng-repeat to loop through results and display as styled
Used ng-show to only display items after search

###### Limitations
This method will only work for few results since every item is held in the DOM

###### Recommendations
Use a custom filter in a controller and only fetch filtered results asynchronously.
