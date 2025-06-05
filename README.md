# Celestial Bodies Database 🌌

## English 🇺🇸

This is a PostgreSQL database project made for the freeCodeCamp Relational Database course.  
The goal of the project was to build a database of galaxies, stars, planets, and moons.

I created five tables: `galaxy`, `star`, `planet`, `moon`, and `observation`.  
Each table has a primary key, some constraints like `NOT NULL` and `UNIQUE`, and foreign keys that connect everything properly.  
I used data types like `INT`, `NUMERIC`, `TEXT`, and `BOOLEAN` as required.  

The `observation` table was added as a way to store extra details, like public notes or comments about the celestial bodies.  
It uses `TEXT` and links to the `moon` table with a foreign key.

This project was developed and tested in the Gitpod virtual environment provided by freeCodeCamp.  
The file `universe.sql` contains the full database schema and some inserted data to complete all project tests.

---

## Español 🇪🇸

Este es un proyecto de base de datos PostgreSQL hecho para el curso de Bases de Datos Relacionales de freeCodeCamp.  
El objetivo era construir una base de datos sobre galaxias, estrellas, planetas y lunas.

Creé cinco tablas: `galaxy`, `star`, `planet`, `moon` y `observation`.  
Cada tabla tiene su clave primaria, restricciones como `NOT NULL` y `UNIQUE`, y claves foráneas para mantener la conexión entre todas.  
Usé tipos de datos como `INT`, `NUMERIC`, `TEXT` y `BOOLEAN`, tal como se pedía.

La tabla `observation` se agregó como una forma de guardar detalles adicionales, como notas públicas u observaciones sobre los cuerpos celestes.  
Usa el tipo `TEXT` y se conecta con la tabla `moon` mediante una clave foránea.

El proyecto se desarrolló y probó en el entorno virtual de Gitpod proporcionado por freeCodeCamp.  
El archivo `universe.sql` contiene todo el esquema de la base de datos y los datos insertados para pasar todas las pruebas del proyecto.
