# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
I am going to create an web application that will be used to manage a small restaurant inventory. Users will need to enter all items to begin with. When entering the inventory items they will also set the starting quantity, a minimum quantity and maximum quantity.Once the starting inventory is ready users will be able to up date the inventory at the end of each day by adjusting the tracked quantities. The application will know when a quantity goes below the minimum amount. Once this happens the item will be flagged for when an order needs to be placed. When the user is ready to create an order they will be able to view all items that are below the minimum amount that they set. The order will automatically determine how much of a given item will need to be order based on the maximum limit that the user also set. The user will be able to make changes to the order as they see fit and once they are happy with the selection they will be able to save the order and send the order information in an email. When the order is received the user will confirm that the shipment is correct. IF the quantities are all correct the user will be able to commit the order to the inventory, which will add the order amounts to the current inventory. If any quantities in the shipment are incorrect the user will be able to adjust the quantities before commit the order to the inventory. Order information will be saved as a backlog and will allow the user the see what has been ordered in the past.

The main user would be my sister that owns a restaurant. She current has to go into the store to do inventory and place orders on her days off. My plan is to create a way for any of her managers to be able to update the inventory and then she would be able to place the orders from her home on her days off. The added benefit of offer some backlog information will provide insight in to what has been order in the past and help with deciding what she may need to order.

### Features
Search -
User will be able to search for products by type (meat, produce, veggie, fruit, etc) and category (breakfast, lunch, dinner, appitizer, beverage etc)

Auto ordering population/logic - 
User will set minimum and maximum quantites for items that will be used to determine if a item needs to be ordered and how much should be ordered

email orders-
User will be able to create an order that will be auto populated with all items who's quantities are equal or below their individual minimum counts. The order will set the amount to order equal to the difference of the maximum amount and current amount of each item. User will also be able to edit the order by adding or removing items and increasing or decrease quantitie as needed to meet their needs.

User login/admin privileges
There will be two types of users. a basic user will only be able to update inventory quantites. The power/admin user will be able to update inventory quantites, add new items, remove items, place orders, update item min/max.

Backlog/reports
The user will be able to view a backlog of what has been ordered in the past. For example they could see what was ordered this week last year.

food supplier API for prices and products
The application would have access to the restaurants food supplier(s) API and would have access to product information and prices. This would be used to inform the user of how much money thye have in their current inventory.

### Technologies
Java
MySQL
API
HTML
Bootstrap
javascript

### What I'll Have to Learn
javascript

###Project Tracker
Git hub projects
