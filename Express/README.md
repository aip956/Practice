Frank is a simple Express backend </br>
There is no database; the data is in the models folder </br>

It has routes: </br>
GET on /. This action will give randomly (in a pool of at least 20) a name of a song from Frank Sinatra. </br>
GET on /birth_date. This action will give Frank Sinatra birth date. </br>
GET on /birth_city. This action will give Frank Sinatra birth city. </br>
GET on /wives. This action will give all the name of Frank Sinatra wife. (string in the app.js) </br>
GET on /picture. This action will give Frank Sinatra's picture. Uses res.redirect </br>
GET on /public. This action will print "Everybody can see this page" </br>
GET on /protected. This action will be protected by a HTTP Basic access authentication and print "Welcome, authenticated client" if you are authorized with the login admin and password admin otherwise it will provide a 401 Not authorized. </br>

This app is tested using curl commands in terminal; the protected route does not show on localhost </br>