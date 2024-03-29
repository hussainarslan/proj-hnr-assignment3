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

## Meeting 3 - 4/12/22
###  Attendees
* Hussain
* Noureen
* Rakeen

###  Meeting Notes
* Merged our closed issues
* Discussed what we learnt
* How we will implement in future projects?

------------------------------------------------------------------------------
## Process Requirements in Open Sources Projects 
### Explored by: Noureen Fatima

### Issue 7: Study about Versioning and Release Management 
Identification and tracking of system versions are key components of the version and release management process. The purpose of such processes is to **prevent the development team from unintentionally changing versions of a system that may be retrieved when needed.**

Versions of the system could possibly have altered functionality, improved performance, or fixed software bugs. Although they may work similarly, several versions may be made for various hardware or software configurations.


* **Variants** are occasionally used to describe versions that only have slight changes.
* A distributed version of a system is also referred to as a **system release**. Every system update should either bring in new features or be tailored to a certain hardware platform.
* A system typically has far more releases than versions. **Versions** are produced by a company for internal testing or development purposes only; they are not meant for customer release.
* **Version identification:** You must define the versions of the system components that should be included in a system in order to produce a particular version of that system. There are hundreds of software components in a complex software system, and each one could have numerous different versions. To ensure that the proper components are used in the system, there must be a clear means to identify each component version.

### Issue 8: Study Techniques for Component Version Identification
* **Version Numbering:** In a version numbering scheme, the component or system name is followed by a version number. If version 1.0, then versions 1.1, 1.2, and so forth will follow. At some point, a new release (release 2.0) is made, and the process starts over at version 2.1. The plan is linear and is based on the notion that system versions are produced one after another. This method of version identification is supported by the majority of version management software, including RCS and CVS. ![image link](https://media.geeksforgeeks.org/wp-content/uploads/20210107091720/517.png)

* **Attribute Based Identification:** It is simple to add new versions that are descended from any of the existing versions if each version is recognised by a distinct set of attributes. These are recognised by means of a distinctive set of attribute values. Most of the attributes are shared with their parent version, preserving linkages between versions. By indicating the necessary property values, specific versions can be retrieved. The last version created or the version created between supplied dates are supported via functions on attributes. Version management systems may implement attribute-based identification directly, with component attributes preserved in a system database. Alternately, a secret version-numbering technique may be developed as a layer on top of the attribute identification system.

* **Change Oriented Identification:** In attribute-based identification, each component is referred to by its name, but it also has a connection to one or more modification requests. Consequently, it is presumptive that each version of a component was developed in response to one or more change requests. Change requests that pertain to components are used to identify a component's version.

### Issue 9: Explore versioning in [Webswing](https://www.webswing.org/docs)
* All the releases are accessible on the website. For example, from release **20.1 to 22.2**.
* Not only each release is mentioned, but also all installation guides, and release notes are present. 
* Dates are also mentioned in each version’s release.
* Moreover all the major changes are mentioned. 
* **Conclusion:** Webswing manages its releases and versions very well. Everything is organized and easy to understand. Everything is well documented.
![image link](https://github.com/karissa-kaal/random/blob/main/Webswing1.jpg?raw=true)

### Issue 13: Explore Versioning in [Open CV](https://docs.opencv.org/)
* All the releases are available to download, also the upcoming releases are also listed.
* Not easy to differentiate between different releases and versions. 
* Each version is documented properly.
![image link](https://github.com/karissa-kaal/random/blob/main/OpenCV1.jpg?raw=true)

### Issue 15: Explore Versioning in [StoreFront UI](https://docs.storefrontui.io/?path=/docs/welcome--page)
* Storefront UI has Change Log documented for each release, which is a good practice.
* The Change Log includes 
   - Breaking Changes
   - Features
   - Fixes
   - Chores
![image link](https://github.com/karissa-kaal/random/blob/main/StorefrontUI1.jpg?raw=true)

### Issue 17: Explore [Ansible](https://docs.ansible.com/ansible-core/devel/dev_guide/index.html) Issue Management
* Ansible has **606** [labels](https://github.com/ansible/ansible/labels) to differentiate between their issues.  
* **632** issues are open and 30,350 are closed
![image link](https://github.com/karissa-kaal/random/blob/main/Ansible1.jpg?raw=true)
* Issues also have tasks to better track the progress of an issue.
![image link](https://github.com/karissa-kaal/random/blob/main/Ansible2.jpg?raw=true)
* When the person checks a checkbox, a task will be completed. These checkboxes are tasks.

### Issue 22: Explore [Jenkins](https://www.jenkins.io/doc/developer/) Issue Management
* **41** Labels are used to manage issues as in Ansible 
![image link](https://github.com/karissa-kaal/random/blob/main/Jenkins1.jpg?raw=true)

### Issue 31: Study Open Source Contribution Req. for developers
[**Ansible**](https://docs.ansible.com/ansible/devel/dev_guide/developing_modules_checklist.html)

![image](https://user-images.githubusercontent.com/82564664/205503811-505326fb-9f41-4155-9fd8-560a56360993.png)

### Issue 32: Study Review Process in Open Source Projects
* In Ansible, the pull requests have **85** checks to fulfill. If it passes the checks, a **green tick** is displayed, else a **red cross** is displayed.
* There are certain labels that bring attention to the issues that need to be addressed or verified.

![image](https://github.com/karissa-kaal/random/blob/main/Ansible4.jpg?raw=true)

------------------------------------------------------------------------------
## Documentation Needs in Open Source Projects
### Explored by: Noureen Fatima

### Issue 40: Exploring User Manual
[Jenkins](https://www.jenkins.io/doc/book/getting-started/)

* Jenkins User Manual can be easily traversed and studied. 
* All the given points are well explained and some include tutorials too.

![image](https://user-images.githubusercontent.com/82564664/205505114-c8a344f8-ebaa-4ce9-adaf-90c710b06c75.png)

### Issue 41: Exploring Installation/Deployment Document 
[Store Front Installation Guide](https://docs.storefrontui.io/?path=/docs/getting-started-installation--page)

![image](https://user-images.githubusercontent.com/82564664/205505427-2b53aa72-9e19-4234-b8b1-ed01c526b33f.png)

[Jenkins Installation Guide](https://www.jenkins.io/doc/book/installing/)

Jenkins smartly provides installation guidelines for different environments including macOS, Windows etc.

![image](https://user-images.githubusercontent.com/82564664/205505499-982b5487-41b6-4d89-aca7-c32d8f9c75af.png)

### Issue 42: Exploring Development/Extension Document

[Ansible](https://docs.ansible.com/ansible-core/devel/dev_guide/index.html)

[Woocommerce](https://woocommerce.com/documentation/plugins/woocommerce/woocommerce-codex/)

[Teammates](https://teammates.github.io/teammates/setting-up.html)

Step wise development guidelines are provided.

### Issue 43: Exploring Tutorials
[StorFront UI Tutorial](https://youtu.be/e2ysjL5G77Y)
[Jenkins](https://youtu.be/yfjtMIDgmfs)

------------------------------------------------------------------------------
## Architectural and Component Level Modularity in Open Source Projects
### Explored by: Hussain Arslan

### Issue 3: Microservices
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
   - Improved maintainability - each service is relatively small and so is easier to understand 
   and change
   - Better testability - services are smaller and faster to test
   - Better deployability - services can be deployed independently
   - It enables you to organise the development effort around multiple, autonomous teams. Each 
   (so called two pizza) team owns and is responsible for one or more services. Each team can 
   develop, test, deploy and scale their services independently of all of the other teams.

6. Each microservice is relatively small:
   - Easier for a developer to understand
   - The IDE is faster making developers more productive
   - The application starts faster, which makes developers more productive, and speeds up 
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

### Issue 4: Extensibility
* **What is Extensibility?**

Extensibility is a software engineering and systems design principle that provides for future growth. Extensibility is a measure of the ability to extend a system and 
the level of effort required to implement the extension. Extensions can be through the addition of new functionality or through modification of existing functionality. 
The principle provides for enhancements without impairing existing system functions.

An extensible system is one that is not affected by modifications in functionality and retains current behaviour

* **Extensibility in VueStorefront**

VueStorefront has a lot of integrations which add on to the basic functionality of VueStorefront 
and their addition does not affect the base functionality. All of these make Vue Storefront 
highly extensible. These integrations are available on the link below:

[Integrations - VueStorefront](https://docs.vuestorefront.io/v2/integrations/)

### Issue 5: Reusability
* **What is Reusability?**

Reusability is the use of existing assets in some form within the software product development 
process. These assets are products and by-products of the software development life cycle and 
include code, software components, test suites, designs and documentation. The opposite concept 
of reusability is leverage, which modifies existing assets as needed to meet specific system 
requirements.

* **Reusability in Ansible**

Ansible has implemented reusability in a very intuitive and effective way. Ansible offers two 
ways to reuse files and roles in a playbook: dynamic and static. Ansible offers four 
distributed, reusable artefact: variable files, task files, playbooks, and roles.

1. A variables file contains only variables.
2. A task file contains only tasks.
3. A playbook contains at least one play, and may contain variables, tasks, and other content. 
You can reuse tightly focused playbooks, but you can only reuse them statically, not 
dynamically. 
4. A role contains a set of related tasks, variables, defaults, handlers, and even modules or 
other plugins in a defined fil-tree. Unlike variable files, task files, or playbooks, roles can 
be easily uploaded and shared through Ansible Galaxy.

In ansible, you can even incorporate multiple playbooks into a main playbook. However, you can 
only use imports to reuse playbooks. Importing incorporates playbooks in other playbooks 
statically. Ansible runs the plays and tasks in each imported playbook in the order they are 
listed, just as if they had been defined directly in the main playbook.

------------------------------------------------------------------------------
## Performance Optimizations in Open Source Projects
### Explored by: Hussain Arslan

### Issue 10: Usage of Lazy Loading
* **What is lazy loading?**

Lazy loading is the practice of delaying load or initialization of resources or objects until 
they’re actually needed to improve performance or save system resources. Lazy loading is a 
technique used to prevent or delay the loading of non-critical resources until they are needed. 

* **Usage of lazy loading in VueStorefront**

In vue storefront lazy loading can be used for different types of resources, but in the case of 
images, the goal is to lazily load everything that is not visible to the user within the initial 
viewport. All other images can be loaded when the user scrolls down the page. A code snippet for 
this can be found on the following link

[Optimizing images | Vue Storefront 2](https://docs.vuestorefront.io/v2/performance/optimizing-images.html)

### Issue 11: Usage of Cache
* **What is cache?**

A cache is a software or hardware component aimed at storing data so that future requests for 
same data can be served faster. The main reason why caching was born is that accessing data from 
persistent memories takes a considerable amount of time

* **Usage of cache in WooCommerce**

WooCommerce adds dynamic pages to your website including the Cart, Checkout and My Account page. 
When you cache content on your website, it’s saved to the user’s device which means it’s no 
longer dynamic. Their web browser will serve them the same page that was cached each time. 
Consequently, customers will never see the correct information on their cart or checkout pages.

[Best Caching Plugins for WooCommerce - CommerceGurus](https://www.commercegurus.com/best-woocommerce-caching-plugins/#:~:text=WooCommerce%2C%20on%20the%20other%20hand,that%20was%20cached%20each%20time.)

### Issue 12: Usage of Content Delivery Network
* **What are content delivery networks?**

Content Delivery Networks(CDNs can help protect a site by providing TLS and/or SSL certificates that ensure a high standard of authentication and encryption. In 
addition, CDNs can help protect your websites and apps through a Web Application Firewall(WAF). A CDN refers to a geographically distributed group of servers that work 
together to provide fast delivery of Internet content.

* **Content Delivery Networks(CDNs in VueStorefront)**

VueStrorefront uses Google Cloud CDN to improve site performance as it supports modern protocols initially developed at Google, like HTTP/2 and QUIC. Google Cloud CDN 
enables websites to serve millions of requests per day seamlessly taking care of delivering superb use experience across all touchpoints.

[Features | Vue Storefront Cloud](https://docs.vuestorefront.io/cloud/v2/in-a-nutshell/features.html)

------------------------------------------------------------------------------
## Security Requirements in Open Source Projects
### Explored by: Rakeen Zia

### Issue 5: What is Security?
In Software Engineering terms, Security is defined as an ongoing process involving people and practices, and ensuring application confidentiality, integrity and availability. Security is the most effective when it is properly planned for and integrated within a software development lifecycle.

The basic guiding principles to software security are as follows and their implementation is also very important:

* Protection from disclosure
* Protection from alteration
* Protection from destruction
* Who is making the request
* What rights and privileges does the requester have
* Ability to build historical evidence
* Management of configuration, sessions and errors/exceptions

### Issue 20: Exploring security implementation in Jenkins
Jenkins has four security methods to make sure that the administrator of Jenkins can control who gets access to what specific parts of Jenkins. There as follows:
* Permissions
* Authentication:
* When a thread runs in Jenkins, it will always have an authentication object attached to it which will represent the user which thread is currently serving.
* ACL(deciding whether authentication object carried by thread has permission)
* AccessControlled(Implemented by an object that owns ACL)
 
There are also plugins which do certain things that protect certain web methods. The ways to protect web methods are as follows:
* Identity certain operations in code that can cause change in state of server or disclose private information. These methods should perform checkPermission.
* Identify nearest AccessControlled objects to check  check permissions with.
* Identify the Permission object to use.
 
Jenkins will also change page rendering according to the permissions of the user. If a user doesn't have relevant permissions then certain elements of the page will not load for the user.
 
Authentication ways:
* Web UI
* REST API(login/password)
* Jenkins CLI jar
* CLI over SSH

[Security - Jenkins](https://docs.vuestorefront.io/v2/integrations/](https://www.jenkins.io/doc/developer/security/)

------------------------------------------------------------------------------
## Reliability Requirements in Open Source Projects
### Explored by: Rakeen Zia

### Issue 19: What is Reliability?
Software Reliability means Operational reliability. It is described as the ability of a system or component to perform its required functions under static conditions for a specific period.
Software Reliability is an essential connection of software quality, composed with functionality, usability, performance, serviceability, capability, installability, maintainability, and documentation. Software Reliability is hard to achieve because the complexity of software turns out to be high. While any system with a high degree of complexity, containing software, will be hard to reach a certain level of reliability, system developers tend to push complexity into the software layer, with the speedy growth of system size and ease of doing so by upgrading the software.

### Issue 26: Exploring reliability in Jenkins
Jenkins has implemented rigorous testing to make sure that reliability standards are met. Jenkins comes with a test harness which is based on JUnit test framework which provides following features:
* Automated setup and teardown of the environment allowing tests to run in a clean environment.
* Helper classes and methods
* Declarative annotations to specify environment test method will use
* Direct access to Jenkins object model
* HtmlUnit support allowing to test webUI interaction

All tests must be placed in standard location of maven projects which is src/test/java/

Tests can be run from either the command line by typing ‘mvn test’ or through the use of an IDE.

Common test patterns include:
* Configuration Round-Trip Testing where users have to configure project via the web interface
Data used in testing is either from a dummy SCM or from within a pipeline.

There is also Performance testing in Jenkins to make sure that performance requirements such as speed and return time meet the standard.

[Testing - Jenkins](https://docs.vuestorefront.io/v2/integrations/](https://www.jenkins.io/doc/developer/security/](https://www.jenkins.io/doc/developer/testing/)
