# Author: Nthabiseng Maya

1. ER COMPONENTS
ENTITY
-An entity is a real-world object that we want to store information about in a databasse.In a Bookstore, a Customer or a Student is an entity because they can place Orders of books they would like to purchase.

RELATIONSHIP
-A relationship shows how two or more entities are connected to each other.For instance in a bookstore a customer places an order of a book.This shows the connection between the Customer and Orders.

ATTRIBUTE
-An attribute is a small information that describes an entity.Like one Customer can have many attributes such as customer_id, name, email_address and phone numbers so this information helps the boostore to identify and also store information about each customer



2. CONCEPTUAL DATA MODEL VS PHYSICAL DATA MODEL
Conceptual Data Model
-a conceptual data model gives us a clear picture of how information in a database will be organised, it deals with the main entities and how they are connected to each other without showing more information,

Physical Data Model 
-A physical data model shows how the database will actually be created in a database system including more information like table names, columns and primary/foreign keys

-So the difference between the two is that conceptual model focuses more on what information do we need and how it is connected then physical model focuses more on how we will store the information in the database

SECTION 3
  CUSTOMER
-customer_id(PRIMARY KEY)
-name
-email
       |
       |
       |
ORDERS
-order_id(PRIMARY KEY)
-order_date
-customer_id (FOREIGN KEY)

One customer can place many orders but each belongs to only one customer
