# Data Modeling

## Name 3 advantages to Test Driven Development

- Better program design and higher code quality.
-  Save project costs in the long run.
- TDD reduces the time required for project development.

## In what case would you need to use beforeEach() or afterEach() in a test suite?

- If need to setup a mock object or  and this object  can be reused by all the tests units


## What is one downside of Test Driven Development

When feature changes, implementation will change as well, and many test cases will fail

The downside to TDD is that it is usually tightly associated with 'Agile' methodology, which places no importance on documentation of a system, rather the understanding behind why a test 'should' return one specific value rather than any other resides only in the developer's head.


### What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

A child of an ES6 class is another type definition which extends the parent with new properties and methods, which in turn can be instantiated at runtime. ... A class constructor creates an instance of the class. A constructor in JavaScript is just a plain old function that returns an object.



### ”Why REST?”

- 1) REST is Easy to Understand and Implement
- 2) REST Makes your Application More Scalable
 - 3) Caching is Easier with REST
- 4) REST is Flexibile


-------------------------------------------------------------------

## *Document the following Vocabulary Terms*

``functional programming``

 functional programming is a programming paradigm where programs are constructed by applying and composing functions.

``object-oriented programming (OOP)``

Object-oriented programming (OOP) is a computer programming model that organizes software design around data, or objects, rather than functions and logic.

``class``

A class is the description of a set of objects that share the same attributes, operations, methods, relationships and semantics. A class may use a set of interfaces to specify collections of operations it provides to its environment.

``super``

 keyword to call the constructor of the super class.

``this``

In the global execution context (outside of any function), this refers to the global object whether in strict mode or not.


``Test Driven Development``

Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed

``Jest``

JEST is a delightful JavaScript Testing Framework with a focus on simplicity and test runner mainly for creating, running, and structuring tests. JEST is distributed as an NPM / YARN package, you can install it in any JavaScript projec

``Continuous Integration (CI)``

Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. It's a primary DevOps best practice, allowing developers to frequently merge code changes into a central repository where builds and tests then run.

``REST``

Representational state transfer (REST) is a software architectural style that was created to guide the design and development of the architecture for the World Wide Web. REST defines a set of constraints for how the architecture of an Internet-scale distributed hypermedia system, such as the Web, should behave.

``Data Model``

A data model (or datamodel) is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities. ... The term data model can refer to two distinct but closely related concepts
--------------------------------------------------------------------------

# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- Linked tabel by key
- Sql lite 
- Collection
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- Sql  Database with multi of tabels and key
- Express Route
- SQL App tools 
> What are you most excited about trying to implement or see how it works?
-  big database with multi of collections 

-----------------------------------------------------------------

## SQL vs NoSQL Database 

### SQL vs NoSQL: High-Level Differences 
- SQL databases are primarily called as Relational Databases (RDBMS); whereas NoSQL database are primarily called as non-relational or distributed database 
- SQL databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column store 
- SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data 
- SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable 
 - SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful. In NoSQL database, queries are focused on collection of documents 

![](https://miro.medium.com/max/2000/1*1QyI7Zxx73mkG0FcwNUyuw.jpeg)
 ### SQL Database Examples : 
 - MySQL Community Edition 
 - MS-SQL Server Express Edition 
 - Oracle Express Edition 

 ### NoSQL Database Examples
-  MongoDB 
- CouchDB 
- Redis 

---------------------------------------------------------
### sql modeling techniques : 

There are many types of modeling software you can use to create models, such as MySql Workbench, which not only create smart looking diagrams 
### Model a relational database table that include : 
- The Table Name, which is located at the top of the table.
- The Primary Keys.  Remember the primary keys uniquely identify each row in a table.  A table typically has one primary key, but can have more.  When the key has more than one column, it is called a compound key.
- Table Columns – There can be one or more table columns.  To keep the diagrams simple, I don’t show the data types.  I may introduce those later when we focus on more comprehensive modeling.
- Foreign Key – This is a column or set of columns which match a primary key in another table.   


![](https://www.essentialsql.com/wp-content/uploads/2021/11/Database-Table-Data-Modeling.png?ezimgfmt=rs:455x336/rscb23/ng:webp/ngcb23)  

### Data Modeling – Table Relationships 

- one-to-many relationship : an entry in one table can be related to more than one entry in another. 
- many-to-one relationship:  is similar to a one-to-many relationship, this difference is in the point-of-view you take when naming the relationship
- one-to-one 
- zero or one-to-many 


![](https://www.essentialsql.com/wp-content/uploads/2014/06/DataModel-Relations1.png?ezimgfmt=ng:webp/ngcb23)
