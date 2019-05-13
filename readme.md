# NSU Offered Course Lists

This is a MySQL database of North South University's offered course lists

* Summmer 2017
* Fall 2017
* Spring 2018
* Summer 2018
* Fall 2018
* Fall 2019

## Getting Started

* Install [Xampp](https://www.apachefriends.org/index.html)
* Start Apache and MySql from Xampp
* Open any browser and go to http://localhost/phpmyadmin
* Create a new Database and import the course_list.sql file

### Prerequisites

* MySQL

### Usage

* Select your database from phpmyadmin and run your sql query

* *For example*

```
SELECT Time, Section 
From `course list` 
WHERE Faculty = 'RJP' and Course = 'CSE215' and Semester = '183' 
```
This query finds you the time and section for CSE215 course taken by Dr Rajesh Palit in the semester 183.