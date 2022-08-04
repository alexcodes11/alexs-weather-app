# Alex's-Weather-App

Welcome to my Weather App project!!! 

<br>

First of all, I wanted to explain that I have another two seperate repositories for this application. One repository is for the Backend (Node.js Proxy Server) and the other repostitory is for the Frontend (React). This is perfect because if I ever want to expand this project I can have dedicated repositories. This will be much more organzied. And when I want to deploy changes I can connect them on this repository.

## View Live Demo
[https://alexs-weather-app.herokuapp.com/](https://alexs-weather-app.herokuapp.com/)

## Node.js Proxy Server
You can check out the code here: [github.com/alexcodes11/Weather](https://github.com/alexcodes11/Weather). Now, let's talk a little about what I did in the backend... 
<br>
* First, I fetched the both the Google Places API and the Weather API into my proxy server.
* Next, I made a REST API for both API's so I can call data from the NODE.js server.
* I then added caching through a middleware for both APIs. This allows for future requests becoming faster than usual. 
* I added rate limiting to my APIs which prevents spammers from making to many requests to my API server.
* I secured the API key by hiding it with an env variable in the nodejs. 


## React Frontend 
You can check out the code here: [github.com/alexcodes11/WeatherApp](https://github.com/alexcodes11/WeatherApp). Now. let's discuss the frontend a little more...
<br>
* Now, that I have implemented the REST API. I am now able to request for the API data using React. 
* It is much more simple now. Because instead of calling an API like this in the front end: 
* ``` fetch(); ```js

