## Object-Relational Mapping (ORM) Challenge: E-commerce Back End

### Description

*Build the back end for an e-commerce site. Take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.*


### App Demo

- Create Schema and Seed data
- GET routes to return all categories, all products
- GET routes to return a single category, a single product, and a single tag
- POST, PUT, and DELETE routes for categories
- POST, PUT, and DELETE routes for Tags
- POST, PUT, and DELETE routes for products



### User Story


AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies and data
SO THAT my company can operate more streamline like other e-commerce companies
```

### Acceptance Criteria

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

### Instructions on how to run the app

- Add a .env file to the root of the app with the following details

```text
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxx'
```