# redesigned-umbrella-module-13-challenge
Module 13 Challenge

## Description

This web application allows the user to view and manipulate a database for an e-commerce platform.  Data can be viewed and modified using Insomnia and HTML routes.  The data revolves around the categories, products, and tags for the items on sale.

## Installation

This application will require Node.js to use.  It will also require running "npm install" to pull in the express, mysql2, sequelize, and dotenv libraries into your environment.

## Usage

Use Insomnia to send fetch calls to various routes depending on what you wish to accomplish.  To view all cateories, products, or tags use a GET route with http://localhost:3001/api/option_name where option name is categories, products, or tags.  Additionally, you can enter an ID number to view one item from any of those options by using the following GET route: http://localhost:3001/api/option_name/ID_number.

You can also use POST, PUT, and DELETE routes to modify data from the database.

To add a new item use POST route http://localhost:3001/api/option_name and pass in JSON.
To update existing item use PUT route http://localhost:3001/option_name/ID_number and pass in JSON.
To delete existing item use DELETE route http://localhost:3001/option_name/ID_number.

E-Commerce Video Demonstration: 

## Credits

N/A

## License

N/A