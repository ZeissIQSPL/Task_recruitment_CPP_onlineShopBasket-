# Task: Online shop basket 

Your company asked to develop software for a large online shop *InspectMarkt*. 
One of the core functionalities is the shopping cart software, 
which can take into account various promotions, discounts and special offers, such as:
- if the value of the order is more than PLN 300, the customer receives a 5% discount on the purchased goods
- if the customer buys 2 products, the 3rd cheapest product is free of charge
- if the value of the order exceeds PLN 200 the customer receives a free company mug
- a one-time 30% discount voucher for a selected product
- ... and many more yet unknown at this stage of implementation.
 
Promotions may change during the course of the programme, i.e. new ones may appear and existing ones may disappear.

Goods in the shopping basket should be sorted in descending order of price, 
and then by alphabetical order of the product names. 
The way in which the products are sorted can change during the life of the programme and should be simple to implement.  

Your task is to implement logic, operating on objects of type ``Product``, 
that allows you to:
1. Search for the cheapest/most expensive product in a given collection of products
2. Search for the n cheapest/most expensive products in a given product collection
3. Sorting of product collections by price as well as by name
4. Calculation of sum of prices of all given products
Application of the types of promotions described above on a preset collection of products in a shopping cart

Features related to the ``Product`` class:
- product code (code) - String
- product name (name) - String
- product price (price) - double
- product price after discount (discountPrice) - double

---

### Note 1
The project should include appropriate unit tests for the functionality you are implementing.

### Note 2
When implementing the shopping cart and promotions, pay attention to the [Command](https://www.oodesign.com/command-pattern.html) design pattern and the [SOLID](https://pl.wikipedia.org/wiki/SOLID) rules.
