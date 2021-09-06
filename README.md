# Inventory-managment-system-ETG-Internship
 This repository have all the codes used in AI/ML Skill India Scholarship Assignment-1, on Inventory Management System.
-------------

### About the Repository
Created an Inventory management system in which inventory of an electronic company is stored in a record.json file. And the system is made in such a way that users can add /update products in the inventory and can make purchases while keeping its record.  After every purchase, the records of the company sales are stored in the sales.json file.
-------------

# Files
1. record.json contains all inventory products and their attributes.
2. sales.json contain records of the company sales with product details with date & time of purchase.
3. inventory.ipynb is the source code file used to update and add products to the inventory.
4. purchase.ipynb is the source code file used to make purchases, generate invoice and record company sales to the sales.json file.
---------------

## Features & Functionality

1. Users can add new products into the inventory and can add more items to the products already available in the inventory.
2. It will first ask the user to enter the number of the item he/she wants to add. So that users can add multiple items at a time. 
3. It will take care of all the errors in spacing, that the user might do while entering the product id.
4. It will check if the id entered by the user is already present in the inventory or not. If it already exists then it'll just add the number of quantities to the previous data      of that id. If not then it'll ask to add all the attributes of the product to the inventory. And after all these changes, the record.json file is updated.
5. It will ask the user to enter the number of items that he/she wants to purchase. Allowing one user to make multiple purchases.
6. Purchasing of the items will be based on the product ID of each product as registered in the record.json file.
7. It will check if the product id entered by the user is a valid id or registered in the record.json file. If it's not valid ID it will prompt " Sorry, we don't sale this item".
8. If the entered id is registered or valid id, but currently not available. It'll print a user-friendly message that the product is not available.
9. If the quantity added by the user for a product is greater than the available quantity. Then it will prompt a question to the user if he wants to purchase the available            quantity of products. If the user responded "yes" irrespective of the case sensitivity. It will continue the purchase.
10. It will then create an Invoice for the items purchased by the user. Mentioning the total bill of all the purchased items.
11. At the end it will update the available quantity of purchased items in the inventory. And keeps the record of all the sales in the sales.json file with products details, date     and time.
-----------------

## Who I am?
My name is Divya Pathak and I recently completed my Masters in physics. I'm currently doing AI/ML python internship with ELITE techno group.

