# Reflection Report of Joe's Online Food Store

## Application Brief Description
Joe's Online Food Store lets you shop for numerous of foods and check your orders from anywhere that have internet. Browse and shop by adding foods to shopping cart, check out deals, make purchases, and check the status of your orders.

## Use-Case Description
Customer visits the home page and browses foods, then adds a food to his or her shopping cart. Customer continues shopping and check other foods. Customer adds several foods to shopping cart. Customer selects 'view cart' option and updates quantities for cart foods in the cart page. Customer verifies shopping cart contents with summary cost and proceeds to checkout. In the checkout page, customer checks the total cost, fills in personal data (e.g. credit card details), then submits his or her details. The order is processed and customer is taken to a order confirmation page. The confirmation page provides a unique reference number for tracking the customer order, as well as a summary of the order. This order confirmation page can also be seen in the order history page as a record in a list.

## Understanding & Usage of Technologies

#### JSP JSTL
#### ORM JPA JDBC
#### MVC
Servlet 
#### Maven
I use Maven as the build tool and to manage all dependencies
  - mysql
  - jdbc
  - junit
  - spring-mvc
  - jetty embedded server

#### Unit Test
#### Web Service
#### About Front-End
#### Version Control

## Use-Case Diagram 
 See here: https://github.com/sfpprxy/java-shop/blob/master/README.md#use-case-diagram
 ![use case diagram](https://raw.githubusercontent.com/sfpprxy/myhub/master/java-project/Use%20Case%20Diagram.png)
 
## Wireframes
 See here: https://github.com/sfpprxy/java-shop/blob/master/README.md#wireframes
 ![food](https://raw.githubusercontent.com/sfpprxy/myhub/master/java-project/food.png)
 ![cart](https://raw.githubusercontent.com/sfpprxy/myhub/master/java-project/cart.png)
 ![checkout](https://raw.githubusercontent.com/sfpprxy/myhub/master/java-project/checkout.png)
 ![confirm](https://raw.githubusercontent.com/sfpprxy/myhub/master/java-project/confirm.png)
 ![orders](https://raw.githubusercontent.com/sfpprxy/myhub/master/java-project/orders.png)
 
## ER Diagram

 
## Learing & Problem solving
#### don't change the requirements
#### make big problem into small problems
one thing at a time
#### don't do everthing your self, talk to others

## Functionality List - Customer

#### Home - display
  - Display category

#### Food list - display
  - Display foods
  - Add foods to shopping cart

#### Cart / cart - update
  - Update foods quantities
  - View summary of quantities and total price

#### Checkout / payment - update
  - View summary cost
  - Fill address
  - Using fictitious credit card details
  - Place an order and make payment

#### Confirmation / complete - display

#### Orders - display
  - View history orders

#### Registration

#### Login

## Functionality List - Admin

#### Order page
  - View customers’ orders

#### Food organization page
  - Add, Delete, Update food
