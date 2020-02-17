# EventTrackerJS

## Overview

An index html and a javascript file were added to the JPA - Spring Boot project. 
The js file uses an XMLHttpRequest to access the SQL database. 

The following image is a sreenshot of the overall CRUD application. A user can create a new event, update an event, or delete and event. 
There are also js functions that total all of the costs and totals all of the gallons. 

<img src="https://github.com/sgmerwin/EventTrackerJS/blob/master/screenshot.png" width="300" height="800">

The following is a screenshot of a js function that lists all of the events in the SQL database. 
There is an interesting block of code in this. A series of buttons are created with the same class.
In a for loop each button is given a unique id and this unique id is referenced in a function call with a this.id
parameter. 

<img src="https://github.com/sgmerwin/EventTrackerJS/blob/master/listall.png" width="300" height="800">




