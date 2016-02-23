# Weather_App
Simple NodeJS weather application.

###### Feature
* Uses [openweathermap](http://openweathermap.org/current) api to get the realtime weather for your city.
* Can manually provide the your desired location.

  ```
  node app.js -l 'Nepal'
  ```
* Uses [ipinfo](http://ipinfo.io/) to get your location automatically if not given manually.

  ```
  node app.js
  ```

* This application uses;
> * uses yargs to take the arguments from user,
> * Async function calls,
> * Callback functions,
> * Requiring local files,
> * Used promises for async programming.

###### Aurthor: [Rajan Maharjan](http://mrajan.com.np/)
