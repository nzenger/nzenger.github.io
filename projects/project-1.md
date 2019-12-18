---
layout: project
type: project
image: images/database.jpg
title: Database for ICS212
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-04-22
labels:
  - C
  - Unix
  - SCCS
summary: Created a database which would store, receive, and retrieve data.
---
A Database project that was written in the C programming language for ICS212. The main goal and purpose of this program is to stores records containing a persons name, account number, and address and store them to be retrieved or manipulated later. The options for this database are adding a new record to the database allowing the user to enter the new information which is then added and sorted into the database. The next database option is to print a specific record which is found with an account number or the name of the person on record. The last features of the database is being able to reverse your list of records and delete specific records based on their account no. This program was designed to be used in Unix and utilizes the SCCS(Source Code Control System) which protects the code from alterations of other parties and allows the programmer to archive previous iterrations of source code created.

I wrote all the code for the databse myself and thoroughly tested the program so to ensure that the dtabase behaved and performed the tasks of storing, searching, and deleting correctly. I also implemented a debugger that I wrote into the source code so that I could check values and locations of the variables being passed around and to check the parameters of function calls withing the code while it's running. This project was a simple but effective database that implemented SCCS in Unix.

Here is the repository for the project: https://github.com/nzenger/ICS212-Project-1
