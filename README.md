# ORM E-COMMERCE BACK END ASSIGNMENT NJH

## USER STORY
AS A manager of a retail company website  
I WANT a back end e-commerce website that uses the latest technologies  
SO THAT my company can compete with other e-commerce companies  

## Acceptance Criteria  
GIVEN a functional Express.js API  
WHEN I add my database name, MYSQL username, and MYSQL Password to an environment variable file  
THEN I am able to connect to a database using Sequelize  
WHEN I enter schema and seed commands  
THEN a live database is created and is seeded with the test data provided  
WHEN I start the app 
THEN I can use insomnia to view current databases using API GET routes to see categories, products or tags  
WHEN I use the GET routes  
THEN I can view the databases in JSON format  
WHEN I test API POST for categories, products or tags by adding JSON bodies  
THEN I will be given correct error codes telling me of failure or success with the request  
WHEN I test API GET for categories, products or tags  
THEN I will be given correct error codes telling me of failure or success with the request ASWELL as the update data  
WHEN I test API PUT and update a current piece of data   
THEN I will be given correct error codes for success, failures and my data will be updated  
WHEN I test API DELETE for categories, products or tags  
THEN I will be givven correct error codes for success, failures and my chosen data will be deleted  

## Installation
Connect to MySQL
```mysql -u root -p```
```USE ecommerce_db;```

Connect to server
```npm run seed```
```npm start```

