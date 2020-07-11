Create Schema
A SQL schema is identified by a schema name, and includes a authorization identifier to indicate the user or account who owns the schema. Schema elements include tables, constraints, views, domains and other constructs that describe the schema.

A schema is created using the CREATE SCHEMA statement. For example, we can create a schema called LIBRARY for this course:

CREATE SCHEMA LIBRARY AUTHORIZATION ‘Robert’

The data types used can be: numeric, character-string, bit-string, Boolean, DATE, timestamp, etc.

CREATE TABLE Statement
The CREATE TABLE statement includes these clauses:

· DEFAULT

· CHECK

Use the DEFAULT clause in the CREATE TABLE statement to specify the default value for the database server to insert into a column when no explicit value for the column is specified.

Use the CHECK clause to designate conditions that must be met before data can be assigned to a column during an INSERT or UPDATE statement.

During an insert or update, if the check constraint of a row evaluates to false, the database server returns an error. The database server does not return an error if a row evaluates to NULL for a check constraint. In some cases, you might want to use both a check constraint and a NOT NULL constraint.

SELECT Statement
The basic structure of the SELECT statement is formed from three clauses: SELECT, FROM and WHERE.

<attribute list> is a list of attribute names whose values are to be retrieved by the query

<table list> is a list of the relation names required to process the query

<condition> is a conditional(Boolean) expression that identifies the tuples to be retrieved by the query

In situations where you might want to use multiple IF-THEN-ELSE statements, you can often use a single SELECT statement instead. The SELECT statement allows a CLIST to select actions from a list of possible actions. An action consists of one or more statements or commands. The SELECT statement has the following syntax, ending with the END statement. You can use the SELECT statement with or without the initial test expression.

SELECT [test expression]

WHEN [expression1]

...

(action)

...

WHEN [expression2]

WHEN [expression3]

...

[OTHERWISE]

...

(action)

...

END
