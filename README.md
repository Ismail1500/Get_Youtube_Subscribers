# YouTubesubscriberProject

This is a backend API that  fetches data from the MongoDB database.
The following actions can be done with the help of the API

<ul>
  <li>Get all the subscribers</li>
  <li>Get subscribers only by name and subscribed channel field</li>
  <li>Find and get data with a specific user ID</li>
</ul>

In this project I have used:-

<ul>
  <li>ExpressJS</li>
  <li>MongoDB</li>
  <li>NodeJS</li>
  <li>Mongoose</li>
  <li>dotenv</li>
  
</ul>
The folder structure consists of an index.js file in the root directory which acts as the main file of this project. Then it has a src folder which contains all the necessary files to execute the required tasks.
In the src folder we have - 

<ul>
  <li>Routes Folder which contains all the routes that are required in the project</li>
  <li>controllers folder which acts as a logic file to execute all the required actions. It contains functions that are passed in the routes</li>
  <li>models folder which contains the Schema and model of the collection</li>
  <li>App.js files for all the requests and middlewares</li>
  <li>createDatabase.js for creating and refreshing the database</li>
  <li>data.js for sample data</li>
  <li>Test folder for the testing that required</li>
  <li>Mocha reported folder which contains an HTML file to view testing visually in the browser</li>
</ul>

First, we have to ```npm i``` command in the terminal to install every dependency
Then we can ```npm run start``` for starting the server and connecting to the database.
Also we can run tests with ```npm run test```
