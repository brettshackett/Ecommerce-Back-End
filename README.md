# E-commerce Back End

## Description
Created a MySQL database to track products and categories for an ecommerce company, giving them the ability to add, change, and delete items from the database using Insomnia. 

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Testing](#testing)


## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
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

## Testing

- GET all products, categories, and tags within the database.
(./images/GET_all.gif)


-GET 1 product, category, tag with id of 1.
(./images/GET_1.gif)

-POST, PUSH, and DELETE from the database.
(./images/POST_PUSH_DELETE.gif)
