# E Commerce Back End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

## Description
This E Commerce backend takes advantage of Sequelize's powerful ORM library (object relational mapping library) to simplify MySQL queries. Sequelize, is a promise based Node.js ORM (essentially a translator) that works with any dialect of SQL. This allows API's to work with data that spans across multiple related SQL tables.

This application holds the information for the backend of a basic E Commerce system, using Category, Product, and Tag models to create relationships between each to allow for the user to obtain detailed information that would otherwise be complex to code using vanilla MySQL code. The user is also able to perform CRUD operations.

### Screenshot
![Screenshot](/public/assets/images/screenshot.png)

### Project Showcase
Check out a quick video of the [Application ShowCase](https://drive.google.com/file/d/1iVT9oXrX14i7XdoouMw2Sabk2E_Wiq03/view).

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [License(s)](#licenses)
4. [Questions](#questions)

## Installation
Clone the repo and open the project. In terminal, execute the command `npm i`. This will install all the dependencies required for this application to work.

## Usage
Once the dependancies are installed, follow the steps listed below:
1. Rename the `EXAMPLE.env` file to `.env`. Open it and change the contents to match your MySQL login information.
2. Create the database my executing `source db/schema.sql`. Then execute `quit` to exit MySQL.
3. Populate the database with `npm run seed`.
4. Start the server with `npm start`.
5. To access the backend, use a program such as Insomnia to test API routes. This application runs on a local server and the port will be listed once the server starts.

## License(s)
MIT

## Questions
My name is Arslan Tahir, the creator of this project. If you have any issues, comments, concerns, or questions regarding this project, feel free to contact me at tahir.arslan@gmail.com.

If you would like to check out my other projects, feel free to explore my !(GitHub Page)[https://github.com/tahir-arslan/].
    