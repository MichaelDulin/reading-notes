# Class 4.1 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 1**
- [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
- [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
- [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
- [sequelize api](https://sequelize.org/master/)

**nosql vs sql**
1. What type of database is the best fit for the complex query intensive environment?
  - SQL
2. What type of database is the best fit for hierarchical data storage?
  - NoSQL
3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
  - SQL is vertically scalable, which can only manage increasing load by increasing hardware due being confined to a single server. NoSQL is scalable horizontally and can increase its load by simply adding more servers.

  
**sql modeling techniques**
1. Among data tables, what is a one-to-many relationship and how do we “relate” them?
  - One-to-many relationships are the most common and refers to a 'parent' database having many 'children' but the 'children' only have one 'parent'. These are related via a primary key
2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
  - Create a diagram
3. Explain the difference between a primary and foreign key.
  - A primary key is unique and identifies every record in a table or relationship. Each database needs a unique identifier for every row of a table, and the primary key plays a vital role in identifying rows in the table uniquely.


**sql vs nosql**
1. How do we treat keywords and parameters differently in SQL syntax?
  - Using keywords, we can identify a 'physical place' in our database which we can then coduct a variety of methods to.
2. Define normalization within the context of schemas and data.
  - Normalization is the process of organizing data within a database in a specific way, avoiding duplicates and other undesirable characteristics
3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
  - Each of these refers to a reference of data. One-to-many would be a parent accessing their children, one-to-one can be a piece of a table accessing another piece within that table and many-to-many refers to two items or tables which share many keys with eachother.


## Things I want to know more about
