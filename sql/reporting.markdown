# Microsoft SQL Reporting

* [Table Creation](#table-creation)
* [Column Creation](#column-creation)

Ensure that you have [SSMS Setup](system.markdown), then follow the steps below

## Table Creation

There is SQL syntax for Creating Tables, but it is NOT ANSI SQL. The syntax varies across implementations. So we'll teach the GUI, and talk about strategies for managing it:

* Expand AdventureWorks
* Expand Tables
* Right click the Table folder and create a new Table
* Name the table whatever you want

## Column Creation

Now that we've got our table, let's setup our schema:

* Make your first column `Id`
* Mark it a `Primary Key` by right clicking to the left of `Id`. You should now see a key icon beside it.
* Make sure the `Allows Nulls` checkbox is left unchecked

While the `Id` column is selected, go to the bottom of the screen and find the "Identity Specification" option and update:

* Is Identity: `Yes`
* Identity Increment: `1`

**Previous:** [Performance](performance.markdown)
