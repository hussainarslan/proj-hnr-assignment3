# proj-hnr-assignment3

Group Members:

* M. Hussain Arslan 20L-1266
* Noureen Fatima 20L-0956
* M. Rakeen Zia Raja 20L-0969

------------------------------------------------------------------------------

## Meeting 1 - 25/11/22
###  Attendees
* Hussain
* Noureen
* Rakeen

###  Meeting Notes
* Discussed what we are doing in this asssignment
* Made initial milestones and divided them amoung ourselves
* Made small tasks as issues in each milestone
* Explored open source projects to study these requirements

------------------------------------------------------------------------------

## Meeting 2 - 3/12/22
###  Attendees
* Hussain
* Noureen
* Rakeen

###  Meeting Notes
* Resolved initial queries
* Discussed what we have learnt
* Everyone explained their learnings
* In order to meet the deadline, meeting was brief and everyone was asked to work on their own tasks and catch up on 4/12/22 evening.

------------------------------------------------------------------------------
## Process Requirements in Open Sources Projects 
### Explored by: Noureen Fatima

### Issue 1: Study about Versoning and Release Management 
Identification and tracking of system versions are key components of the version and release management process. The purpose of such processes is to **prevent the development team from unintentionally changing versions of a system that may be retrieved when needed.**

Versions of the system could possibly have altered functionality, improved performance, or fixed software bugs. Although they may work similarly, several versions may be made for various hardware or software configurations.


* **Variants** are occasionally used to describe versions that only have slight changes.
* A distributed version of a system is also referred to as a **system release**. Every system update should either bring in new features or be tailored to a certain hardware platform.
* A system typically has far more releases than versions. **Versions** are produced by a company for internal testing or development purposes only; they are not meant for customer release.
* **Version identification:** You must define the versions of the system components that should be included in a system in order to produce a particular version of that system. There are hundreds of software components in a complex software system, and each one could have numerous different versions. To ensure that the proper components are used in the system, there must be a clear means to identify each component version.

------------------------------------------------------------------------------
##Architectural and Component Level Modularity in Open Source Projects
###Explored by: Hussain Arslan

###Issue 3: Microservices
* **What are microservices?**
Microservices are an architectural and organisational approach to software development where software is composed of small independent services that communicate over
well-defined APIs. These services are owned by small, self-contained teams.

* **Benefits of microservices**
1. Highly maintainable and testable - enables rapid and frequent development and deployment

2. Loosely coupled with other services - enables a team to work independently the majority of 
time on their service(s) without being impacted by changes to other services and without 
affecting other services

3. Independently deployable - enables a team to deploy their service without having to 
coordinate with other teams

4. Capable of being developed by a small team - essential for high productivity by avoiding the 
high communication head of large teams

5. Enables the continuous delivery and deployment of large, complex applications.
   -Improved maintainability - each service is relatively small and so is easier to understand 
   and change
   -Better testability - services are smaller and faster to test
   -Better deployability - services can be deployed independently
   -It enables you to organise the development effort around multiple, autonomous teams. Each 
   (so called two pizza) team owns and is responsible for one or more services. Each team can 
   develop, test, deploy and scale their services independently of all of the other teams.

6. Each microservice is relatively small:
   -Easier for a developer to understand
   -The IDE is faster making developers more productive
   -The application starts faster, which makes developers more productive, and speeds up 
   deployments

7. Improved fault isolation. For example, if there is a memory leak in one service then only 
that service will be affected. The other services will continue to handle requests. In 
comparison, one misbehaving component of a monolithic architecture can bring down the entire 
system.

8. Eliminates any long-term commitment to a technology stack. When developing a new service you 
can pick a new technology stack. Similarly, when making major changes to an existing service you 
can rewrite it using a new technology stack.

* **Microservices in WooCommerce**
Considering all the information above about microservices, WooCommerce has implemented these to 
supplement the user experience and make it easier to add a lot of different functionalities to 
their product by using them. Some of these examples include eBay integration for WooCommerce, 
estimated delivery date and time and even currency switcher. 

[Plugins - WooCommerce - WooCommerce](https://woocommerce.com/documentation/plugins/woocommerce/)

Above is a link for some plugins that are used by WooCommerce and may be considered 
microservices. Furthermore, there are some APIs used by WooCommerce. These include Stripe, 
WooSidebars, In Stock Notifications, Pre-Orders and Google Listings & Ads.

[Extensions - API Manager - WooCommerce](https://woocommerce.com/documentation/woocommerce-extensions/api-manager/)
