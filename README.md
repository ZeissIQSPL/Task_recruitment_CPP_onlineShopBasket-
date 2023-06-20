# Task: Online shop basket 

---

Your company has been commissioned to develop software for a large *JavaMarkt* online shop. 
One of the core functionalities is the shopping cart software, 
which can take into account various promotions, discounts and special offers, such as:
- if the value of the order is more than PLN 300, the customer receives a 5% discount on the purchased goods
- if the customer buys 2 products, the 3rd cheapest product is free of charge
- if the value of the order exceeds PLN 200 the customer receives a free company mug
- a one-time 30% discount voucher for a selected product
and many more yet unknown at this stage of implementation. 
Promotions may change during the course of the programme, i.e. new ones may appear and existing ones may disappear.

Goods in the shopping basket should be sorted in descending order of price, 
and then by alphabetical order of the product names. 
The way the products are sorted can change during the course of the programme. 

Your task is to implement logic, operating on objects of type ``Product``, 
that would enable you to:
1. search for the cheapest/most expensive product in a given collection of products
2. search for the n cheapest/most expensive products in a given product collection
3 Sorting of product collections by price as well as by name
4. calculation of sum of prices of all given products
Application of the types of promotions described above on a preset collection of products in a shopping cart

Features related to the ``Product`` class:
- product code (code) - String
- product name (name) - String
- product price (price) - double
- product price after discount (discountPrice) - double

In this task, use an array of products as the collection on which you will operate.

---

### Note 1
The project should include appropriate unit tests for the functionality you are implementing.

### Note 2
When implementing the shopping cart and promotions pay attention to the design pattern [Command](https://www.oodesign.com/command-pattern.html).

### Note 3
When planning a sorting mechanism pay attention to the [Dependency Inversion Principle](https://www.oodesign.com/dependency-inversion-principle.html) .
