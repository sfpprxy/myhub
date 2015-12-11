# Reflection Report of Joe's Online Food Store

## Application Brief Description
Joe's Online Food Store lets you shop for numerous of foods and check your orders from anywhere that have internet. Browse and shop by adding foods to shopping cart, check out deals, make purchases, and check the status of your orders.

## Use-Case Description
Customer visits the home page and browses foods, then adds a food to his or her shopping cart. Customer continues shopping and check other foods. Customer adds several foods to shopping cart. Customer selects 'view cart' option and updates quantities for cart foods in the cart page. Customer verifies shopping cart contents with summary cost and proceeds to checkout. In the checkout page, customer checks the total cost, fills in personal data (e.g. credit card details), then submits his or her details. The order is processed and customer is taken to a order confirmation page. The confirmation page provides a unique reference number for tracking the customer order, as well as a summary of the order. This order confirmation page can also be seen in the order history page as a record in a list.

## Understanding & Usage of Technologies

#### JSP JSTL
JSP is for front-end presenting that have HTML embedded.
JSTL are useful libraries tags that can use less codes to do the same thing(encapsulate common functions).

#### ORM JPA JDBC
About Java persistence API, I only use JDBC (raw SQL) to access data, because in that case it will help more on understanding how java interacting with database. 

#### MVC
The main advantage of using MVC in web application development is to separate front-end(HTML in jsp) codes and back-end(businesses logic and data access codes in Java) codes and have more readability, modularity and scalability in the future(especially in a team project). Which means if one is familiar with a MVC framework he or she can develop software with higher productivity and quality. Because the system architecture was pre-designed very well.
[]

#### Maven
This project use Maven as the build tool and to manage all dependencies
  - spring-mvc (contains servlet)
  - jdbc
  - mysql
  - junit
  - jetty embedded server
  - jackson-databind (convert web service data into json format)
  - etc

#### Unit Test & results
At first I use System.out.println() for testing, but later it becomes so inefficient and unreliable. So I tried to use junit to simulate the runtime error. Furthermore, by using it I can cover almost every corner case.
[result]

#### Web Service
I use RESTful(via HTTP URI) to allow other application to access my data, which the API is provided by spring-mvc.
[json]

#### About Front-End
I simply use bootstrap(js and css lib) to provide a relatively more professional GUI through html.
[]

#### Version Control
I use git and host the source code in Github:
https://github.com/sfpprxy/java-shop
So the development progress commits are recorded in:
https://github.com/sfpprxy/java-shop/commits/master

## Use-Case Diagram 

## ER Diagram

## Wireframes

## Learning & Problem solving
#### Deviation
In order to implement some hard futures, sometimes I will try new technologies, new methods. But finally I found it only speeds up the efficiency, it does not solve the requirement / problem itself.
#### Make big problem into small problems
I learnt a very useful way of solving problem through this module:
When facing a big problem or debugging. Split it into small problems. If it’s still confusing. Split them into smaller problems. Then there will be solutions already excited. At last, link the small solutions together.
#### Communication
Sometimes I got stuck for days and try to figure out myself but nothing came out. So I ask my teacher, then quickly I got inspired and solve the problem. Therefore, it is important to have communication with others.

## Functionality List - Customer

#### Food list page
  - Display foods
  - Add foods to shopping cart

#### Cart page
  - Update foods quantities
  - View summary of quantities and total price

#### Checkout / payment
  - View summary cost
  - Fill address
  - Using fictitious credit card details
  - Place an order and make payment

#### Confirmation / complete
  - View order details

#### Orders
  - View history orders

#### Registration

#### Login

## Functionality List - Admin

#### Order page
  - View customers’ orders

#### Food organization page
  - Add, Delete, Update food information.
