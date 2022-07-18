# CRUD-task

# DEPENDENCIAS
npm i express mysql express-handlebars express-myconnection
npm i nodemon

# CREAR DB
CREATE DATABASE IF NOT EXISTS crud-task;

# CREAR TABLA EN LA DB
CREATE TABLE tasks (
	id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
  title VARCHAR (100),
  description VARCHAR (100)
);
