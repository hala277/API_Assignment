# Investigating APIs

* ## [LocationIQ](https://locationiq.com/)

### 1.API Description

*LocationIQ offers enterprise-grade location-based solutions that are adaptable. Every day, they collaborate with developers, entrepreneurs, and businesses all across the world to serve billions of requests.*

### 1.API Usage

*in my server, I did use Europe endpoint and I did choose to use the key which is required to add and I did add q to search for, use a free-form query string. Commas are optional, but they increase speed by decreasing the search's complexity. Combining structured/postal code parameters is not recommended. so I did use this one.`https://eu1.locationiq.com/v1/search.php?key=pk.dba98f11f1ab559ebe7f36c0b03e9610&q=Amman&format=json`*

### 1.API Endpoints/Request URLs

*The Autocomplete API endpoint provides an Anycast IP address and routes user queries to the nearest datacenter. Similar to other LocationIQ endpoints, you  still can explicitly select a region.`https://eu1.locationiq.com/v1/search.php?key=pk.dba98f11f1ab559ebe7f36c0b03e9610&q=Amman&format=json`*  

### 1.Authentication Key

*An access token is required for any request to LocationIQ's APIs or Map tiles.*
key = `pk.dba98f11f1ab559ebe7f36c0b03e9610`

---------------------

* ## [Moviedb](https://www.themoviedb.org/)

### 2.API Description

*The moviedb API service is for developers who want to use pictures and/or data from movies, TV shows, or actors in their applications. moviedb API is a mechanism that allows you and your team to retrieve and use our data and/or photos programmatically.*

### 2.API Usage

*in my server i did use query its for search and MOVIE_API_KEY for the key and in this way I will look to movie and that what i did use in my server`https://api.themoviedb.org/3/search/movie?api_key=${MOVIE_API_KEY}&query=${query}`*

### 2.API Endpoints/Request URLs

`https://api.themoviedb.org/3/search/movie?api_key=${MOVIE_API_KEY}&query=${query}`

### 2.Authentication Key

*On version 3, application-level authentication is managed by api key, a single query parameter, or by using your v4 access token as a Bearer token. Log in to your TMDB account and select the "API" link on the left hand sidebar of your account page to get an API key. I used api key in my case.*
key = `f05abe10b41e11666cd796b3522255e6`

---------------------

* ## [Weather Bit API](https://www.weatherbit.io/)

### 3.API Description

*With the Weather API, you may get real-time weather data from over 47,000 live weather stations, as well as historical weather data from over 120,000 stations, doppler radar, satellite, and atmospheric re-analysis products over the previous 10 years. Also, highly localized weather forecasts for every location on the planet, based on the world's most reliable weather models!*

*You may seek weather information using a variety of techniques, including:*

1. Latitude/longitude
2. Name of the city
3. Identification of the City
4. The ID of the weather station
5. ICAO code for an airport
6. Any nation in the world has a postal (zip) code.

### 3.API Usage

*I did use this API to get Weather Forecasts for 16 days,Forecasts for the next 16 days / daily for every area on the planet Among the world's most accurate weather models include the GFS 13km, ECMWF, DWD 6.5km ICON-Europe, and NOAA 3km HRRR.The 22 weather fields returned included temperature, precipitation, snowfall/snow depth, solar irradiance, UV index, and weather conditions, I did use key and city to city name for my server `http://api.weatherbit.io/v2.0/forecast/daily?city=${city}&key=${process.KEY}`*

### 3.API Endpoints/Request URLs

 `http://api.weatherbit.io/v2.0/forecast/daily?city=${city}&key=${KEY}`

### 3.Authentication Key

key = `14f0d4e856674b01b84e102604cb999d`
