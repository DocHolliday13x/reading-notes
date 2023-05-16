# Class 4 Reading: Data Modeling

## Resources

- [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
- [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
- [sql vs nosql video](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
- [sequelize api](https://sequelize.org/docs/v6/)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-04/)

### NoSQL vs SQL

1. What type of database is the best fit for the complex query intensive environment?
    - SQL

2. What type of database is the best fit for hierarchical data storage?
    - NoSQL

3. Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.
    - SQL databases are vertically scalable, meaning that you can increase the load on a single server by increasing things like RAM, CPU, or SSD. NoSQL databases are horizontally scalable, meaning that you can add more servers to handle the load.

### SQL Modeling Techniques

1. Among data tables, what is a one-to-many relationship and how do we "relate" them?
    - A one-to-many relationship is when one record in a table is associated with one or more records in another table. We "relate" them by using a foreign key.
2. Prior to designing your relational database, it might be useful to ___a___ of the database tables and thier relationships.
    - sketch a diagram

3. Explain the difference between a primary and foreign key.
    - A primary key is a column that uniquely identifies each row in a table. A foreign key is a column that creates a relationship between two tables.

### SQL vs NoSQL Video

1. How do we treat keywords and parameters differently in SQL syntax?
    - We treat keywords as commands and parameters as values.

2. Define normalization within the context of schemas and data.
    - Normalization is the process of organizing data in a database. It involves creating tables and establishing relationships between those tables according to rules designed both to protect the data and to make the database more flexible by eliminating redundancy and inconsistent dependency.

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
    - A one-to-one relationship is when one record in a table is associated with one record in another table. A one-to-many relationship is when one record in a table is associated with one or more records in another table. A many-to-many relationship is when one or more records in a table are associated with one or more records in another table.

#### Bookmark and Review

- [sequelize api](https://sequelize.org/docs/v6/)

#### Reflection

1. What are your learning goals after reading and reviewing the class README?

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-04/)

  - I want to learn more about SQL and NoSQL databases. I also want to learn more about data modeling.

#### Things I Want to Know More About

1. Why it's necessary to have a Things I Want to Know More About section on a page of notes that also has a Reflection section. Repetition is close to godliness, I suppose.
