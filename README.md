# Wildlife Tracker

#### By **Jeanine NISHIMWE**
![Alt text](src/main/resources/public/images/demo.png?raw=true "")
## Description

An application that allows Rangers to track wildlife sightings in the area.

## Technologies Used
* Java
* Handlebars
* DB/SQL
* CSS
* Javascript
* HTML


## Installation
* git clone (https://github.com/NJeanine-creator/WildlifeTracker.git) this repository
* cd WildlifeTracker

## SQL
1. Launch postgres
2. Type in psql
##### Run these commands
3. CREATE DATABASE wildlife_tracker;
4. \c wildlife_tracker;
5. CREATE TABLE animals (id serial PRIMARY KEY, name varchar,age varchar, healthy varchar,endangered varchar );
6. CREATE TABLE sightings (id serial PRIMARY KEY, location varchar ,ranger varchar);
7. CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;

## User Requirements

The applications allow users to do the following:
1.Add a new animal
2.Add an endangered animal
3.Add an animal Sighting


## Contact Details

You can contact me on jnishimwe321@daviscollege.com/0780629636


## License

This project is licensed under the MIT Open Source license Copyright (c) 2019. [LICENCE](https://github.com/NJeanine-creator/WildlifeTracker.git/blob/master/LICENCE)

