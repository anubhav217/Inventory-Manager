# Hive IMS

## Info

* It is an "**Inventory Management System**"
* A system which has different stock categories and helps to manage stock data efficiently using CRUD feature for persistent storage
* Used Python as the primary coding language to build the system and MySQL Database to manage the data

## Design Pattern

* **Object Oriented Programming** approach has been implemented in the application while building the system
* **Factory Design Pattern** has been implemented to allows an interface or a class to create an object, but let subclasses decide which class or object to instantiate

## Features
* Hive IMS provides Inventory Management of stock categories of different Product's
* Each Product has a unique Item ID which will  be generated automatically when user wants to insert details of a new item
* It provides CRUD features to the user's in simple menu-based format to accept user input
* The MySQL Database will be connected from the system itself

## Functionalities
* Provides **CRUID** features using simple Menu based format in Command Line Interface
* **LIST** entire data of a particular Item ID, according to user input of Item ID
* **INSERT** data into the table by taking all required data of the Item and store the data into the database with a unique Item ID generated by the application itself
* **DELETE** data from the table of a particular Item ID, according to user input of Item ID
* **UPDATE** item details of a particular Item ID, according to user input of Item ID

## Prerequisites

* Python 3 and MySQL Database

## Installation and usage Guide
1. Download and install Python 3 [link](https://www.python.org/downloads/)
2. Download and install MySql Database and Setup the Database [link](https://dev.mysql.com/downloads/installer/)
3. Import the shared database file "test_stocks0.sql" from the repository [link](https://github.com/bitan-mondal/InventoryManagementSystem/blob/master/test_stocks0.sql)
4. Clone the repository to your local folder
4. Change the User ID and Password in the method `get_db_connection` in Services.py file with your Database user id and password
5. Open command prompt in your local repository and type `python main.py` to run the code

# Snapshot of Running Product
## Welcome Menu
![](HIVE_IMS_Product_Images/Welcome_Menu.jpg)
## Option [1] to List all the details of an item
![](HIVE_IMS_Product_Images/Option_1.JPG)
## Option [2] to Update details of an item
![](HIVE_IMS_Product_Images/Option_2.JPG)
## Option [3] to Delete an item
![](HIVE_IMS_Product_Images/Option_3.JPG)
## Option [4] to Add details of an item
![](HIVE_IMS_Product_Images/Option_4.JPG)
## Option [5] to List details of all item
![](HIVE_IMS_Product_Images/Option_5.JPG)
## Option [0] to Exit
![](HIVE_IMS_Product_Images/Option_0.JPG)

# Snapshot of MySQL Database
## MySQL Database
![](HIVE_IMS_Product_Images/MySQL_DB.JPG)




