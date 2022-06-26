# SQL_Project

## SQL_Project: Project Overview

The goal of this project is to analyze data from a sales records database for scale model cars and extract information for decision-making.
We are trying to answer the following questions:

* Question 1: Which products should we order more of or less of?

* Question 2: How should we tailor marketing and communication strategies to customer behaviors?

* Question 3: How much can we spend on acquiring new customers?


## Database schema

The scale model cars database schema.

![This is an image](https://github.com/haithamq11/SQL_Project/blob/main/structure%20of%20db.png)


It contains eight tables:

**Customers:** customer data

**Employees:** all employee information

**Offices:** sales office information

**Orders:** customers' sales orders

**OrderDetails:** sales order line for each sales order

**Payments:** customers' payment records

**Products:** a list of scale model cars

**ProductLines:** a list of product line categories

Here are the tables, attributes of each table and number of rows

![This is an image](https://github.com/haithamq11/SQL_Project/blob/main/tables%20and%20records.png)


## Conclusion

Here are the answers to our questions.

**Question 1:** Which products should we order more of or less of?

Classic cars are the priority for restocking. They sell frequently, and they are the highest-performance products.

![This is an image](https://github.com/haithamq11/SQL_Project/blob/main/question%201.png)

**Question 2:** How should we match marketing and communication strategies to customer behaviors?

VIP customers

![This is an image](https://github.com/haithamq11/SQL_Project/blob/main/question%202.png)

Least engaged customers

![This is an image](https://github.com/haithamq11/SQL_Project/blob/main/question%202%20part%202.png)

**Question 3:** How much can we spend on acquiring new customers?

![This is an image](https://github.com/haithamq11/SQL_Project/blob/main/question%203.png)


LTV tells us how much profit an average customer generates during their lifetime with our store. We can use it to predict our future profit. So, if we get ten new customers next month, we'll earn 390,395 dollars, and we can decide based on this prediction how much we can spend on acquiring new customers.
