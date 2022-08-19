# DSCI 513: Databases and Data Retrieval

How to work with data stored in relational database systems or in formats utilizing markup languages. Storage structures and schemas, data relationships, and ways to query and aggregate such data.

## Course Learning Objectives

By the end of the course, students are expected to be able to:

1.  Use an Entity-Relationship (ER) Diagram to determine the entities, relationships, attributes, data types, primary keys, foreign keys,  etc., for a given database application; translate an ER Diagram to a relational database schema.
2.  Write SQL statements to define, query, and update tables in a database.
3.  Write programs containing embedded SQL statements to communicate with and query a database, thereby generating reports requiring more complicated logic and calculations than what is possible via stand-alone SQL.
4.  Write well-formed XML; use XPath and XQuery to write simple queries over an XML repository (i.e., XML database). 
5.  Explain basic concepts of the Map Reduce paradigm. 

## Assessments

Labs

|   | Lab topic   |  Due Date |
|------|-----------|-----------|
| [1](labs/lab1.md)<sup>*</sup> |  Intro to SQL. Embedded SQL programming in R | 2018-11-17|
| [2](labs/lab2.md) | ER diagrams. Embedded SQL programming in Python. | 2018-11-24 |
| [3](labs/lab3.md)<sup>*</sup> | Advanced SQL.| 2018-12-01 |
| [4](labs/lab4.md) |  Write well-formed XML; extraction from XML; MapReduce | 2018-12-08 |

Quizzes

|     | Time | Date | Location |
|-----|------|------|----------|
| 1 | 15:00 - 15:30 | 2018-11-27 | In your lab section |
| 2 | 11:00 - 11:30 | 2018-12-13 | DPM 301 |



## Lectures


| # |     Date      | Day |  Topic  |  Slides  |
|---|---------------|-----|---------|----------|
| 1 | 2018-11-13 | Tue | Introduction to the relational model; Syntax/concepts for creating tables; Introduction to constraints | [Lecture1.pdf](slides/Lecture1.pdf); [live coding examples](slides/Lecture1_live_coding.txt)| 
| 2 | 2018-11-15 |Thur | Basic querying using SQL: Selection, Projection, Join | [Lecture2.pdf](slides/Lecture2.pdf); [sailors.db](slides/sailors.db); [Lecture2_with_answers.pdf](slides/Lecture2_with_answers.pdf); [live coding examples](slides/Lecture2_live_coding.txt) |
| 3 | 2018-11-20 | Tue | Conceptual database design - Part 1: ER model, constraints | [Lecture3.pdf](slides/Lecture3.pdf) |
| 4 | 2018-11-22 |Thur | Conceptual database design - Part 2: Translating ER to relational DB | [Lecture4.pdf](slides/Lecture4.pdf); [Lecture4_with_answers.pdf](slides/Lecture4_with_answers.pdf); [live coding examples](slides/Lecture4_live_coding.txt) |
| 5 | 2018-11-27 | Tue | Advanced SQL queries: set operations, nested queries | [Lecture5.pdf](slides/Lecture5.pdf); [Lecture5_with_answers.pdf](slides/Lecture5_with_answers.pdf); [live coding examples](slides/Lecture5_live_coding.txt); [Selfjoin_to_nestedquery_example](slides/Selfjoin_to_nestedquery.pdf)|  
| 6 | 2018-11-29 |Thur | Advanced SQL queries: aggregation | [Lecture6.pdf](slides/Lecture6.pdf) |
| 7 | 2018-12-04 | Tue | Database application development; Introduction to semi-structured data and internet applications | [Lecture7.pdf](slides/Lecture7.pdf) |
| 8 | 2018-12-06 |Thu  | Semantic web; Big data; Introduction to MapReduce | [Lecture8.pdf](slides/Lecture8.pdf); [cd_catalog.xml](slides/cd_catalog.xml); [cd_catalog.ipynb](slides/cd_catalog.ipynb) |
 


## Reference Material and other Resources
* Ramakrishnan, Raghu and Gehrke, Johannes. Database Management Systems, 3rd Edition, McGraw-Hill, 2002. (http://pages.cs.wisc.edu/~dbbook/)
* [SQL Tutorials on W3Schools](https://www.w3schools.com/sql/)
* [Learn SQL basic and advanced concepts](https://www.scaler.com/topics/sql/)
