## Project Name

Wildlife Tracker App

## This project is a Wildlife Tracker App, Version Date: 20th June 2023

## By **Peter Kenneth**

## Project Description
Wildlife Tracker is an app that allows one to record sightings of various animals.

It allows one to create rangers,locations,animals and sightings.It also allows you to view rangers locations sightings and animals.

One can also view sightings a ranger has made and locations with the sightings that have occurred in them

## Setup/Installation Requirements
* Fork this repo
* Clone this repo
* Open terminal
* Navigate to appropriate directory using the cd command
* Type in the command git clone and paste the url of clone and then press enter

## Setup Requirements for Database
* In PSQL:
* CREATE DATABASE wildlife_tracker;
* \c wildlife_tracker
* CREATE TABLE animals (id serial PRIMARY KEY, name varchar,type VARCHAR,health VARCHAR,age VARCHAR);
* CREATE TABLE locations (id serial PRIMARY KEY,name VARCHAR);
* CREATE TABLE locations_sightings (id serial PRIMARY KEY,location_id INT,sighting_id INT);
* CREATE TABLE rangers (id serial PRIMARY KEY,name VARCHAR,badge_number VARCHAR);
* CREATE TABLE rangers_sightings (id serial PRIMARY KEY,ranger_id INT,sighting_id INT);
* CREATE TABLE sightings (id serial PRIMARY KEY,animal_id INT,ranger_id INT,location_id INT,time TIMESTAMP);
* CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;
## In order to run locally
* Go to DB.class in main/java folder and make necessary changes
* Go to DatabaseRule in test/java folder and make necessary changes

## Known Bugs

There are no known bugs on this project.

## Technologies Used

* Java
* Heroku
* CSS
* HBS

## GITHUB URL Link

To view project click: https://github.com/PKenneth01/Wildlife-Tracker.git

### License

_The License used is GPL_

Copyright (c) 2023 **Peter Kenneth**# Wildlife-Tracker
