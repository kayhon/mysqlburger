# mysqlburger (Eat-da-burger!)

MySqlBurger (Eat-Da-Burger!) is a customizable restaurant app that lets users 'Order Burgers From Custom Menu' and/or input the names of burgers they'd like to eat.<br>


![User-Menu-View-burg00-jpg](https://github.com/kayhon/mysqlburger/blob/master/images/burg00.jpg)<br>

![User-Menu-View-burg0-jpg](https://github.com/kayhon/mysqlburger/blob/master/images/burg0.jpg)<br>

## App Features

-After a user submits a burger name, the app will display the new burger on the left side of the menu/page, waiting to be ordered/devoured.<br>
-Each burger in the waiting area also has a 'Devour it!' button. When the user clicks it, the burger will move to the right side of the page where it says'Burgers Previously Ordered/Devoured!'.<br>
-You have the option to re-order the same burger you already ate/ordered by clicking the 'Devoured/Eat-Again' Button and it pops back to the available side(on the left). <br>
-When you 'Add a Burger' you can pick which side it goes to.
-The User also has the option to delete any burger anywhere & anytime on the screen.<br>
-Each Burger maintains a unique 'ID', wherever it is, because the app will store each burger in a database, whether devoured or not.<br>


### Technologies Used

* Node.js
* MySql
* Express
* Handlebars


#### Directory structure / File Setup 
#### (Model View Control - 'MVC Design')

All the files and directories have the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── burger_style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
