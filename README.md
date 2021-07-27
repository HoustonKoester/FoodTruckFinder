# Food Truck Finder 

### Project discription and overview

This project is a food truck finder application to find and display information about food trucks in Austin Texas

Users can login to the application and using the google maps API to search through food trucks located in Austin Texas

A user can also choose to apply to have their own food truck added to the map using the food truck application feature.

### List of included features
- A user can login/logout
- A user can view the app dashboard
- A user can submit a food truck application
- A user can view information about the food trucks by clicking on the map markers
- A user can view the menu, hours of opperation, and the ratings and reviews for the food truck that they clicked on

### Future development
- Allow users to submit their own reviews of the food truck
- User the Yelp API to get reviews from yelp along with the reviews displayed on our application
- Develop a manager and food truck owner profile so that food truck owners/website managers can view and edit food truck information


### List of used technologies
- Java
- Spring Framework
- Angular 2+
- HTML
- CSS
- Hibernate
- Log4J
- JUnit
- SQL
- TypeScript

### How to setup project
Inside the project folder you must add information to 2 files to be able to have the project work correctly. 

You must add in your database information to the hibernate.cfg located in FoodTruckFinder/src/main/resources/hibernate.cfg

You must also add in the google maps API key located in the food-truck-finder/src/app/dashboard on line 22.

The databases must be setup in accordance with how data is accessed throughout the rest of the project.

To start the application you can open both of the projects individually (food-truck-finder as a angular project and FoodTruckFinder as a Maven project) the base ports for the project are localhost4200 for the angular project and localhost8080 for the Maven/backend.

###### Project Created By: Houston Koester, Edwin Munoz, Isabel Sanchez, and Peter Fowler
