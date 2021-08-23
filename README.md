# 13-ecommerce-back-end
## Table of Contents
* [General info](#general-info)
* [Recording](#screenshot)
* [Technologies](#technologies)
* [Setup](#setup)
* [User Story](#User-Story)
* [Acceptance Criteria](#Acceptance-Criteria)

## General Info
The back end for an e-commerce site


## Recording
Recording of the API working can be found here: https://drive.google.com/file/d/1R1XJq_DoZ_Uy1WDKKf7YbqmWXYNhIZlD/view

## Technologies
Project is created with:
* Nodejs
* Express
* Sequelize
* MySQL

The example was deployed on Heroku.

## Setup
To setup the dependencies required for this project, copy the contents and run `npm install` in the root directory.

Once setup, to install the schema execute the commands found in `db\schema.sql`.

To run seed data run:
`npm run seed`

To run the server run:
`npm start`

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
