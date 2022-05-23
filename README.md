# java-mysql-g5
Proyectos que muestran la conexion desde a java a mysql usando proyectos maven


Se requiere la instalacion de mysql-server, entrar con el usuario root
y correr los siguientes comandos:

CREATE USER 'usuariotabla'@'localhost' IDENTIFIED BY 'pass1234'; 
GRANT ALL PRIVILEGES ON *.* TO 'usuariotabla'@'localhost' WITH GRANT OPTION; 
CREATE DATABASE datos;  
use datos;  
CREATE TABLE alumnos (id INT, nombre VARCHAR(20), apellido VARCHAR(20), matricula VARCHAR(10)); 
INSERT INTO alumnos VALUES (0,'Manuel','Mendoza','21530324'); 
