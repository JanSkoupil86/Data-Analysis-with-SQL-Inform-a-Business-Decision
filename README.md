# Data-Analysis-with-SQL-Inform-a-Business-Decision
The SQL code provided demonstrates the use of several skills and concepts. Here's a breakdown:

SELECT statement: This skill is used to specify the columns to be included in the result set.

Column aliases: The alias "SalesAmt" is used to give a more descriptive name to the computed column sum(Quantity * Price).

FROM clause: This clause specifies the tables from which the data is being retrieved.

INNER JOIN: This skill is used to combine rows from multiple tables based on a related column between them. In this code, there are multiple inner joins between the tables "employees," "orders," "orderDetails," and "products."

ON clause: This clause is used in conjunction with the inner join to specify the join condition based on the equality of specific columns between the joined tables.

GROUP BY clause: This clause is used to group the result set by a specified column or columns. In this code, the grouping is done by "orders.orderid."

HAVING clause: This clause is used to filter the groups created by the GROUP BY clause based on specified conditions. In this code, it filters the groups to include only those with order IDs specified in the list (10372, 10424, 10417, 10324, 10351).

ORDER BY clause: This clause is used to sort the result set based on one or more columns. In this code, the result set is sorted by the "SalesAmt" column in descending order.

Overall, the skills used in this SQL code include selecting specific columns, joining tables, aggregating data with the SUM function, grouping data with the GROUP BY clause, filtering grouped data with the HAVING clause, and sorting the result set with the ORDER BY clause
