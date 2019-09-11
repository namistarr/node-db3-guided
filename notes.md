# Problem

A client has hired you to track zoo animals.
For each animal, you must track their name, species, and all zoos in which they have resided (including zoo name and address).

Determine the database tables necessary to track this information.

Label any relationships between table.


SELECT customers.customerName, customers.country, orders.orderId, orders.orderDate FROM [Orders] inner join customers on orders.customerId = customers.customerId order by orders.customerId


LEFT JOIN: give me all records from the left table and data you find from the right table


