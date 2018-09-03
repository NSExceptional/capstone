Deya and the Dudes

Supplementary Specification

Peer Review LTI 

Version 1.1

 

 

 

 

 

Revision History

<table>
  <tr>
    <td>Date</td>
    <td>Version</td>
    <td>Description</td>
    <td>Author</td>
  </tr>
  <tr>
    <td>8/23/18</td>
    <td>1.0</td>
    <td>Initial Version</td>
    <td>Carlos Gamino</td>
  </tr>
  <tr>
    <td>8/26/18</td>
    <td>1.1 </td>
    <td>Editing Initial Version </td>
    <td>Carlos Gamino</td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
  </tr>
  <tr>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
  </tr>
</table>


 

Table of Contents

1. Introduction                                                                                                                             

    1. Purpose                                                                                                                         

    2. Scope                                                                                                                            

    3. Definitions, Acronyms, and Abbreviations                                                                

    4. References                                                                                                                     

    5. Overview      

                                                                                                                 

2. Functionality                                                                                                                            

    6. Administrator

    7. Mediator Role

    8. Initiator Role

    9. User Role (meeting participants)      

                                                                        

3. Security                                                                                                                                   

   

4. Reliability                                                                                                                                 

 	

5. Performance                                                                                                                              

    

6. Supportability                                                                                                                           

7. Design Constraints                                                                                                                   

    10. Hardware Limitations

    11. Software Limitations                                                                            

     

8. Online User Documentation and Help System Requirements                                            

  

9. Purchased Components                                                                                                            

10. Interfaces                                                                                                                        

    12. User Interfaces                                                                                                         

    13. Hardware Interfaces                                                                                                 

    14. Software Interfaces                                                                                                  

    15. Communications Interfaces                                                                                     

11. Licensing Requirements                                                                                                 

12. Legal, Copyright, and Other Notices                                                                            

13. Applicable Standards                                                                                                      

Supplementary Specification

# **1. Introduction**

The Supplementary Specification provides an overview of the entire document. It includes the purpose, scope, definitions, acronyms, abbreviations, references, and overview of this Supplementary Specification. The Supplementary Specification captures the system requirements that are not readily captured in the use cases of the use-case model. Such requirements include:

·Legal and regulatory requirements, including application standards.

·Quality attributes of the system to be built, including usability, reliability, performance, and supportability requirements.

·Other requirements such as operating systems and environments, compatibility requirements, and design constraints.

## **     1.1 Purpose**

The purpose of the Supplementary Specification is to capture the system requirements that are not readily captured in the use cases of the use-case model. It includes requirements such as legal and regulatory requirements, application standards, quality attributes of the system to be built (usability, reliability, performance, and supportability requirements) and other requirements such as operating systems and environment, compatibility requirements and design constraint.

## **     1.2 Scope**

This Supplementary Specification applies to the LTI plugin that allows for peer reviews, which will be developed by "Deya and the Dudes" Capstone Team.  The DnD team will develop a customizable, centralized system that allows individuals or organizations; to easily, efficiently, and precisely schedule and assign Peer Review Worksheets to team members in accordance with practical limitations of virtual and real-world groups. The scope of this document does not include describing fully what the software system will do, but on how it will perform actions, by describing nonfunctional requirements such as security, reliability, extensibility, and performance.

## **     1.3 Definitions, Acronyms, and Abbreviations**

**Active participant:** A user, who is also an attendee, whose role in the meeting requires them perform an action.

 

**Administrator:** is a privileged user who is responsible for managing user accounts, and managing resources (ex. adding or removing users).

 

**Attendee:** a user, who receives a peer review invite, and is responsible for either accepting or declining the invite. In the case the invite is accepted, the attendee is required to provide an exclusion and preference set. An attendee can be furthermore classified as important or active participant.

 

**Concurrency:** the ability to handle more than one meeting requests at same time.

 

**Confirmation:** A notification sent to attendees by the initiator confirming the peer review.

 

**COTS:** Commercial of-the-shelf. A software product that is ready-made and available for sale.

 

**Customer:** Aars

 

**Date conflict: **occurs when no available date can be found in the stated date range.

 

**Date range:** time interval specified by the initiator in which the peer review should take place, this also serves as the boundaries for the exclusion and preference sets.

 

**Date set:** a pair of input values, including calendar date and time period.

 

**End customer:** person, or organization, that buys the TLI software.

 

**Exclusion set**: a set of dates on which the attendees are not available to attend a perform the peer review.

 

**GUI:** Graphical User Interface.

 

**Internationalization (I18N)**: The process of designing a software application so that it can be adapted to various languages and regions without engineering changes.

 

**Important participant:** A user, who is also an attendee, whose attendance at the peer review is necessary for the peer review to take place.

 

**Initiator:** The user who calls for the peer review.

 

**Initiator representative:** A user who is delegated to act on behalf of the initiator.

 

**Invite:** A peer review request sent by an initiator or representative to the potential attendees, which includes meeting topic, date range and requires attendees to respond with their preferences regarding date.

 

**Localization (L10N):** The process of adapting software for a specific region or language by adding locale-specific components and translating text.

 

**Nomadicity: **The ability to move from one location to another and start communications from any location.

 

**Preference set:** a set of dates on which the attendees would prefer the peer review to take place.

  

**Strong date conflict: **This occurs when no date can be found within the date range and outside all exclusion sets.

**Time interval:** a period of time with defined limits. For the purposes of the system, limits are defined in 15 minutes increments (e.g. 8:15 am, 8:30 am, 8:45 am & 9:00am)

 

**UML:** Unified Modeling Language

 

**User:** A person who interacts directly with the product. A user can have different roles with respect to the system (e.g. administrator, mediator, regular user) and meeting events (e.g. initiator, attendee, active participant, or important participant).

 

**Weak date conflict: **This occurs when dates can be found within the date range and outside all exclusion sets, but no date can be found which coincides with all preference sets.

 

**Weak location conflict:** This occurs when the available locations do not coincide with the preferred locations.

## **     1.4 References**

     N/A

## **     1.5 Overview**

The Supplementary Specification document is composed of different sections including Functionality, Security, Reliability, Performance, Supportability, Design Constraints, Online User Documentation and Help System Requirements, Purchased Components, Licensing Requirements, Legal, Copyright, and Other Notices, Applicable Standards.

The Functionality Requirements describes requirements of the systems which are expressed in the natural language style. This section will be organized by features or by users or organizations by subsystem.

Security Section includes all of the requirements that affect security.

Reliability section describes about availability (percentage of time available, hours of use, and maintenance access), mean time between failures, how long is the system allowed to be out of operation after it has failed, accuracy, maximum bugs, defect rate.

Performance sections uses figures to describe the performance characteristics of the system.

Extensibility section indicates any requirements such as scalability and customizability.

Design Constraints indicates any design constraints on the system being built. Such as software languages, software process requirements, prescribed use of developmental tools, architectural and design constraints.

Online user documentation describes the requirements for online user documentation and help systems requirements. 

Purchased Components describes any purchased components to be used with the system , any applicable licensing or usage restrictions, and any associated compatibility/interoperability or interface standards.

Licensing Requirements, Legal, Copyright, and Other Notices section describes any necessary legal disclaimers, warranties, copyright notices, patent notice, wordmark, trademark, or logo compliance issues for the software.

Applicable Standards section describes by reference any applicable standards and the specific sections of any such standards that apply to the system being described.

# **2. Functionality**

## **2.1	Administrator**

###     *2.1.1   The system shall allow the administrator to add users.*

### *    2.1.2   The system shall allow the administrator to modify user information.*

### *    2.1.3   The system shall allow the administrator to remove users.*

### *    2.1.4   The system shall allow the administrator to modify information from a physical location.*

## **2.3	Initiator role**

### *    2.3.1   The system shall allow the initiator to send peer reviews..*

### *    2.3.2   The system shall allow the initiator to view the information of any peer reviews which they initiated.*

### *    2.3.3   The system shall allow the initiator to cancel any peer reviews which they initiated.*

### *    2.3.4   The system shall allow the initiator to modify any of the following information for a peer review which they initiated.*

### *    2.3.5   The system shall allow the initiator to perform the following conflict resolution activities for a peer review they have initiated.*

### *    2.3.6   The system shall allow the initiator to send and receive messages from users.*

### *    2.3.7   The system shall allow the initiator to consider specific criteria to schedule a peer review.*

## **2.4	User role**

### *2.4.1	The system shall authenticate users at the beginning each session.*

### *2.4.2	The system shall allow the user to view their peer review.*

### *2.4.3	The system shall notify the user of any peer review changes.*

### *2.4.4	The system shall allow users to send and receive messages.*

### *2.4.5	The system shall request a user response to initiator or mediator messages.*

### *2.4.6	The system shall allow the user to modify the date preference set of an already submitted peer reviews.*

### *2.4.7	The system shall allow the user to change the password.*

### *2.4.8	The system shall allow the user to change personal contact information.*

### *2.4.9	The system shall allow the user to customize the interface settings.*

### *2.4.10	The system shall allow the user to view past peer reviews.*

### *2.4.11	The system shall allow the user to search past peer reviews.*

### *2.4.12	The system shall allow the user to view pending peer reviews.*

### *2.4.13	The system shall allow the user to search pending peer reviews.*

### *2.4.14	The system shall show the peer reviews to the user in ascending time order by default.*

### *2.4.15	The system shall allow users to search for other users by given criteria.*

### *2.4.16	The system shall allow users to view other users’ information.*

### *2.4.17	The system shall allow user to specify custom peer reviews.*

### *2.4.18    The system shall allow users to act on behalf of another user.*

# **3. Security**

#### The security softgoal is divided into confidentiality, integrity, and availability. To cover confidentiality it’s important to achieve authentication, users are required to log into the system by providing username and with strong password, it also provides site key and account lockdown to prevent unauthorized users. Integrity covers completeness such as data validation, accuracy, and consistency. And availability provides protection against DOS attack relays on the firewall, see figure below.

## **3.1	Security requirement:**

### *3.1.1    Given requirements, "…and information about peer reviews should be secure" the system will have to meet the following:*

#### *3.1.1.1	The SDMS shall utilize HTTPS communication to ensure data confidentiality.*

#### *3.1.1.2	User authentication and privileges are defined outside the scope of the SDMS by the Microsoft Active Directory Server.*

#### *3.1.1.3	Personal information security is defined outside the scope of the SDMS by the database server.*

#### *3.1.1.4	Users shall be required to log into the system for all operations except the operations on the login page.*

#### *3.1.1.5	The system shall restrict the user's operation within its user role.*

# **4. Reliability**

#### The reliability softgoal is divided into accuracy, integrity, and availability. Accuracy involves consistency and availability provides protection against DOS attack relays on the firewall. Integrity covers completeness such as data validation, efficiency, and consistency. And availability provides protection against DOS attack relays on the firewall, see figure below.

## **4.1 Reliability Requirement**

### *1.1.1	The SDMS should store and retrieve information accurately as provided by the user.*

### *1.1.2	In the event a user’s session times out, any task which requires future dependent information shall be cancelled.*

# **5. Performance**

#### One of the most important nonfunctional requirements customers wants is a system with good  and fast performance rate. Therefore, the performance goal is divided into three subgoals: time, space, and responsive. Time is divided into throughput time and response time (when using indexing). There are two level of indexing multi-level and single-level. Single-level is based on categories and keyword. A claim of response time is that indexing improves responses time when retrieving. Responsive subgoal deals on how fast the system responds to queries, and space subgoal with storage space. Storage space should not be wasted in order to achieve a good performance.

## **5.1 Performance Requirement**

### *5.1.1	The SDMS web application shall add no more than 5 seconds of perceivable overhead time to any necessary web and database transaction time.*

### *5.1.2	In the event the complete SDMS transaction requires longer than 5 seconds, the system shall display an informational messages requesting they continue waiting for a response. [6]*

### *5.1.3	In the event the complete SDMS transaction takes more than twice the expected duration, derived from empirical data (system characterization), for a given type of transaction, the SDMS will inform the user that the transaction has failed.*

# **6. Supportability**

## **6.1 Supportability Requirement**

### *6.1.1	The SDMS will provide an API to allow third-party developers to extend the abilities of the SDMS and include it into their own program.*

### *6.1.2	The system shall provide a documentation framework to support scalability.*

### *6.1.3	The system shall support I18N and L10N by configuration files and language package files.*

### *6.1.4     **The system shall support different time zone and time format.*

# **7. Design Constraints**

## **1.1 Hardware Limitations**

### **   ***  1.1.1   The SDMS hardware limitations are defined by the limitations of its support web server and database server.*

## **1.2 Software Limitations**

### **  ***  1.2.1   The SDMS software limitations are defined by the limitations of its support web server and database server.*

# **8. Online User Documentation and Help System Requirements**

#### Online support concerning administration issues & user tutorials including "How to" guides and “Tip of the Day” will be available. 

#### Readme files and release notes are to be delivered to the customer in each release.

#### User guides and Administration guides are to be provided per customer request.

# **9. Purchased Components**

#### All software used to develop the SDMS will comply to the software license agreement.

#### Microsoft Software Agreement: ASP.NET, Microsoft Windows Server

#### Open source Agreement: GNU GPL

# **10. Interfaces**

## **10.1 User Interfaces**

### *1.1.1	All interaction with the SDMS will occur through a web-based interface.*

### *1.1.2	The SDMS will be accessed through a secure user interface requiring the use of a predetermined login name and password.*

### *1.1.3	Any unexpected system operation will be announced to the user with an error web page stating the cause of the error. In the event that a cause can not be readily determined a generic error message will be presented.*

### *1.1.4	The layout of the web interface will conform to a standard screen resolution of 1024x768.*

## **10.2 Hardware Interfaces**

### *1.1.1	The SDMS will interact only with the provided web server and database server. Any additional system interaction will be handled directly by the operating system and any other supporting software systems.*

## **10.3 Software Interfaces**

### *1.1.1	The SDMS will interface with Microsoft SQL Server for database interactions*

### *1.1.2	The SDMS will utilize Microsoft IIS 6.0 Web Server to deliver HTML content to clients*

### *1.1.3	The SDMS will access Microsoft Active Directory via the LDAP protocol for user authentication.*

### *1.1.4	The SDMS will provide support for communication with Microsoft Exchange Servers for email notification and calendar synchronization.*

### *1.1.5	The SDMS will provide support for database interaction with a third-party property management system.*

### *1.1.6	The SDMS will provide a standardized API so that third-party programs may access information programmatically from the SDMS system.*

## **10.4 Communications Interfaces**

*10.4.1   **The ASP.Net framework will provide systems for HTTP and HTTPS interactions with the web server.*

# **11. Licensing Requirements**

#### N/A 

# **12. Legal, Copyright, and Other Notices**

#### The following are the disclaimers, terms and conditions for use of the SDMS. By using Online Meeting System you are accepting that you are bound by the disclaimers, terms and conditions set forth below.

####  The product will be part of open source under GNU GPL (GNU General Public License). GPL states that everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed.

#### Software will be built with use of Microsoft products and therefore comply with Microsoft Software License. Distribution of any portion of the software is not allowed unless profits are made on behalf of Synergy. All copyright, trademark, and a patent notices that are present in the software must be followed.

# **13. Applicable Standards**

#### All documentation should meet IEEE and RUP standards.

#### ASP.NET 2.0 and web standards.

