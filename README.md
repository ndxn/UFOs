# UFOs

## Challenge
This project builds from the natural point where the module left off. The module work brought the site **The Truth Is Out There** to the point where it could take a single date and filter the JavaScript file containing the UFO sightings and display them in the HTML table. From that point, the challenge was to add additional filters, including 

## Technologies Used
There are two main technologies underpinning this project, one for the frontend and one on the backend. The front end is build on HTML and associated technologies. The first of these associated technologies is CSS, which almost invariably accompanies HTML sites. The use of bootstrap allows the CSS file to be rather spartan--only a background color and a background image are defined, whereas bootstrap take the lions share of setting a dynamic layout and styling. 

The backend is powered by JavaScript. The information regarding UFO sightings is stored as a list of dictionaries in a JS file while the code to return the filtered data is coded in its own files. Accompanying JS, the Data-Driven Documents, or D3, allows for interactivity between user inputs and the JavaScript filters. 

These technologies work together as such. Then webpage structure is created in HTML and dressed up using CSS and bootstrap. Users may enter filters and D3 is the connection that hands those inputs into the JS function and the return is displayed in the webpage as an HTML table.

## Further Development
While the webpage is able to take user inputs and create filters based on the exact inputs, such pure interaction does not work very well in the real world. Often, what users input into a system will not be the pristine condition that this program requires. The most basic example of this limitation is if a user correctly inputs a value into a field where there is no match, the table will return empty. A basic fix for this problem would be an encapsulating if-else statement that will return a message.

However, it's entirely possible that a user will simply enter a value incorrectly. A live lookup and matching of values would help ensure that users cannot enter incorrect values. 

Finally, there are usability issues inherent with this program. It is usually not practical or particularly useful to look up just one date. A relatively simple solution would be to have a date range and to filter results based on being greater-than or equal to the lower limit and less-than or equal to the upper limit. Another usability issue with the program is that typing in values for the filters is not the most practical operation for all types. Date might be better entered via a pop-up calendar. States could be a list. But the most glaring and perhaps unusual filter is that for shape. The JS data should be cleared up and generalized into just a few different kinds of shapes that can be represented in a list--after all, how different is a rhombus from a diamond?