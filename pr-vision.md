# Peer Review Vision Document
Deya and The Dudes  
Version 1.5


## Revision History

<table>
  <tr>
    <td>Date</td>
    <td>Version</td>
    <td>Description</td>
    <td>Author</td>
  </tr>
  <tr>
    <td>08/23/2018</td>
    <td>1.0</td>
    <td>Creation of Rough Draft</td>
    <td>Deyanira Gomez</td>
  </tr>
  <tr>
    <td>08/23/2018</td>
    <td>1.1</td>
    <td>Filled in most info</td>
    <td>Tanner Bennett</td>
  </tr>
  <tr>
    <td>08/26/2018</td>
    <td>1.2</td>
    <td>Slight addition of assumptions</td>
    <td>Carlos Gamino</td>
  </tr>
  <tr>
    <td>8/27/2018</td>
    <td>1.3</td>
    <td>Add to Stakeholder information and User Needs</td>
    <td>Deyanira Gomez</td>
  </tr>
  <tr>
    <td>8/27/2018</td>
    <td>1.4</td>
    <td>Changed wording and fixed spelling mistakes</td>
    <td>Justin Ritter</td>
  </tr>
    <tr>
    <td>8/27/2018</td>
    <td>1.5</td>
    <td>Converted to Markdown</td>
    <td>Tanner Bennett</td>
  </tr>
</table>
 

## Table of Contents

1. Introduction  
	1.1 References
2. Positioning  
	2.1 Problem Statement  
	2.2. Product Position Statement  
3. Stakeholder and User Descriptions  
	3.1 Stakeholder Summary  
	3.2 User Summary  
	3.3 User Environment  
	3.4 Summary of Key Stakeholder or User Needs  
	3.5 Alternatives and Competition  
4. Product Overview  
	4.1 Product Perspective  
	4.2 Assumptions and Dependencies  
	4.3 User Criteria Selection  
5. Product Features  
6. Other Product Requirements  

## Vision
### 1. Introduction

This document provides coverage over the vision prepared for the creation of an LTI for taking peer reviews within Canvas, Moodle, ect. (referred to just as *‘Learning Tool’* for simplicity’s sake). We cover the actual problem stated, what demographic we are building, and the functionality provided for all stakeholders involved in its creation. The details are more properly defined in the following writing and separate use cases.

### 2. Positioning
#### *2.1 Problem Statement*
	
<table>
  <tr>
    <td>The problem of </td>
    <td>Being unable to review group peers in Learning Tools</td>
  </tr>
  <tr>
    <td>affects</td>
    <td>Students and teachers</td>
  </tr>
  <tr>
    <td>the impact of which is</td>
    <td>Reviews must be done though third party site</td>
  </tr>
  <tr>
    <td>a successful solution would be</td>
    <td>To be able to perform reviews within Learning Tools provided for by schools</td>
  </tr>
</table>


#### *2.2 Product Position Statement*

<table>
  <tr>
    <td>For</td>
    <td>Teachers and students</td>
  </tr>
  <tr>
    <td>Who</td>
    <td>Who are teaching or taking a class with a group project</td>
  </tr>
  <tr>
    <td>Our LTI</td>
    <td>Is a convenient tool</td>
  </tr>
  <tr>
    <td>That</td>
    <td>Makes the act of reviewing your group members straightforward</td>
  </tr>
  <tr>
    <td>Unlike</td>
    <td>Traditional review methods such as class handouts or fake quizzes</td>
  </tr>
  <tr>
    <td>Our product</td>
    <td>Will make you wonder why we didn’t think of it sooner</td>
  </tr>
</table>


### 3. Stakeholder and User Descriptions
#### *3.1 Stakeholder Summary*

<table>
  <tr>
    <td>Name</td>
    <td>Description</td>
    <td>Responsibilities</td>
  </tr>
  <tr>
    <td>Development Team</td>
    <td>The team developing the application</td>
    <td>To produce the software, one deliverable at a time, as a team, while maintaining pace with the project schedule and utilizing Docker, Jira, etc.</td>
  </tr>
  <tr>
    <td>Mentors</td>
    <td>Prof. Matthew Aars
Pro. Michael Aars</td>
    <td>To mentor the dev team in the production of the peer review LTI.</td>
  </tr>
</table>

#### *3.2 User Summary*

<table>
  <tr>
    <td>Name</td>
    <td>Description</td>
    <td>Responsibilities </td>
    <td>Stakeholder</td>
  </tr>
  <tr>
    <td>Students</td>
    <td>Students in a class with a need for a peer review</td>
    <td>Performs reviews of their peers</td>
    <td>The student is responsible for the information they input into the system, but the development team is responsible for providing the best experience possible to the students. </td>
  </tr>
  <tr>
    <td>Teachers</td>
    <td>Teachers hosting a class with a need for a peer review</td>
    <td>Sees all reviews made by students</td>
    <td>The teacher is responsible for adding to the base question in the review, but the development team is responsible for providing the the basic questions that will cover as many situation as is allowed for. </td>
  </tr>
</table>

#### *3.3 User Environment*

The current user environment should consist of students and teachers, always changing in size and interests. Since this is an LTI, the user is constrained to any site that supports LTI’s.

#### *3.4 Key Stakeholders or User Needs*

What are the reasons for the problem?
- There is no way to perform peer reviews within current addtitions of Learning Tools.

How is it solved now?
- Teachers email or print out their own peer review sheets, and students turn them in.
- Teachers post a fake quiz that students then take

What solutions does the stakeholder or user want?
- The development team would like to create an LTI that would enable teachers to create and manage groups of students and allow them to peer review each other.

<table>
  <tr>
    <td>Need</td>
    <td>Priority</td>
    <td>Concerns</td>
    <td>Current Solution</td>
    <td>Proposed Solutions</td>
  </tr>
  <tr>
    <td>Students need to know who is in their group</td>
    <td>Medium</td>
    <td>Student may not have prior experience with group members and has concern</td>
    <td>Ask professor in person / remember</td>
    <td>Professor creates groups in Learning Tools, students can see their group members and group member ratings</td>
  </tr>
  <tr>
    <td>Students need to peer review their group members</td>
    <td>High</td>
    <td>Students may feel pushed to rate their peers higher than they feel like they deserve due to doing them in person</td>
    <td>Professor prints out or emails a survey and students turn in</td>
    <td>Professor creates peer review survey on Learning Tool, students log into Learning Tool and complete the peer review</td>
  </tr>
  <tr>
    <td>Teacher needs to review peer reviews for a grade</td>
    <td>High</td>
    <td>Students may have illegible handwriting or just not do the review at all </td>
    <td>Professors have to directly go in person to the students that need to do the review</td>
    <td>Teacher creates and sends peer reviews over Learning Tool, students can log into Learning tool and complete peer review. </td>
  </tr>
</table>

#### *3.5 Alternatives and Competition*

Canvas, Moodle, ect. do not provide their own features competing with this functionality. We cannot speak for all sites supporting LTI extensions, but we are not competing with anything to our knowledge.


### 4. Product Overview
#### *4.1 Product Perspective*

Our Peer Review LTI is an extension to Learning Tools that enables professors to provide a mechanism for students to review their group members. This system is entirely dependant on sites which support LTI extensions.

#### *4.2 Assumptions and Dependencies*

- This product assumes that all users have access to an operating system capable of viewing web pages and an internet connection.
- This product assumes that all users are using a Learning Tools that supports LTI extensions.
- This product assumes that Learning Tool sites do currently and will continue to support LTI extensions for the foreseeable future.
- This product assumes that users have basic knowledge of the Learning Tool provided for by their school to use the LTI extension.
- This product assumes that all users are registered users of the Learning Tool provided for by their school.

#### *4.3 User Criteria Selection*

Three user criterium have been chosen:

1. Student group assignments
2. Configuration of the review (questions, etc)
3. Review start and end date


### 5. Product Features
	
- Default questionnaire
- Custom questionnaire 
- Analytics over student responses
- Email notification for "failing students"
- Assigning students to groups
- Reporting analytics to teacher
- Export or print out reviews


### 6. Other Product Requirements

This LTI will require an internet connection for initial download of page and continued interaction with the website(it is a website, after all).

The data regarding student groups and review configuration and review results will need to be stored in the same place as everything else, typically in the Learning Tool server. 
