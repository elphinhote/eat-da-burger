# eat-da-burger

Eat-Da-Burger is an app users input with their favorite burgers. 

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [License](#license)
* [Contributors](#contributors)
* [Questions](#questions)

## Description
Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.
Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.
Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.
Your app will store every burger in a database, whether devoured or not.

![image](https://user-images.githubusercontent.com/65749636/113531136-c9db2e00-957c-11eb-9812-0528a386a939.png)

## Installation Instructions
Install npm install with dependencies.  Use JAWSDB and MYSQL deploy with Heroku.

## Usage
 The application's directory is as follows.
 

.
* ├── config
* │   ├── connection.js
* │   └── orm.js
* │ 
* ├── controllers
* │   └── burgers_controller.js
* │
* ├── db
* │   ├── schema.sql
* │   └── seeds.sql
* │
* ├── models
* │   └── burger.js
* │ 
* ├── node_modules
* │ 
* ├── package.json
* │
* ├── public
* │   └── assets
* │       ├── css
* │       │   └── burger_style.css
* │       └── img
* │           └── burger.png
* │   
* │
* ├── server.js
* │ 
* └── views
*   ├── index.handlebars
*  └── layouts
*       └── main.handlebars

## Add-on from Heroku creates username, password, and database for use with JAWSDB and MYSQL.

![image](https://user-images.githubusercontent.com/65749636/113531429-9d73e180-957d-11eb-92c0-1194afeeaa90.png)

![image](https://user-images.githubusercontent.com/65749636/113531379-7a493200-957d-11eb-86db-0a13d022379a.png)

![image](https://user-images.githubusercontent.com/65749636/113530542-263d4e00-957b-11eb-831f-e47479332ec8.png)

![image](https://user-images.githubusercontent.com/65749636/113529844-6e5b7100-9579-11eb-9dd5-37e07d793404.png)


## Technologies Used
* Express
* Express-handlebars
* MySql
* JaAWSDB
* Heroku


## License
ISC

<img src="https://img.shields.io/badge/LICENSE-isc-green"/>


## Contributors
Eva Wang

## Questions
Contact me:
Email: [elphinhote@yahoo.com](elphinhote@yahoo.com)

Github: https://github.com/elphinhote/eat-da-burger/

Deployed App: https://evening-eyrie-60267.herokuapp.com/ (App did not deploy, need to tweak to deploy)
