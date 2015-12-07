# wordpress-plugin-exercise
Outline of WordPress plugin to be created by potential new hire as a way of demonstrating relevant skills.

Description
-----------

* Build a WordPress plugin from scratch that uses the openweathermap API to display weather info for our office locations around the world.
* Write the plugin using PHP5 OOP classes & methods. 
* The plugin should work when activated on WordPress 4.3.
* CSS & aesthetics is not important for the purposes of this exercise, use a default theme like twentyfifteen for page layout
* Expect to walk us through how you approached building the plugin during your interview. 

You will need
-------------

* WordPress 4.3 running on your localhost or at a hosted location we can view during your interview.
* API docs: http://openweathermap.org/current
* You will need to register for an API key (it's free) http://openweathermap.org/appid#get

Requirements
------------

* User facing:

    * Display:
        * The current weather description
        * Current temperature in Farenheit for the selected location
    * User can toggle between all the Motley Fool Office locations around the world:
        * Queensland, Australia
        * London, UK
        * Berlin, Germany
        * Singapore
        * Halifax, Canada
        
* wp-admin plugin settings:
    
    * The plugin should have a settings screen
    * Admin can toggle whether to display temperature in Farenheit or Celsius so that the user-facing website reflects the change

Bonus Points
------------

For extra credit, make the user facing website toggle between office locations without making the page reload. This would require use of Ajax. 


