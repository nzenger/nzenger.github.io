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
summary: Created a database which would store, receive, and retrieve data.
---
A Database project that was written in the C programming language for ICS212. The main goal and purpose of this program is to stores records containing a persons name, account number, and address and store them to be retrieved or manipulated later. The options for this database are adding a new record to the database allowing the user to enter the new information which is then added and sorted into the database. The next database option is to print a specific record which is found with an account number or the name of the person on record. The last features of the database is being able to reverse your list of records and delete specific records based on their account no. This program was designed to be used in Unix and utilizes the SCCS(Source Code Control System) which protects the code from alterations of other parties and allows the programmer to archive previous iterrations of source code created.



Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).


