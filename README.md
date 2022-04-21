# CUSTOMER-S-ORDERS
Queries using LEFT OUTER JOINS with GROUP BY and ORDER BY DESC

I've created a database for customers and their orders. Not all of the customers have made orders, however. I want to create a list with the name and email of every customer followed by the item and price of orders they've made. I want to be able to see my customers even if they've made no orders, and don't add any ORDER BY, to do so I used a LEFT OUTER JOIN.
Then I need a query that will result in one row per each customer, with their name, email, and total amount of money they've spent on orders, sorting the rows according to the total money spent, from the most spent to the least spent.
