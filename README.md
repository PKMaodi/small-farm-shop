# small-farm-shop

The Web application works with two roles, a manager and a customer. Each of the roles have their own respective menu options. A manager is able to do two things, namely:
1. Persist items into the database. An item has the following attributes:
✓ Code;
✓ Description;
✓ Unit price; and
✓ Quantity.
Also included as item attributes is an id and the creation date. The id serves as a primary key. This 
key is automatically generated by the persistence provider. The creation date is a timestamp reflecting when an item was persisted into the database.
2. Display the details of all the orders placed by customers that that fall within an order value range, i.e between minimum and maximum order values. An order value is the total cost of an order (amount
due by a customer). The details of the placed orders must be displayed in a descending form according 
to the order value. For each order, the following information is displayed:
✓ Order number;
✓ Order timestamp;
✓ Amount to be paid by the customer for the order (order value); and
✓ Address of the customer.
A customer is able to place an order. For a customer to place an order, all the available items, together with their unit prices must be shown to the customer for selection. A customer must be able to select an item, state the needed quantity and place the selected item on a shopping cart. A customer must be able to select all the needed items. After completing the selection process, a customer must be able to provide a delivery address and thereafter place an order. The order must be persisted into the database. So an order will consist of a list of items, their total value (total amount due), the customer address and the creation date(timestamp). An address has three attributes, namely street, area, and code. The primary key of an order (id) must be automatically generated by the persistence provider.
