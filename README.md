# tasks1

https://github.com/topics/udemy-clone


Cart = Ajax 

1. create separate header/footer files and include in index/products/contact files
2. create config.php file in project root location to store common variables and constants.
3. create array of products from products.php html section and replace current product listing using foreach loop
4. implement add to cart functionality using jquery ajax.

To do = Ajax
Create a ToDo list based on template provided.

Conditions:
page won't reload for any operation
add/delete/update todo
mark complete todo
list completed and pending todos in different group as in template
once use click edit todo, value should populate in top todo form and ADD button should change to UPDATE button.
[todo (1).zip](https://github.com/VikasRathore16/tasks1/files/8109498/todo.1.zip)

Cart = Session/cookies
1. create separate header/footer files and include in index/products/contact files
2. create config.php file in project root location to store common variables and constants.
3. create array of products from products.php html section and replace current product listing using foreach loop
4. implement add to cart functionality using PHP Forms/Session/Cookie
[html (2).zip](https://github.com/VikasRathore16/tasks1/files/8109511/html.2.zip)

To Do list = session/cookies
Create a ToDo list based on template provided.

Conditions:
add/delete/update todo
mark complete todo
list completed and pending todos in different group as in template
once use click edit todo, value should populate in top todo form and ADD button should change to UPDATE button.
[todo (2).zip](https://github.com/VikasRathore16/tasks1/files/8109514/todo.2.zip)

Airport
We have a Central Dashboard for all flights and individual Airport Dashboard for Airports.

Take some records manually in flightdata.json file.

Now Central Dashboard display all flight details, let say we have data of 5 flights.

For Airport Dashboard, you can enter flight no. and once Search button is clicked it list From and To Details of flight in display. 

You can update Estimated Arrival & Estimated Departure of flight and press Update button. It would update central database and hence Central Dashboard would update and display changes in realtime.

Status field in Central Dashboard would show statuses like

On Time
Arriving Late By 30mins
Arriving Early By 30mins
Departing Late By 30mins
Departing Early By 30mins
Departed


Depending on Time Entered and Actual Time of user.

You can open 1 Browser Tab for Central Dashboard and multiple tabs on same browser for Airport Dashboards.

Whatever changes you make in Airport Dashboards it reflect back in Central Dashboard automatically with jQuery Ajax.
![IMG_6CB867994A89-1](https://user-images.githubusercontent.com/98630517/155158072-1b7e99c2-6e73-4c50-b28c-bea77e6760b4.jpeg)

If you reload Central Dashboard, it display current changes.





Use:
Spotify API: https://developer.spotify.com/documentation/general/guides/ 
Postman
Phalcon to create app

Create an app in phalcon to which uses spotify data of any user and do following
Step 1:
Use Postman to create a collection Spotify
Use its OAuth authoirzation to get access token
Create requests which are going to be use in our app

Step 2: App in phalcon
Create a search form with 
A Textfield to enter search keywords
filters in checkbox
Button with name SEARCH
Filters can be
"album"
"artist"
"playlist"
"track"
"show"
"episode"
Whatever filters are checked will be included in search api to get results
When hitting SEARCH button we have to show all the results in different section based on filteres choosen
for example if "album" and  "artist" are selected then 2 sections will be there in search results
Creat CRUD of playlist for authenticated user
Create playlist
add tracks into it (this you can do from a search results)
Remove tracks

