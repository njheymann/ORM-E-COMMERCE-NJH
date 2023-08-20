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

## Screenshots 
NOTE: These images depict the same functionality as Category and Tags request. Please refer to walkthrough video  
to view the full functionality.

![Screenshot 2023-08-21 084714](https://github.com/njheymann/ORM-E-COMMERCE-NJH/assets/125000756/47a05a58-e443-42e5-bd81-76030acfb704)
![Screenshot 2023-08-21 084730](https://github.com/njheymann/ORM-E-COMMERCE-NJH/assets/125000756/190e6ebc-3151-4504-aa84-74b042d785d8)

![Screenshot 2023-08-21 084809](https://github.com/njheymann/ORM-E-COMMERCE-NJH/assets/125000756/e0214857-9547-4601-b07d-3ab6de8a8256)

![Screenshot 2023-08-21 084822](https://github.com/njheymann/ORM-E-COMMERCE-NJH/assets/125000756/6b32a152-0873-49c0-8398-ce4241ee66a8)
![Screenshot 2023-08-21 084834](https://github.com/njheymann/ORM-E-COMMERCE-NJH/assets/125000756/94e85e39-a25e-4ed9-8d8c-9e65a5f3eeda)

## Walkthrough Video
MySQL connection:  
https://drive.google.com/file/d/1y0eM5Atl6c_8qVp9aCfcFV5zrJyEP9If/view

Server connection and how to use app:  
https://drive.google.com/file/d/194ZbR_u2tkV9mG-xrhlgV8Yq_HM1MEIg/view

## Repository URL
https://github.com/njheymann/ORM-E-COMMERCE-NJH
