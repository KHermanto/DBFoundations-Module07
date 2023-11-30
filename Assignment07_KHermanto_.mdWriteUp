# Kevin Hermanto

# 11/28/2023

# Course: IT FDN 130A

# Assignment 07 – Functions

# https://github.com/KHermanto/DBFoundations-Module07

## Introduction
In this document, I will discuss SQL functions, SQL UDF and the difference between Scalar, Inline and Multi-Statement Functions

## When you would use SQL UDF	
SQL UDF is a User Defined Function. It’s a custom function by the user that can return a table or a single value. Users may use UDF to perform an action, complex calculations or retrieve data from tables or views. Functions can be created once, stored in the database and used in many circumstances. This reduces the amount of time the users need to code which results in faster execution. In addition, UDF is independent from the program source code, which means the users may make changes to the code without modifying the program source code.
Scalar, Inline, and Multi-Statement Functions 
Scalar Function is a type of UDF that returns a single value (eg, integer, string or date). In the example below **(Figure1)**, the purpose of the Select statement is return date.
 
 ![Figure1](https://github.com/KHermanto/DBFoundations-Module07/assets/151798353/95aa8412-2fc1-4779-8c02-63bf97e347cf)

**Figure1**



Inline Function is also a UDF that returns a table-like result based on input parameters. In **Figure2** below, we have an Inline Function with specified parameter “@KPI” with the data type “Int”.  The Select Statement below returns data like ProductName, InventoryDate, etc from the “vProductInventoriesWithPreviousMonthCountsWithKPIs” View with the value equal to the function’s parameter “@KPI”.

 ![Figure2](https://github.com/KHermanto/DBFoundations-Module07/assets/151798353/ea79ceee-d868-4c04-ba5a-6ca5541b4648)

**Figure2**



Multi-Statement Functions is another UDF function that includes multiple T-SQL statements within the function itself. It uses the “Begin” and “End” block. This function is mostly used for complex code that cannot be expressed in a single expression.

## Summary
SQL UDF is an essential tool in SQL development. The three distinct UDFs address different reporting needs and complexity without modifying the program source code. They capture customized logic within the queries as well as facilitate code reusability to optimize performance and efficiency. UDFs also improves SQL code’s maintenance and simplify processes. 
