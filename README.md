Concept:
Many shopping centers are willing to put their items on Web so that they can increase their revenue. To do this, they must have a Web application that manages items and lets clients to choose and buy them online.
For this project you must create an application that contains the information needed.

About:
Suppose we have a Shopping center that has its own inventory application and wants to connect this application to a Web application that shows items and provides a platform to sell items.

Requirements:
-	Users must create an account
-	Users must provide contact information
-	Users can select items based on categories
-	Users can add items to their basket
-	Users can select different types of payments (online, on-receive, …)
-	Users can change their profile
-	Users can delete items from their basket
-	Users can change number of an item in their basket
-	Users can see availability of an item
-	Users can see detail information about an item
-	Admin users can be alerted when an item is sold out completely
-	Admin users can see reports of sales based on categories
-	Admin users can see a factor to be provided to the user
-	Inventory staff should see items to be sent to users
-	Each sale transaction can have different states (in progress, ready to send, sent, received, … )
-	System Admin users can define, edit and delete admin users

Entities:
-	Shopping item

o	Name

o	Id

o	Count in inventory

o	Category

o	Price

o	Size

o	Color

o	Description

o	…

-	Category

o	Name

o	Id

o	Description

-	Factor

o	Id

o	List of items

o	Status (ready, sent, received, … )

o	Date created

o	Date modified

o	Type of payment

o	Total price

-	User 

o	Name

o	Address

o	Phone number

o	Credit card number (not mandatory)

o	Username

o	Password

-	Admins

o	Name

o	Username

o	Password

o	Department

o	Employee Id

o	Date joined

o	Status (active, suspended, in leave, … )

-	System Admin

o	Name

o	Username

o	Password

Duty:
Design an application from UI to DB that meets the requirements with having in mind that requirements may be added in future)

Note:
-	You can add properties to entities to have a better design.
-	You must include all properties that are mentioned
-	There may be different properties based on item’s category
-	You can design your database with your desire. That is, it is not mandatory that “employee” table must have a “department id”

Enjoy!

