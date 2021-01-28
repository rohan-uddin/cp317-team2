

<h1>  Software Project Management Plan (SPMP)  </h1>

<h2> Revision history </h2>

| Date      | Member        | Description                                          |
|-----------|---------------|------------------------------------------------------|
| 1/20/2021 | Janelle Tait  | Created SPMP layout                                  |
| 1/23/2021 | Janelle Tait  | Finished Section 1 and 5                             |
| 1/27/2021 | Ann Baldonasa | Added to Section 1 and completed sections 2, 3, 4 |

<h2> Table of Contents </h2>

- [1. Overview](#1-overview)
  - [1.1. Project Summary](#11-project-summary)
    - [1.1.1. Purpose, Scope, and Objectives](#111-purpose-scope-and-objectives)
    - [1.1.2. Intended audience](#112-intended-audience)
    - [1.1.3. Constraints](#113-constraints)
    - [1.1.4. Assumptions](#114-assumptions)
    - [1.1.5. Dependencies](#115-dependencies)
    - [1.1.6. Project Deliverables](#116-project-deliverables)
    - [1.1.7. Evolution of the Plan](#117-evolution-of-the-plan)
- [2. Reference materials](#2-reference-materials)
- [3. Definitions](#3-definitions)
- [4. Project Organizations](#4-project-organizations)
  - [4.1. External interfaces](#41-external-interfaces)
  - [4.2. Internal structure](#42-internal-structure)
  - [4.3. Organizational structure](#43-organizational-structure)
- [5. Managerial process plans](#5-managerial-process-plans)
  - [5.1. Management Objectives and Priorities](#51-management-objectives-and-priorities)
  - [5.2. Work plan](#52-work-plan)
    - [5.2.1. Work activities and schedule allocation](#521-work-activities-and-schedule-allocation)
  - [5.3. Control plan](#53-control-plan)
    - [5.3.1. Schedule control plan](#531-schedule-control-plan)
    - [5.3.2. Quality control plan](#532-quality-control-plan)
  - [5.4. Risk management plan](#54-risk-management-plan)
    - [5.4.1. Risk map](#541-risk-map)
    - [5.4.2. Risk details](#542-risk-details)
- [6. Supporting process plans](#6-supporting-process-plans)
  - [6.1. Configuration management plan](#61-configuration-management-plan)
  - [6.2. Verification and validation plan](#62-verification-and-validation-plan)
  - [6.3. Documentation plan](#63-documentation-plan)
  - [6.4. Quality assurance plan](#64-quality-assurance-plan)
  - [6.5. Problem resolution plan](#65-problem-resolution-plan)
- [7. Index](#7-index)
- [8. Versions](#8-versions)
  
<h2> List of figures </h2> 
<h2> List of tables </h2>

---

## 1. Overview
*StudySpace is a web application that provides university students with access to virtual study spaces and several other useful tools to help them succeed in school.*
### 1.1. Project Summary

#### 1.1.1. Purpose, Scope, and Objectives
The purpose of the App is to give university students a sense of unity by providing them with several tools to meet new people, connect, and study together. This document intends to provide the developers of App easy access of the project deliverables, scope, purpose, plans, processes, and the TEAM organizational structure.  

#### 1.1.2. Intended audience 
The TEAM considers Mr. David Brown as the primary audience for the App. 
The TEAM considers university students as the secondary audience for the App. 

#### 1.1.3. Constraints
The TEAM is subjected to the following constraints. 
* Schedule. 
  The deadlines were imposed by its primary audience.  
  There are set deadlines for each workflow, and the entire project must be done in less than four months.
* Budget and resources. 
  The developers of this App are limited by course resources to free software.
* Inexperience. 
  Members of the TEAM may have limited experience and knowledge of the methodologies, tools, techniques, and languages to be used in the completion of the App. 

#### 1.1.4. Assumptions 

The TEAM have the following assumptions with respect to the completion of the App.
* Workflow.
  Each workflow has 2 groups.
    * Those who write/code (the authors).
    * Those who make suggestions for revisions and look for defects (the SQA team).
    * The authors and SQA group members will vary between workflows, but each group member will, in some way, contribute to MOST workflows.
* Documentation.
  Each document (SRS, Design, Analysis) will be completed in three phases. 
  * Phase 1: initial draft of the document and code.
  * Phase 2: quality assurance will be completed by members of the TEAM who did not participate in Phase 1.
  * Phase 2: suggestions will be taken into consideration by the original authors of the initial draft and the appropriate revisions will be made. 
  * Everyone should have participated in the marking of revisions and initial drafts in at least one of the documents. 
* Availability.
  1. All group members are assumed to be available to help out with most workflows.
  2. It is assumed that all group members can be reached via discord on a regular basis.
  3. It is assumed that all group members have/can obtain the necessary software and equipment needed to complete their assigned tasks.
* Skills.
  It is assumed that not all group members have the same set of skills or abilities. However, it is assumed that regardless of level of expertise, all members are ready and willing to learn and continuously try their best to help out and contribute however they can.

#### 1.1.5. Dependencies 

The dependencies are:
1. In order to begin the next workflow, at minimum, the first version of the previous workflow must be completed and of high quality and detail.
2. In order for the SQA team to perform quality assurance, the first draft/version of the document or code in question must already be complete.
3. Before submitting a finalized version of a document or code, all concerns, suggestions, and defects pointed out by the SQA team must be addressed.
4. If any changes are made to the project plan or certain specifications are not implemented, the appropriate updates must be made to past documentation to ensure they align with the outcome of the project.

#### 1.1.6. Project Deliverables
|                    Phase                   |       Date        |
|:------------------------------------------:|:-----------------:|
|                    SPMP                    |  February 5, 2021 |
| Software requirements specifications (SRS) | February 12, 2021 |
|                  Analysis                  |   March 5, 2021   |
|                   Design                   |   March 26, 2021  |
|               Implementation               |   April 21, 2021  |
#### 1.1.7. Evolution of the Plan
|                Goal                |     Deadline     |
|:----------------------------------:|:----------------:|
|            Initial draft           | January 29, 2021 |
|         Initial draft (SQA)        | January 31, 2021 |
|            Final draft             | February 2, 2021 |
| Additional edits [1] |   April 5, 2021  |

*Notes:*
* This SPMP may be viewed in HTML or PDF format. 
* Subsequence changes to the SPMP are controlled and monitored via git/Github as the version control tracking system. 
* [1] It is expected that updates may be made to the SPMP when various features, goals, or any other system changes occur. 


---

## 2. Reference materials

- IEEE Standard For Software Project Management Plans - IEEE Std 1058-1998
- [Project Risk Management Template](http://www.readysetpro.com/eval/risks.html)
- [Course Webpage](https://bohr.wlu.ca/cp317/)

--- 

## 3. Definitions

1. **DESK**
    A Desk is a virtual space wherein students may collaborate privately or publically. 
    Each desk is temporary it only exists so long as there are people are using it. After everyone leaves the desk, it is purged from memory. 
    Each desk has an admin who can set a limit to the number of members and add signifiers such as language, age category,  and other factors. 
    Users can sort desks based on their preferences (see: Private Desk), or join a random one (see: Public Desk).
2. **TEAM**
    Team refers to students in CP317 W21 Team 2. 
3. **STUDY SPACE**
   Study Space refers to the web application created by the Team for the Initial Audience, Mr. David Brown.
4. **USER MATCH**
    Users have the option to enter information about themselves, such as various preferences, courses they’re enrolled in, and their study habits. 
    Users who are both members of the same group have the possibility of getting matched. The more preferences, common classes, and similar study habits two group members have, the more likely they are to be matched. When a User Match occurs, the matched users show up in each other’s list of user matches, found on the page of the group they were matched from.
5. **STUDY GROUP**
    A group of Students. 
6. **STUDENT**
    A Student is a user enrolled in any Canadian university, who seeks the use of a Desk. 
7.  **INITIAL AUDIENCE**
    This product was made for the use of Mr. David Brown, who is the initial User that is not part of the Team to use and test this application. 
8.  **TARGET AUDIENCE**
    This product was created to solve areas most commonly experienced by Students. 
9.  **CHAT** 
    A Chat is a feature where all members of a Group can send text messages to each other. The Chat is viewed through a chat box on the Group’s page.
10. **VOICE CHAT**
    A Voice Chat is a feature where all members of a Group call each other. The Voice Chat is viewed through a chat box on the Group’s page.
11. **TUTOR**
    A Tutor can be a student, professor, or a 3rd party that offers teaching services to any student(s).
12. **PUBLIC DESK**
    A Desk that any Student can enter and collaborate in.
13. **PRIVATE DESK**
    A Desk designated for a particular Study Group. 
    Students that are not part of that Study Group may not enter a Private Desk. 
14. **FRIEND**
    Any two Users can become Friends if one sends a Friend Request and the other accepts it. When two Users are Friends, they are able to send private chats directly to one another.
15. **GROUP NAME**
    A Group Name is the name of a Group. The Group Name is set by a member of the Group. The Group Name must be unique so that other Users can easily discover the Group via Search.
16. **GROUP**
    A Group is a collection of two or more users who have connected through StudySpace either by Invitation or a User Match. All members of a Group automatically have access to a Chat upon joining.
17. **INVITATION**
    An Invitation is the opportunity for a User to join a Private Group. Any member of a Private Group can choose to send an Invitation to a User who isn’t already a member.
18. **PAGE**
    A Page is where Posts are viewed. Each Group can have one or more Pages.
19. **POST**
    A Post is an object which can include photos and text. Posts are created by Users for all members of a Group to see. Users can make a Post about anything they wish, including: buying/selling textbooks, searching for a tutor, asking questions, looking for advice, etc. Users can write a Response to a Post.
20. **PRIVATE GROUP**
    A Private Group is a Group that is only accessible to Users who have either been Invited to the group by an existing member or User Matched to the group. Posts and Chats, and Pages within a Private Group are not visible to any User who is not a member of the Group.
21. **PUBLIC GROUP**
    A Public Group is a Group that is accessible to all Users and does not require an Invitation or User Match to join. All Posts and Chats, and Pages within a Public Group are visible to all Users.
22. **PROFILE**
    A page with personal information about the user. The Profile also provides functionality such as managing group memberships and accessing chats.
23. **RESPONSE**
    A Response is a text message which is linked to a Post. 
24. **SEARCH**
    Search is a function of the app where Users can search and discover Groups by Group Name or Users by Username.
25. **USER**
    A User is someone who uses the application; likely a Student.
26. **USERNAME**
    A Username is part of a User’s account information. A Username is the name by which a User is referred to on the app.

--- 

## 4. Project Organizations 
### 4.1. External interfaces

The acquiring organization of the project and the documentation(s) accompanying the project is Wilfrid Laurier University as this project was produced to fulfil CP317 course requirements. 

Entities that interact with the product  will include students from the Team but may include various students from other universities.

### 4.2. Internal structure

With respect to implementation, there are two groups in charge of two different parts of the web application: the back-end team and the front-end team. 

The back-end team: 
* Ann Baldonasa
* Kevin Lin
* Dayton Talarico
* Mackenzie Van Zanden
* Shyam Dave
  
The front-end team: 
* Zeeshan Jafri
* Arvin Benipal
* Muhammad Hashir
  
??? 
* Brian Carvalho
* Janelle Tait
* Jordan Bergen
* Rohan Uddin
* Arshdeep Sahi

### 4.3. Organizational structure
|        Deliverable        |                                  Initial Authors                                  |       Review (SQA)       |
|:-------------------------:|:---------------------------------------------------------------------------------:|:------------------------:|
|       Specifications      | Arvin, Brian, David, Mackenzie, Matthew, Muhammad Hashir, Shyam, Zeeshan, Janelle |    Rohan, Dayton, Ann    |
|            SPMP           |                           Arshdeep, Ann, Janelle, Jordan                          |  Shyam, Matthew, Dayton  |
|        Requirements       |                                     Mackenzie                                     | Arshdeep, Shyam, Matthew |
|          Analysis         |                                                                                   |  Ann, Janelle, Arshdeep  |
|           Design          |                                                                                   |      Rohan, Janelle      |
| Implementation: front end |                                  Matthew, Zeeshan                                 |    Janelle, Shyam, Ann   |
|  Implementation: back end |                   Janelle, Mackenzie, Kevin, Shyam, Ann, Dayton                   |                          |

--- 
## 5. Managerial process plans

### 5.1. Management Objectives and Priorities
The objective of this project is to produce a web application that provides university students with several tools, including virtual study groups. The main objective is to complete all workflows of the project by their respective deadlines, as determined by the professor. The main priorities are quality of work and time efficiency. Budget is not a priority because there is no intention for any amount of money to be spent on this project.



### 5.2. Work plan
#### 5.2.1. Work activities and schedule allocation

<!-- copied form https://www.tablesgenerator.com/markdown_tables# -->
|      Phase     | Starting | Deadline for first draft to be submitted to SQA | Deadline for SQA to finish Assessment | Deadline for final revision | Convert documentation to HTML by | Deadline to submit final product  |
|:--------------:|:--------:|:-----------------------------------------------:|:-------------------------------------:|:---------------------------:|:--------------------------------:|:---------------------------------:|
| Specifications |  Jan. 18 |                     Jan. 23                     |                Jan. 25                |           Jan. 28           |              Jan. 29             |              Jan. 29              |
|      SPMP      |  Jan. 26 |                     Jan. 29                     |                 Feb. 1                |            Feb. 4           |              Feb. 5              |               Feb. 5              |
|  Requirements  |  Feb. 2  |                      Feb. 6                     |                 Feb. 8                |           Feb. 11           |              Feb. 12             |              Feb. 12              |
|    Analysis    |  Feb. 12 |                     Feb. 27                     |                 Mar. 1                |            Mar. 4           |              Mar. 5              |               Mar. 5              |
|     Design     |  Mar. 5  |                     Mar. 10                     |                Mar. 14                |           Mar. 25           |              Mar. 26             |              Mar. 26              |
| Implementation |  Mar. 15 |                     Mar. 28                     |                 Apr. 4                |            Apr.11           |              Apr.12              |              Apr. 12              |

Each work activity has been scheduled in such a way that maximizes opportunities for different tasks to be done concurrently. Because each successive phase depends on having an established, agreed upon plan provided by the previous phases, it must be ensured that the next phase is never started before the deadline for SQA of the previous phase.

### 5.3. Control plan
#### 5.3.1. Schedule control plan
Mechanisms used to measure progress and compare actual progress against planned progress include:
1. Weekly group meetings on discord that are held every Saturday. These weekly meetings are intended to allow for regular check-ins and to ensure that all task forces are working on schedule.
2. Teams assigned to write and perform SQA on individual project phases are appointed a “communicator” member, who is responsible for communicating to all outside members if their team is having an issue with timing or scheduling.
   
When actual progress does meet planned progress, corrective actions include:
1. Making adjustments to scheduling the better suit the needs of the group members who require more time.
2. Assign additional group members to the task that is demanding more time. 

#### 5.3.2. Quality control plan
Mechanisms used to control quality of work include:
1. An SQA team assigned to each individual phase of the project to ensure all work done by the authors is correct, detailed, and conforms to the plans established in the previous phases. If there has been an update to the project scope or plan, it is the responsibility of the SQA team to ensure that the representatives of previous phases are notified in the event that their phase requires modifications due to this update.
2. Each project phase has a representative who is responsible for updating the documentation of their phase whenever changes are made in successive phases that do not conform to the plans as laid out in their own documentation.
3. All contributors to a phase -whether an author or SQA team member- must review the documentation from all previous phases prior to starting to work on their own phase. This is to ensure that all members are aware of plans, goals, and vision for their phase, which have been made by the past phases of the project.

### 5.4. Risk management plan
#### 5.4.1. Risk map

| Likelihood/Impact | Catastrophic | Critical | Significant  | Marginal |
|-------------------|--------------|----------|--------------|----------|
| Very Likely       | none         | R1       | R2           | none     |
| Likely            | none         | none     | R3           | none     |
| Unlikely          | none         | none     | none         | none     |
| Very Unlikely     | none         | none     | none         | none     |

#### 5.4.2. Risk details
**R1: Could run out of time since we have a very tight schedule.**
*Mitigation strategy.*
  1. Start with a schedule that all group members can agree is reasonable.
  2. Aim to get each phase done at least a day before its due date so there is a time buffer if needed. 
  3. For the implementation phase especially, plan for things to go wrong; allocate extra time.

**R2: There will be many technical difficulties throughout the implementation phase because most group members are inexperienced in working on projects of this size.**
*Mitigation strategy.*
1. Schedule enough time for more knowledgeable group members to guide others at first; anticipate a slow start as everyone learns.
2. Assign many group members to the SQA team and start SQA early on so that most bugs are identified while enough time is remaining for the programmers to actually fix them.
3. Make sure no programmer is given a workload that is too much for them to handle.
  
**R3: We might be underestimating the time, effort, and skills required to implement our project.**
*Mitigation strategy.*
1. Compare our project with what has been accomplished in sample projects from previous years. If ours is a lot more complicated, consider which features are unnecessary and what can be removed.
2. Remember that the planning documents are all living documents -if, after writing them, we decide we won’t implement something we said we would, we can retroactively update previous documents. It is the job of the representatives of previous project phases to ensure the older documents are up to date with the current plan.


---

## 6. Supporting process plans
### 6.1. Configuration management plan
### 6.2. Verification and validation plan
### 6.3. Documentation plan
### 6.4. Quality assurance plan
### 6.5. Problem resolution plan

--- 

## 7. Index


--- 

## 8. Versions

<h3> Version 1.0 </h3>
<h4> Authors </h4>

-  Ann Baldonasa
-  Arshdeep Sahi
-  Janelle Tait
-  Jordan Bergen

<h4> Software Quality Assurance </h4>
  
- Dayton Talarico
- Matthew Francis
- Shyam Dave

 

