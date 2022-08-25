WeatherApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.3.

Development:

- find resources you will need, pictures and icons for application
- make angular project in cmd with ng new "name of the project"
- delete everything from app.component.html and design it as you wish
- in styles.css design and position everything for your application

- for api we will use RapidAPI site (you need to make an account/its free)
- https://rapidapi.com/KirylBokiy/api/openweather43/ this is the api i was using (it has limit 20 requests per day)
- in app folder make services folder/ then generate service with ng g s weather
- connect enviroment with api with host name and key name
- test endpoint so we can formate json data we generated (make sure data is right format)
- then convert generated data in typescript
- make models folder in app with one file "weather.model.ts" which will have previously generated data in typescript
- call the data and parameters to app.component.html
