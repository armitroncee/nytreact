# nytreact

see the deployed version here https://boiling-tor-57598.herokuapp.com/

![site](/images/screen1.png)

This web app is made in React.js and using express and node.js for the backend. It also uses MongoDB for the database.
In this app you can search for an article in the New York Times database using an ajax request. It will display the top 5 
results in the results card. The results will display dynamically. It will have the title of the article, a web url so you can 
check out the article, and a brief description of the article. You can also save the article by pressing the save button. This will 
save the article to the database so whenever you open the app back up it will stay there persistently. In the save section you can
delete any article you don't want saved anymore and that will delete it from the database.