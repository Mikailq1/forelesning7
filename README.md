# PostgreSQL, JDBC og Java

* [x] Installing postgresql
* [x] Accessing postgresql fra Intellij
* [x] Access database from Java
  * Add dependency on Postgresql driver with Maven
* [ ] Test: retrieving an inserted person from database
  * Add AssertJ testing library with Maven
* [ ] Test: list people by last name
  

## Database

  create user person_dbuser with password '/Rhx2\bZ(G>9!F4B6';

  create database person_db with owner person_dbuser

  create table people (
  id serial primary key,
  first_name varchar(100),
  last_name varchar(100)
  );

insert into people(first_name, last_name) values ('Mikail', 'Qureshi')