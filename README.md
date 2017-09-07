# Eat Da Burger

## Description
 Eat Da Burger is a full-stack application, utilizing node.js, express.js, handlebars.js and a mysql database, to simulate an ordering a burger and then devouring it. This application could easily be modified for commercial use for an ordering and completion application. Eat Da Burger allows the user to order from a prefilled list or add a specialty burger of their choosing.  It then adds the burger to the "Burgers to eat" column. Once a burger is devoured it is moved to the "Burgers already eaten" column. All of the data is stored and updated in the mysql database.

## Important Details
This application requires node.js so please be sure to have that installed or it will not work.
Before running the application it is necessary to navigate to the folder containing all of the application files and run the following command in the terminal: **npm install**
This will install all the packages and their necessary versions according to the package.json file.

## Utilization
In order to run Eat Da Burger the user will need to: 
1. Choose from the "Burgers to eat" column by clicking on "Devour it". This will move the selected burger to the "Burgers already eaten" column.
2. In order to add a specialty burger the user will need to enter the burger name in the text area and click "submit". This will add the specialty burger to the "Burgers to eat" column and the user can then "devour it".


