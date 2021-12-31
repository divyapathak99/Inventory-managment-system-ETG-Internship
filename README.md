# Inventory-management-system-ETG-internship
This repository has all the codes used in AI/ML skill India internship assignments on the inventory management systems.

##  About the repository
This creates an Inventory management system stored in a record.json file, one can add and purchase products from inventory and then all sales will be stored in the sales.json file.

## Files 
1. record.json contain all the inventory products.
2. sales.json contains all sales company has made.
3. add_items.ipynb contain codes to add new products into inventory.
4. purchase. ipynb contain codes to make purchase from inventory and create an invoice for consumer and add sales to sales.json.

## Features
1. User can add any number of items into inventory. If an item already exists in the inventory then update the quantity of that item.
2. Users can purchase any number of items from inventory. So, it will ask the user to enter the number of products he/she wants to purchase.
3. One can purchase any product base on product ID and the product ID is unique for each product.
4. If the user will ask for a product whose quantity is zero that is not available in the inventory, the program will prompt a dialogue "Not Available".
5. If the user will ask for a product whose product ID is not registered in the inventory. It will give the same dialogue "Not Available".
6. If the quantity of product the user has asked for is greater than the quantity of product in inventory, it will prompt a question to the user tha if the user wants to purchase the available quantity of products and if the user enters yes, it will continue with the purchase. if the user enters no then it will quit that purchase transaction and continue with the next item.
7. It creates an invoice for user purchased items with the date and time.
8. It updates inventory, add sales to the sales.json file with the date and time of sale.


###  Who am I
I am Divya pathak. I have recently completed my masters in physics. Currently, doing an AI/ML python internship with Elite Techno Group.
