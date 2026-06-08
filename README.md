Celestial Bodies Database

This repository contains the database schema and data for the Celestial Bodies Database project, completed as part of the freeCodeCamp Relational Database Certification.
Project Overview

The project involves designing a PostgreSQL database to model celestial entities, demonstrating proficiency in relational data structures, integrity constraints, and data manipulation.
Database Schema

The database consists of five interrelated tables:

    galaxy: Base entity containing galactic information.

    star: Stellar data, linked to galaxies via foreign keys.

    planet: Planetary data, linked to stars.

    moon: Satellites of planets, linked to planets.

    asteroid: Additional celestial body tracking.

Technical Details

    Database System: PostgreSQL

    Key Constraints: Implemented Primary Keys (SERIAL), Foreign Keys, UNIQUE constraints, and NOT NULL requirements.

    Data Types: Utilized a variety of SQL types including VARCHAR, TEXT, INT, NUMERIC, and BOOLEAN.


## Usage
To restore the database on your local machine using the provided dump file:
```bash
psql -U <username> < universe.sql







    
