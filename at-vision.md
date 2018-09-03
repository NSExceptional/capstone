# Attendance Vision Document
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
    <td>08/24/2018</td>
    <td>1.1</td>
    <td>Filled in most info</td>
    <td>Tanner Bennett</td>
  </tr>
  <tr>
    <td>08/26/2018</td>
    <td>1.2</td>
    <td>Added slight info</td>
    <td>Carlos Gamino</td>
  </tr>
  <tr>
    <td>8/27/2018</td>
    <td>1.3</td>
    <td>Confirmed information about risks and stakeholders</td>
    <td>Deyanira Gomez</td>
  </tr>
  <tr>
    <td>8/27/2018</td>
    <td>1.4</td>
    <td>Changed wording and fixed spelling mistakes.</td>
    <td>Justin Ritter</td>
  </tr>
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

This document provides coverage over the vision prepared for the creation of a LTI for taking attendance within Canvas, Moodle, ect. (referred to just as ‘Learning Tool’ for simplicity’s sake). We cover the actual problem stated, what demographic we are building, and the functionality provided for all stakeholders involved in its creation. The details are more properly defined in the following writing and separate use cases.


### 2. Positioning
#### *2.1 Problem Statement*

<table>
  <tr>
    <td>The problem of </td>
    <td>Being unable to take attendance in Learning Tools</td>
  </tr>
  <tr>
    <td>affects</td>
    <td>Teachers and professors</td>
  </tr>
  <tr>
    <td>the impact of which is</td>
    <td>Attendance must be taken by hand</td>
  </tr>
  <tr>
    <td>a successful solution would be</td>
    <td>To be able to take attendance in Learning Tools</td>
  </tr>
</table>

#### *2.2 Product Position Statement*

<table>
  <tr>
    <td>For</td>
    <td>Teachers and professors</td>
  </tr>
  <tr>
    <td>Who</td>
    <td>Choose to use Learning Tools to take attendance</td>
  </tr>
  <tr>
    <td>Our LTI</td>
    <td>Is a convenient and helpful asset</td>
  </tr>
  <tr>
    <td>That</td>
    <td>Makes taking attendance a breeze</td>
  </tr>
  <tr>
    <td>Unlike</td>
    <td>Traditional methods of taking attendance</td>
  </tr>
  <tr>
    <td>Our product</td>
    <td>Makes creating a seating chart and taking attendance easier than ever before</td>
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
Prof. Michael Aars</td>
    <td>To mentor the dev team in the production of the attendance LTI and acts a stand-in Customer.</td>
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
    <td>Students in a class</td>
    <td>Viewing the teacher-created seating chart

Add prefer name/pronunciation</td>
    <td>The student is responsible for the information they input into the system, but the development team is responsible for providing the best experience possible to the students. </td>
  </tr>
  <tr>
    <td>Teachers</td>
    <td>Teachers or professors</td>
    <td>May choose to make a seating chart, visible to students or not, and may choose to take attendance</td>
    <td>The teacher is responsible for the information they input into the system, but the development team is responsible for providing the best experience possible to the teacher. </td>
  </tr>
</table>


#### *3.3 User Environment*

The current user environment should consist of students and teachers, always changing in size and interests. Since this is an LTI, the user is constrained to any site that supports LTI’s.

#### *3.4 Key Stakeholders or User Needs*

What are the reasons for the problem?
- There is no way to take attendance in Learning Tools
- There is no way for any user to view a seating chart in Learning Tools

How is it solved now?
- Teachers must make seating charts and take attendance by hand
- Students must ask their classmates for names and email addresses

What solutions does the stakeholder or user want?
- The development team would like to create an LTI that would enable teachers to create seating charts and take attendance.
- Students may also be able to view the seating chart to learn about classmates.

<table>
  <tr>
    <td>Need</td>
    <td>Priority</td>
    <td>Concerns</td>
    <td>Current Solution</td>
    <td>Proposed Solutions</td>
  </tr>
  <tr>
    <td>Seating charts</td>
    <td>High</td>
    <td>Gaining privileges to the students in the class</td>
    <td>Teacher makes seating chart by hand, or not</td>
    <td>Teacher makes seating chart in Learning Tools, chooses to allow students to view it</td>
  </tr>
  <tr>
    <td>Teachers can take attendance</td>
    <td>High</td>
    <td>Teachers making mistakes about attendance</td>
    <td>Teacher takes attendance on paper</td>
    <td>Teacher takes attendance in Learning Tools with assistance of the seating chart</td>
  </tr>
  <tr>
    <td>Students can track their own attendance</td>
    <td>High</td>
    <td>Students changing their attendance to their own benefit</td>
    <td>Students must ask teacher or keep track on their own</td>
    <td>Students can log into Learning Tools and see their attendance</td>
  </tr>
</table>

#### *3.5 Alternatives and Competition*

Learning Tools do not provide their own feature competing with this functionality. We cannot speak for all sites supporting LTI extensions, but we are not competing with anything to our knowledge.


### 4. Product Overview
#### *4.1 Product Perspective*

Our Attendance LTI is an extension to Learning Tools that will enable professors to take attendance, and provides a mechanism for students to track their own attendance and potentially see who sits where in their class. This system is entirely dependant on sites which support for LTIs extensions.

#### *4.2 Assumptions and Dependencies*

- Assumes teacher even takes attendance or wants to students to see seating chart
- This product assumes that all users have access to an operating system capable of viewing web pages and an internet connection.
- This product assumes that all users are using Learning Tools which supports LTI extensions.
- This product assumes that there will be continued support for LTIs in classrooms
- This product assumes that users have basic knowledge of the Learning Tool that is provided for by their school.
- This product assumes that all users are registered users of the Learning Tool provided for by their school.

#### *4.3 User Criteria Selection*

Five user criterium have been chosen:

1. Enable attendance
2. Enable students to track attendance
3. Enable seating chart
4. Configuration of seating chart
5. Enable students to see seating chart


### 5. Product Features

- Calendar and number of dates that students have missed class
- Turning Point support for classes where teacher prefers the use of clickers.
- Take attendance, or choose not to take it at all
    - Enable or prevent students from viewing their attendance
    - Make attendance a grade
    - View student or class attendance history
    - Mark students as here, tardy, or absent
- Make a seating chart, or not
    - Default grid layout when complex seating chart is not necessary
    - Enable or prevent students from seeing the chart
        - Or allow students to see where they sit but anonymize other seats
    - Print seating chart’
    - Change seating chart at a later date


### 6. Other Product Requirements

This LTI will require an internet connection for initial download of page and continued interaction with the website(it is a website, after all).

The data regarding student groups and review configuration and review results will need to be stored in the same place as everything else, typically in the Learning Tool server. 

