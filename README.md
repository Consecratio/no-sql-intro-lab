# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
    - Refers to - Non relational databases OR Not only SQL OR Non SQL
2. What are some of the common arguments for using a non-relational versus a relational db?
    - Very useful for fast paced development
    - Easy to structure and evolve NoSQL DBs
    - Easy to scale with large amounts of data.
3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
    - Documents store or encapsulate and encode data in a standard format or encoding. (XML, YAML, JSON, and BinarySON)
    - Documents are not required to adhere to a standard schema, nor will they have the same sections, slots, parts, or keys.
    - Not all fields are required.
4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vs SQL?
    - SQL is structured and strict, but Mongo/NoSQL isn't which allows for more versatility.
    - Mongo stores documents with data (XML, YAML, JSON, and BinarySON)
5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 
    - A table in SQL that contains users would contain a column for UserName, Password, Email, FirstName, LastName, etc.
    - A similar setup in Mongo would be stored as an object similar to JSON { "userName": "", "password": "", "email": "", "firstName": "", "lastName": "" }
6. What is an example situation where a Mongo database makes sense versus a non-relational db?
    - When your program is going to add more functionality down the line.
    - When you need data to change over time or quickly.
    - When you're not concerned about data consistency or integrity. (Things can change)
    - When inputs can change datatypes, or when you have large amounts of data.
    - When your data needs to scale up, down or any direction.
