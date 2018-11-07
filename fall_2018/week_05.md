## Last Week's Accomplishments

> Created and inputted some sample data into our PostgreSQL database with a small python program. Have all the Py programs to easily convert csv to be written into the psql database/server.

## This Week's Plan

> Fix up datatypes of columns of the 'fundamentals' table in PSQL, since they were incorrectly assigned (i.e. uuid datatyle instead of string or integer: will be using Py). Read assigned uuid of companies, and link them to all the items in the fundamentals data (Also using Py). Create new code to split up reading/parse and writing data into PSQL server, split up data into manageable chunks, or rewrite in C++. Clean up deprecated/commented-out code in previous Py programs. Hopefully by next week, learn to submit pull request for cleaned up Py code.
 

## Anything Blocking?

> Over the course of the past week, it turned out the columns of the fundamentals table had the incorrect datatypes, so I was pushing an incorrect format into the tables. It was also the case that the Py program was taking too long (disconnecting from the server) to read and write to the PostgreSQL server (Roughly 10 million rows/items.), so I need to find a more efficient way to load all the data in.

## Notes

> N/A.
