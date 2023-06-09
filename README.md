# DataWarehouse-querying_in_depth

> Introduction to the warehouse itself. 

> Structure of SQL as a language ( ORDER OF OPERATIONS ) * images 

> Initial queries 
> Aggregate functions 
> String functions 

> JOINS and subqueries

# Review of the beauty of SQL

# Introduction & Goals
The following project is designed to provide a clear overview of the core concepts behind the SQL language using the Adventure works (global manufacturing company) database which is organised within a typical star schema whereby the fact and dimensions of the database are separated. In particular , we will be working with the sales, reseller and finance databases each with approximately 6-12 interlinking tables. 
As per the contents section, the project will be broken down into an introduction of the data itself followed by the primary strucuture of SQL queries whereby it will then delve deeper into the nuances of joining tables and developing subqueries within SQL itself. 

# Contents

- [The Data Set](#the-data-set)
- [Used Tools](#used-tools)
  - [Connect](#connect)
  - [Buffer](#buffer)
  - [Processing](#processing)
  - [Storage](#storage)
  - [Visualization](#visualization)
- [Pipelines](#pipelines)
  - [Stream Processing](#stream-processing)
    - [Storing Data Stream](#storing-data-stream)
    - [Processing Data Stream](#processing-data-stream)
  - [Batch Processing](#batch-processing)
  - [Visualizations](#visualizations)
- [Demo](#demo)
- [Conclusion](#conclusion)
- [Follow Me On](#follow-me-on)
- [Appendix](#appendix)


# The Data Set
The various databases follow the Azure data stack in which they will be accessed through the Azure Data Studio deskop application. The data itself is owned by a Multi-National manufacturing company who manufactures and sells metal and composite bicycles. The company consists of 290 employees with several regional teams and is looking to broaden its market share by reviewing the source of its sales with a particular focus on the performance via its online presence. 

The tables within the database consist of the following schemas: 
  -> Financial data: 
    IMAGE
  -> Sales data: 
    IMAGE
  -> Reseller data: 
    IMAGE

Upon initial review, one can determine that the data itself is well structured with the factual data acting as the central potion of each database with the dimensions following a logical snowflake-like structure. For the purposes of this project, no additional functionality of such a database such as views will be covered as the analysis is being conducted from the viewpoint of a data analyst. 

# Developing familiarity with the database (overview of order of operations within SQL)

The tools within this project are fairly simple with SQL being the only language utilised. One may ,however, utilise notepad++ as a repository of sorts, to store data in the format in which it would be illustrated from the UI of the datawarehouse (as opposed to a text based notepad or a language specific IDE such as PyCharm). 

# Joins and SubQueries
- You could add a demo video here
- Or link to your presentation video of the project

# Conclusion
Write a comprehensive conclusion.
- How did this project turn out
- What major things have you learned
- What were the biggest challenges

# Follow Me On
Add the link to your LinkedIn Profile

# Appendix

[Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
