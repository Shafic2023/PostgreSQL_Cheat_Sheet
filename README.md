# PostgreSQL_Cheat_Sheet
SQL Querying Data Cheat Sheet
## Purpose:

This SQL cheat sheet for querying a relational database  is based on PostgreSQL tutorial for the famous *dvd rental database* that comes with PostgreSQL and can be found ![here](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-select/).

## What is PostgreSQL?

Let’s start with a simple question: what is PostgreSQL?

PostgreSQL is an advanced, enterprise-class, and open-source relational database system. PostgreSQL supports both SQL (relational) and JSON (non-relational) querying.

PostgreSQL is a highly stable database backed by more than 20 years of development by the open-source community.

PostgreSQL is used as a primary database for many web applications as well as mobile and analytics applications.

PostgreSQL’s community pronounces PostgreSQL as /ˈpoʊstɡrɛs ˌkjuː ˈɛl/.

## **History of PostgreSQL**
The PostgreSQL project started in 1986 at Berkeley Computer Science Department, University of California.

The project was originally named POSTGRES, about the older Ingres database which was also developed at Berkeley. The goal of the POSTGRES project was to add the minimal features needed to support multiple data types.

In 1996, the POSTGRES project was renamed to PostgreSQL to clearly illustrate its support for SQL. Today, PostgreSQL is commonly abbreviated as Postgres.

Since then, the PostgreSQL Global Development Group, a dedicated community of contributors continues to make the releases of the open-source and free database project.

Originally, PostgreSQL was designed to run on UNIX-like platforms. And then, PostgreSQL evolved to run on various platforms such as Windows, macOS, and Solaris.

** Common Use Cases of PostgreSQL**

The following are the common use cases of PostgreSQL.

1)  A robust database in the LAPP stack
LAPP stands for Linux, Apache, PostgreSQL, and PHP (or Python and Perl). PostgreSQL is primarily used as a robust back-end database that powers many dynamic websites and web applications.


3)  General-purpose transaction database
Large corporations and startups alike use PostgreSQL as the primary database to support their applications and products.


5)  Geospatial database
PostgreSQL with the PostGIS extension supports geospatial databases for geographic information systems (GIS).


** Language support**

PostgreSQL supports the most popular programming languages:

* Python
* Java
* C#
* C/C+
* Ruby
* JavaScript (Node.js)
* Perl
* Go
Tcl
### PostgreSQL feature highlights

PostgreSQL has many advanced features that other enterprise-class database management systems offer, such as:

1 User-defined types

2 Table inheritance

3 Sophisticated locking mechanism

4 Foreign key referential integrity

5 Views, rules, subquery

6 Nested transactions (savepoints)

7 Multi-version concurrency control (MVCC)

8 Asynchronous replication

9 The recent versions of PostgreSQL support the following features:





I will use the DVD rental database to demonstrate the features of PostgreSQL. The DVD rental database represents the business processes of a DVD rental store. The DVD rental database has many objects, including:
•	 15 tables

•	 1 trigger

•	 7 views

•	 8 functions

•	 1 domain

•	 13 sequences

DVD Rental ER Model


There are 15 tables in the DVD Rental database:
•	actor – stores actor data including first name and last name.

•	film – stores film data such as title, release year, length, rating, etc.

•	film actor – stores the relationships between films and actors.

•	category – stores film’s categories data.

•	Film category- stores the relationships between films and categories.

•	store – contains the store data including manager staff and address.

•	inventory – stores inventory data.

•	rental – stores rental data.

•	payment – stores customer’s payments.

•	staff – stores staff data.

•	customer – stores customer data.

•	address – stores address data for staff and customers.

•	city – stores city names.

•	country – stores country names.

## Download the PostgreSQL sample database 

You can download the PostgreSQL DVD Rental sample database via the following link: Download DVD Rental Sample Database The database file is in zip format ( dvdrental.zip) so you need to extract it to  dvdrental.tar before loading the sample database into the PostgreSQL database server.

To practice SQL, Install PostgreSQL on Windows by following this step-by-step guide

![here](https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/)- * For Windows*

![here](https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql-macos/) - * For Mac*

![here](https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql-linux/) - * For Linux*

A Script of the code is attached in the files section of the Repo!
