MIS507
======

Online Shopping(Gifts) portal

Proposal:

Our project proposal is to build an online gift delivery system. The system will serve as

an online portal for people to browse through, order and ship gifts. The system would

include suppliers (who hold inventory), buyers (or customers), an online shopping

module and a delivery module. The system will catalog and categorize the different

gifts supplied by different suppliers and provide customers the opportunity to order

(and maybe customize) gifts online. Customers can pay for it online and choose to ship

the products to desired addresses. With regard to design patterns, the team primarily

expects to use the Publisher-Subscriber design pattern, the bridge pattern and the

abstract-factory design pattern to facilitate system functioning. Other design patterns

and system functionalities are expected to be added as the project runs its course.

User Functions:

For our project, we have designated two types of users – customer and administrator.

Different user functions will be implemented depending on the type of user. We will be

implementing the following user functions in our application:

Customer can browse through the list of articles under different categories

Customer can place an order on the articles he chooses

Admin can add, modify or delete new items in the catalog

Admin can also add or delete users as required and modify their roles

A shopping cart function will be implemented to check-out the selected items

Customer can subscribe to alerts on new additions to the catalog or product

changes and offers

Project Milestone 2

Design Patterns:

Following are the design patterns that we propose to use for the project:

Design Pattern

Publisher – Subscriber

Bridge

Addressed Problem

Abstract - Factory

To notify subscribed users of new products added to catalog

To implement user class for customers and admin differently

– the two types of users exhibit different behavior

To instantiate item objects based on specific item categories

Publisher – Subscriber (Observer)

In this design pattern, there is a Publisher class and a set of Subscriber classes which

subscribe to the publisher class. As and when there are changes to the publisher class,

all the subscriber classes are notified of these changes. We plan to use this design

pattern to notify customers of product additions and modifications.

Bridge

This design pattern is used to decouple the abstractions from the implementations of

different classes. We plan to use this design pattern to separate the customers from the

admin as these users have different roles and responsibilities.

Abstract – Factory

This design pattern is used to encapsulate a group of individual factories that have a

common theme, without specifying the concrete classes. We intend to use this pattern

to instantiate the different objects (items) as they belong to different item categories.

Using the design patterns mentioned above, we plan to implement the various user

functionalities of the web portal. As the project progresses and problems need to be

solved, minor changes to the system may be made.