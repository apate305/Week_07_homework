# Week_07_homework
Explain what autoincrementing is. Also explain the difference between creating a join and a subquery.

Autoincrementing is when a number is automatically generated for a record that is inserted into a database.  A autoincremented field is usually specified as a primary key field in a query. It is important to note that by default the starting value is 1 and this number will increment by 1 for each row in the table. If you want to specify a different starting point and increment, you need to adjust your query accordingly.

Joins are able to connect 2 or more tables together through matching columns. It allows you to select multiple fields across different but related tables. Through joins, the user can see how the data from different tables relate to each other. The outputted table will contain columns from different tables where the values across fields can be succinctly connected. A join occurs in the from clause only.

On the other hand. subqueries are embedded within the main query and can stand on its own unlike a join. Unlike joins, it can occur in where, select and from clauses. Also subqueries do not combine tables like joins instead they have their own output which is used by the main query as a condition to filter or restrict data. 
![Datacamp Join Certificate](https://user-images.githubusercontent.com/69228806/139956372-9ff22567-3d5c-4903-be0f-32f25565721f.png)
