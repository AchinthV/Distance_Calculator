# Distance_Calculator
Take in user input of 2 addresses (A and B). Calculate the distance between A and B.


To do: 
//Help with: 
//the html to display things 
//how to grab and store information on Azure
//Angular.js to speed things up perhaps or streamline
//How to make User Accounts


/*First Request an API KEY
 * then have them enter location A
 * then have them enter location B
 * Press a button : "Calculate"
 * then display the result
 * update result only when the button is pressed
 */
 
 
 //Do all logic in Service

//need to create a class "Location" -> contain a KEY, city, street, number, state, coordinates
/*Take coordinates of object Location A as well as object Location B
 * Find the change in X and change in Y for the object
 * Square their sums then root them to find the exact distance from A to B
 * Call to View, have View display the result
 * Simultaneously (or before) call to Model, store the addresses and the result
 *API KEY for Google Maps:
 * C# 6 String formatting
 * Call for 1600 Amphitheatre Parkway, Mountain View, CA
 * WebRequest locA = WebRequest.Create("https://maps.googleapis.com/maps/api/geocode/json?address="LocationA->getnumber()
 "+"LocationA->getAddress"+"LocationA->getCity"+"LocationA->getState"&key=[" KEY "]");
 1600+Amphitheatre+Parkway,+Mountain+View,+CA&key=[THE API KEY]
 *LocationA->setCoordinates(locA);
 * see Program.cs for instructions for view
 */
 
