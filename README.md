# ECom_SQL
This project aims to build the back end for an e-commerce site using Express.js API and Sequelize to interact with a MySQL database.

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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
## Installation 

1. Clone this repository
2. Navigate to the project directory in your terminal.
3. Install the dependencies.
```md
npm i
```

## Usage 
1. Configure your MySQL database
```md
npm run seed
```
2. Start Server 
```md 
node start 
```
3. The Server will run on `http://localhost:3001`


### Walkthrough Video 



https://github.com/joshjac16/ECom_SQL/assets/130494193/04c595bb-2f3d-4d1b-af79-fb002d2db07e



## Technologies used 

* Express.js 
* Sequelize
* MySQL
