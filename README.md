# E-Commerce-Back-End

  ![Badge](https://img.shields.io/badge/License-MIT-blue.svg)

## Description

The e-commerce backend, or server-side, is the data access layer that holds products, orders, and customer information. It helps websites operate by processing, storing, and transferring their data to and from the customer-facing side. These actions are carried out by backend components like the web server, application server, and database which make the frontend interactive. They make it so customers can view products, place orders, and manage their purchases using their own devices. I build the back end for an e-commerce site by modifying starter code. I put together a working Express.js API to use Sequelize to interact with a MySQL database. On the terminal in vsCode go to `mysql -u root -p`, entered password, then `SHOW DATABASES;` entered , then `USE ecommerce_db;` entered and exit. Run `npm run seed` to created seed, then run `npm start`, now listening and go to Insomnia.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)
- [Features](#features)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](questions)

## Installation

- Install `.gitignore` and include `node_modules` and `.DS_Store/`, then Install `npm` to acquire inquirer package

- Install `npm install --save mysql2` to use the [MySql2] and `npm i sequelize` to use the [sequelize] to connect your Express.js API to a MySQL database and also `npm i dotenv` the [dotenv] package to use environment variables to store sensitive data.

## Usage

GIVEN a functional Express.js API.
As a user :
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Demo
https://drive.google.com/file/d/10LlEB1JoqkRcsY6GXXgwbdP-UrTugdaR/view

## Credits
- https://github.com/Simon-Xu-Lan

- https://github.com/sam-ngu

- https://github.com/cupacheeno

## License
    This application is covered by the MIT license.

---
## Badges
![Badge](https://img.shields.io/badge/License-MIT-blue.svg)
![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

## Features

n/a

## Contributing

Pull request are welcome, you can make a constribution at the bottom of any docs page to make small changes such as a typo, sentence fix or a broken link. For major changes, please open an issue first to discuss what you would like to change.

## Tests

- In Insomnia shows the application's GET routes to return all categories, all products, and all tags being tested: 
  ![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.]

- In Insomnia shows the application's GET routes to return a single category, a single product, and a single tag being  tested: 
  ![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”]

- In Insomnia shows the application's POST, PUT, and DELETE routes for categories being tested:
  ![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”]

## Questions

If you have any question, Email me at: djaja@iinet.net.au 

Find me on GitHub: [B-smd](https://github.com/B-smd)   









