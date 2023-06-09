# Review of the beauty of SQL

# Introduction & Goals
The following project is designed to provide a clear overview of the core concepts behind the SQL language using the Adventure works (global manufacturing company) database which is organised within a typical star schema whereby the fact and dimensions of the database are separated. In particular , we will be working with the sales, reseller and finance databases each with approximately 6-12 interlinking tables. 

As per the contents section, the project will be broken down into an introduction of the data itself followed by the primary strucuture of SQL queries whereby it will then delve deeper into the nuances of joining tables and developing subqueries within SQL itself. 

# Contents

- [The Data Set](#the-data-set)
- [Used Tools](#used-tools)
- [Steps](#steps)
  - [Developing familiarity with the database](#developing-familiarity-with-the-database)
  - [Joins and SubQueries](#joins-and-subqueries)
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

# Used Tools
The tools within this project are fairly simple with SQL being the only language utilised. One may ,however, utilise notepad++ as a repository of sorts, to store data in the format in which it would be illustrated from the UI of the datawarehouse (as opposed to a text based notepad or a language specific IDE such as PyCharm). 

# Steps

## Developing familiarity with the database
Although there are many queries that one can utilise to familiarise oneself with the databases, I believe the following image servers as one that provides a clear illustration in terms of the methodology that the SQL language utilises: 

* IMAGE: 

As per the above, the manner in which one should typically approach a database is through determining the tables in which all the data would be present utilising the FROM statement whereby the subsequent operational statements refine what the user is seeking to garner. This proves to be the area in which one wishes to do aggregate operations on the tables via the groupby statement followed by the selection of the end columns and implementing a final organisation via the "ORDER BY" statement. 

The second visulisation provides an example of how one can leverage multiple conditional statements within SQL , proving that SQL can be utilised to develop analysis itslef rather than be simply viewn as a data extracton tool. 

* IMAGE: 

Queries pertaining to the initial analysis are provided in the accompanying files. 

## Joins and SubQueries
When attempting to join tables within a database, rather than viewing the operations from an circular object type interectional framework as taught in various courses that I have undertaken in the past, I find it most useful to view the joins in a rescursive manner whereby I attempt to emulate what would occur should there not be a corresponding row-wise vaulue within the second column. IE Inner join : if there is no corresponding value , I do not want the data to be included. 
Moreover, I find that there are not always many resources that cover the functionality between bridge tables. As such I have included an image of a SQL query which hasndles suc an operation quite clearly: 

* IMAGE 

In the nature of clarity, the idea of the above is to connect the orignating fact table to the various tangential tables through the primary - foreign keys followed by leveraging such a connection to pull in the desired columns. 

As per the initial section, additional sql files are provided in the attached folder. 

# Conclusion
Although I may not have found this project to be too challenging in terms of the development of the data (in terms of sourcing, processing , testing the data and thecreation of the schema's) I enjoyed exploring the functionality of SQL as a language which , in all honesty, initially did not think too much of. I also realised that the power of SQL as a whole in the data industry is, in part, due to its standardised approach to dealing with data allowing for a higher level of operability between various users of an end system.

# Follow Me On
Add the link to your LinkedIn Profile

# Appendix
All data aquired from the BIDA CFI course. 
