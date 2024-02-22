A CRUD application (Create, Read, Update, Delete) using Node.js, Express, MySQL & EJS Templating Engine. 

Here are the steps to use it:

1. Download it
2. Extract it
3. Create Database and table
4. Connect Node js Crud app with mysql database by editing lib/db.js
5. Start Application Server by running npm start
6. Open browser and type http://127.0.0.1:3000/customers


Sql Query to create Database:

CREATE TABLE customers (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL
);

Read detailed guide = [Node.js Express CRUD Example with MySQL](https://www.tutsmake.com/first-crud-node-express-js-mysql-example?crud-operation)https://www.tutsmake.com/first-crud-node-express-js-mysql-example?crud-operation
