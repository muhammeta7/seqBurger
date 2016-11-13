# Eat-A-Burger

A template for an express server using a MySQL localhost connection and the handlebars file structure

### Overview

Brief Description of Project 

### Getting Started

heroku link: type link here


## Technologies used (fill in with applicable technologies)
- Node.js
- npm express (https://www.npmjs.com/package/express)
- npm body-parser (https://www.npmjs.com/package/body-parser)
- npm method-override (https://www.npmjs.com/package/method-override)
- npm handlebars (https://www.npmjs.com/package/handlebars)
- npm express-handlebars (https://www.npmjs.com/package/express-handlebars)
- npm mysql (https://www.npmjs.com/package/mysql)
- npm sequelize (https://www.npmjs.com/package/sequelize)

### Prerequisites

```
See package.json
```
 

## Directory Structure

#### MVC File Layout

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── burger_style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars

```

#### Sequelize MVC File Layout

```
.
├── config
│   └── config.json
│ 
├── controllers
│   └── burgers_controller.js
│
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │  
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars

```


## Built With (fill in with applicable fields)

* Node
* Sequelize
* Terminal/Gitbash
* Sublime Text - Text Editor

## Authors

* **Muhammet Aydin** - *Sequelize/Node/Express* - [Muhammet Aydin](https://github.com/muhammeta7/burger)

## Acknowledgements

Dan and Nate for all the help