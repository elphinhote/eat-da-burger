# eat-da-burger



## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [License](#license)
* [Contributors](#contributors)
* [Questions](#questions)

## Description
Eat-Da-Burger a restaurant app that lets users input the names of burgers they'd like to eat.
Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.


Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.


Your app will store every burger in a database, whether devoured or not.

## Installation Instructions
Npm install express, express handlebars, MySql, and create database with JawsDB.  Use Heroku to deploy.

## Usage
 The application has a directory structure.  In Heroku use JawsDB for MySql.
 
* ├── conf
* │   ├── connection.js
* │   └── orm.js
* │ 
* ├── controllers
* │   └── burgers_controller.js
* │
* ├── db
* │   ├── schema.sql
* │   └── seeds.sql
* │
* ├── models
* │   └── burger.js
* │ 
* ├── node_modules
* │ 
* ├── package.json
* │
* ├── public
* │   └── assets
* │       ├── css
* │       │   └── burger_style.css
* │       └── img
* │           └── burger.png
* │   
* │
* ├── server.js
* │
* └── views
*    ├── index.handlebars
*   └── layouts
*       └── main.handlebars

##Use Add-on JawsDB-MySql from Heroku  

![image](https://user-images.githubusercontent.com/65749636/113367321-88464b00-9310-11eb-89a5-8c96f184d0e9.png)



![image](https://user-images.githubusercontent.com/65749636/113367047-dad33780-930f-11eb-94af-b5e45ac8667a.png)


![image](https://user-images.githubusercontent.com/65749636/113369081-423fb600-9315-11eb-8131-13b7de39e29e.png)



## Technologies Used

* Express
* Handlebars
* MySql
* JawsDB MySql
* Heroku
* Node.js

## License
ISC

<img src="https://img.shields.io/badge/LICENSE-isc-green"/>


## Contributors
Eva Wang

## Questions
Contact me:
Email: [elphinhote@yahoo.com](elphinhote@yahoo.com)

Github: https://github.com/elphinhote/eat-da-burger

Deployed App:  https://evening-eyrie-60267.herokuapp.com/

