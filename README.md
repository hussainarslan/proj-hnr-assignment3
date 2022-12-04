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

### Issue 9: Explore versioning in Webswing
* All the releases are accessible on the website. For example, from release **20.1 to 22.2**.
* Not only each release is mentioned, but also all installation guides, and release notes are present. 
* Dates are also mentioned in each version’s release.
* Moreover all the major changes are mentioned. 
* **Conclusion:** Webswing manages its releases and versions very well. Everything is organized and easy to understand. Everything is well documented.
![image link](https://github.com/karissa-kaal/random/blob/main/Webswing1.jpg?raw=true)
