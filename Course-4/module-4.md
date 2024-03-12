# Tools of the Trade: Linux and SQL

## Module 4 - Databases and SQL

### Learnings

- Relational databases
- SQL queries
- SQL filters
- SQL joins


### Introduction to databases

**Database**

An organized collection of information or data

**Spreadsheets**

- Designed for a single user or a small team
- Store less data

**Databases**

- Accessed by multiple people simultaneously
- Store massive amounts of data
- Perform complex tasks while accessing data

**Relational database**

A structured database containing tables that are related to each other

**Primary key**

A column where every row has a unique entry

**Foreign key**

A column in a table that is a primary key in another table


### Query databases with sql

**SQL (Structures Query Language)**

A programming language used to create, interact with, and request information from a database

**Query**

A request for data from a database table or a combination of tables

**Log**

A record of events that occur within an organization's systems


### Basic queries

**`SELECT`**

Indicates which columnns to return

**`FROM`**

Indicates which table to query

**Syntax**

The rules that determine what is correctly structured in a computing language


### Basic filters on SQL queries

**Filtering**

Selecting data that match a certain condition

**Operator**

A symbol or keyword that represents an operation

**`WHERE`**

Indicates the condition for a filter

**`LIKE`**

Used with `WHERE` to search for a patter in a column 


### Filter dates and numbers

**Common data types**

- String
- Numeric
- Date and time

**String data**

Data consisting of a ordered sequence of characters

**Numeric data**

Data consisting of numbers

**Date and time data**

Data representing a date and/or time

**Operators**

- `=`
- `>`
- `<`
- `<>`
- `>=`
- `<=`

**`BETWEEN`**

An operator that filters for numbers or dates within a range


### Filters with AND, OR, and NOT

**`AND`**

Specifies that both conditions must be met simultaneously

**`OR`**

Specifies that either condition can be met

**`NOT`**

Negates a condition


### Join tables in SQL

**`INNER JOIN`**

Return rows matching on a specified column that exists in more than one table.

**Types of outer joins**

- `LEFT JOIN`
- `RIGHT JOIN`
- `FULL OUTER JOIN`

**`LEFT JOIN`**

Returns all of the records of the first table, but only returns rows of the second table that match on a specified column.

**`RIGHT JOIN`**

Returns all of the records of the second table, but only returns rows from the first table that match on a specifies column.

**`FULL OUTER JOIN`**

Returns all records from both tables.


