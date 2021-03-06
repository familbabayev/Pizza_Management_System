# Pizza Management System
Simple project for ordering pizzas.
## Contents
* [General Info](#general-info)
* [Technologies used](#technologies-used)
* [Setup](#setup)
* [Usage](#usage)
* [Relational Database diagram](#relational-database-diagram)
* [Class diagram of Decorator Pattern](#class-diagram-of-decorator-pattern)

## General Info
The application includes the following functionalities:
* Registration of a new user
* Login as user and admin
* As a user
  * Selecting pizza and customizing toppings and quantity
  * Adding multiple pizzas to basket
  * Ordering pizza
  * Viewing order history
* As an admin
  * Adding new pizza
  * Viewing all orders
* Notifying users when new pizza added

## Technologies used
Project created with:
* Python3
* Tkinter
* SQLite

## Setup
1. Install python3
2. Install tkinter(if you don't have). In Linux:
```
sudo apt-get install python3-tk
```
3. Clone this repository
```
git clone https://github.com/familbabayev/Pizza_Management_System.git
```
4. Install the requirements of this repository
```
pip install -r requirements.txt
```
if you get error, try to upgrade your pip
```
python3 -m pip install --upgrade pip
```
5. Run main.py
```
python3 main.py
```
## Usage
Sample database records are already in pizza.db and its instructions are in main.py as commented part. If you want to build from scratch just delete pizza.db

Run main.py 

Have Fun :)
## Relational Database diagram
![PizzaRelationalDatabase](https://user-images.githubusercontent.com/44068684/80802158-9ac77a00-8bbf-11ea-9c0b-1a53c72e344d.png)
## Class diagram of Decorator Pattern
![PizzaClassDiagram](https://user-images.githubusercontent.com/44068684/80802167-a024c480-8bbf-11ea-9a5f-540b1be69b2a.png)
