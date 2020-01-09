# FrontEnd Developer Task - Simple Weather App

**A simple, Javascript based task checking your frontend development skills.**


### Overview

You are exepected to develop a **single-page weather application** for top 3 cities in Turkey (Istanbul, Ankara and Izmir).  Users of the app can see both the current weather condition and 5-day forecasting of the city they choose.

* This is a frontend only application, there is no backend development needed. 
* There is no authentication needed.
* When a user first enters the app, the current city is Istanbul.
* Users can select the city using the drop down menu of the app. The app remembers the latest choice of the users (within same browser). 
* The application shows: 
	* *MeasureTime, RealFeelTemperatureShade, WeatherIcon, RealFeelTemperature, Temperature, WeatherText*, 
	* Additional Information for the weather (UV Undex, Wind, Wind Gusts etc. ) ,
	* 5 Days Forecast of temperature
for current city.
* You may check layout section for details.

### Layout

A sample layout for the application is shown below. You are free to make changes in the layout. You may use any styling template you want. (Colors, fonts, icons etc.)

![](layout.png?raw=true)

### API

A sample data is gathered from AccuWeather, and hosted in this repository.  You may want to check AccuWeather API for data description and documantation. 

You may access the data using github endpoints as below.

#### Current Weather API

Ankara :  [https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/ankaraCurrentWeather.json](https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/ankara5DaysWeather.json)

Istanbul : [https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/istanbulCurrentWeather.json]

Izmir : [https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/izmirCurrentWeather.json]


#### 5 Days Forecast Weather API

Istanbul : [https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/istanbul5DaysWeather.json](https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/ankara5DaysWeather.json)

Ankara : [https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/ankara5DaysWeather.json](https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/ankara5DaysWeather.json)

Izmir : [https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/izmir5DaysWeather.json](https://raw.githubusercontent.com/ardatasci/frontend-recruitment-task/master/ankara5DaysWeather.json)

#### Icons

The data includes "icon" fields. You can use icons as below :

```
https://developer.accuweather.com/sites/default/files/{icon}-s.png
```

**Ex:** 

For the icon 01:

 (https://developer.accuweather.com/sites/default/files/01-s.png) 
![enter image description here](https://developer.accuweather.com/sites/default/files/01-s.png)



### Requirements 

* The application will be developed using **Vue.js**.
* All the charts in the application will be rendered using **Highcharts** libraries https://www.highcharts.com/
* **Pay attention** to things like good usage of Vue.js, Javascript and Highcharts, code separation, readability, maintainability, and error handling as well as lazy loading, caching and storage.
* The layout shall be **Responsive**.
* All the work done shall be documented. A user guide (How to run ?) shall be included in the documentation.


### Submission

You will commit your code to a public github repository. (If you prefer a private repository, you may grant access to user *ardatasci*)

