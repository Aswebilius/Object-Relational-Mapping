# E-commerce Back End

The purpose of this assignment was to work with backend technologies to create and seed a database for an E-commerce site. This challenge also was meant for us to practice our databse SQL skills, get more experience with Sequelize, and to help us further develop our skills in writing code for GET, POST, and DELETING API routes.

To use this assignment you will need to have Express.js installed, Mysql2, and Sequelize. Open the integrated terminal and type "npm i express", "npm mysql2", and lastly, "npm sequelize." Once the packages are installed type in "mysql -u root -p" when prompted for a password it will be 112990. Then you will type 'SOURCE C:\Users\Austin\desktop\challenges\Object-Relational-Mapping\db\schema.sql" after this will type "USE ecommerce_db;". Exit mysql and open the integrated terminal. Once there you will need to type "npm run seed" to seed the database. Then type "npm start" to start the server. 

Walkthrough Video URLs:

https://drive.google.com/file/d/16HsFq3mIaiR8_oQ5X9xDGYI2SwjP2le_/view

https://drive.google.com/file/d/1HlACwJtpDQ6Taa8zogCzrRmHhvOc_81H/view


USER STORY:
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

ACCEPTANCE REQUIREMENTS:
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