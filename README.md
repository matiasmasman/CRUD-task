# CRUD-task
Aplicacion de tareas para crear, leer, actualizar y eliminar datos. Las tecnologias utilizadas son: javascript, express, mysql y handlebars como motor de renderizado en HTML

# GENERAR PROYECTO
npm init --yes

# DEPENDENCIAS
npm i express mysql express-handlebars express-myconnection
npm i nodemon

# INICIAR SV
npm run dev

# CREAR DB
CREATE DATABASE IF NOT EXISTS crud-task;

# CREAR TABLA EN LA DB
CREATE TABLE tasks (
	id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
  title VARCHAR (100),
  description VARCHAR (100)
);
