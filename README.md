# E-commerce Back End Object Relational Mapping (Module 13)
![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

## Description
Our challenge was to build the back end for an e-commerce site. I took a working Express.js API and configured it to use Sequelize to interact with a MySQL database. The app displays the creation of mySQL database with models and associations. API Routes performs RESTful CRUD operations that are demonstrated in the walk through videos.

## User Story
AS A manager at an internet retail company</br>
I WANT a back end for my e-commerce website that uses the latest technologies</br>
SO THAT my company can compete with other e-commerce companies</br>

## Acceptance Criteria
GIVEN a functional Express.js API</br>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file</br>
THEN I am able to connect to a database using Sequelize</br>
WHEN I enter schema and seed commands</br>
THEN a development database is created and is seeded with test data</br>
WHEN I enter the command to invoke the application</br>
THEN my server is started and the Sequelize models are synced to the MySQL database</br>
WHEN I open API GET routes in Insomnia for categories, products, or tags</br>
THEN the data for each of these routes is displayed in a formatted JSON</br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia</br>
THEN I am able to successfully create, update, and delete data in my database</br>

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Contact](#Contact)

## Installation 
The user should clone the repository from GitHub. </br>
This application requires Node.js, Express.js, and Sequelize.</br> 
To connect to the database: 
- run ` mysql -u root -p ` and enter password from .env file. 
- Then source the schema.sql. 
- To seed the file run `npm run seed`. 
- Finally to connect to the server run `npm start`.

## Usage
The app allows the user to view, add, edit, and delete categories, products, and tags.</br>

Video showing MySQL walk through via [GeForce Experience](https://drive.google.com/file/d/1Ra--oaesanKtlcCeHPw5rQIYPSiWIHUl/view)<br>
Video walk through of the API routes and Insomnia via [GeForce Experience](https://drive.google.com/file/d/10SBAJdQ2QzU-vUTpl44zhLU5Fr9n9mzT/view)<br>

## License 
This project is license under MIT

## Contributing 
Contributors should read the installation section. 

## Tests
There are no tests for this application. 

# Contact
- [GitHub](https://github.com/viakeegan 'GitHub')
- [Email](mailto:viakeegan@gmail.com 'Email')
- [Repo](https://github.com/viakeegan/ecommerce-backend-13 'Repo')
