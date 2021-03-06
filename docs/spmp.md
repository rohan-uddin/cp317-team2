

- [Team Members](#team-members)
- [Revision History](#revision-history)
- [Preface](#preface)
- [List of Figures/Tables](#list-of-figurestables)
- [1. Overview](#1-overview)
  - [1.1. Project Summary](#11-project-summary)
    - [1.1.1. Purpose, Scope, and Objectives](#111-purpose-scope-and-objectives)
    - [1.1.2. Intended Audience](#112-intended-audience)
    - [1.1.3. Constraints](#113-constraints)
    - [1.1.4. Assumptions](#114-assumptions)
    - [1.1.5. Dependencies](#115-dependencies)
    - [1.1.6. Project Deliverables](#116-project-deliverables)
  - [1.2. Evolution of the Software Project Management Plan](#12-evolution-of-the-software-project-management-plan)
- [2. Reference Materials](#2-reference-materials)
- [3. Definitions](#3-definitions)
- [4. Project Organizations](#4-project-organizations)
  - [4.1. External Interfaces](#41-external-interfaces)
  - [4.2. Internal Structure](#42-internal-structure)
    - [4.2.1. Internal Structure for the Specifications and SPMP Phases](#421-internal-structure-for-the-specifications-and-spmp-phases)
      - [4.2.1.1. Internal Structure for the Specifications and SPMP Phases Table](#4211-internal-structure-for-the-specifications-and-spmp-phases-table)
    - [4.2.2. Internal Structure for Future Phases (Requirements, Analysis, Design)](#422-internal-structure-for-future-phases-requirements-analysis-design)
    - [4.2.3. Group Organization](#423-group-organization)
      - [4.2.3.1. Group Organization Diagram](#4231-group-organization-diagram)
  - [4.3. Project Responsibilities](#43-project-responsibilities)
- [5. Managerial Process Plans](#5-managerial-process-plans)
  - [5.1. Management Objectives and Priorities](#51-management-objectives-and-priorities)
  - [5.2. Work Plan](#52-work-plan)
    - [5.2.1. Work Activities and Schedule Allocation](#521-work-activities-and-schedule-allocation)
      - [5.2.1.1. Work Activities and Schedule Allocation Table](#5211-work-activities-and-schedule-allocation-table)
  - [5.3. Control Plan](#53-control-plan)
    - [5.3.1. Schedule Control Plan](#531-schedule-control-plan)
    - [5.3.2. Quality Control Plan](#532-quality-control-plan)
  - [5.4. Risk Management Plan](#54-risk-management-plan)
    - [5.4.1. Risk Map](#541-risk-map)
    - [5.4.2. Risk Details](#542-risk-details)
- [6. Technical Process Plans](#6-technical-process-plans)
  - [6.1. Process Model](#61-process-model)
  - [6.2. Methods, Tools, and Techniques](#62-methods-tools-and-techniques)
- [7. Supporting Process Plans](#7-supporting-process-plans)
  - [7.1. Verification and Validation Plan](#71-verification-and-validation-plan)
    - [7.1.1. Verification Plan](#711-verification-plan)
    - [7.1.2. Validation Plan](#712-validation-plan)
  - [7.2. Documentation Plan](#72-documentation-plan)
  - [7.3. Quality Assurance Plan](#73-quality-assurance-plan)
  - [7.4. Problem Resolution Plan](#74-problem-resolution-plan)
- [8. Appendix](#8-appendix)
  - [8.1. Appendix 1: Changes Made to Past Documents](#81-appendix-1-changes-made-to-past-documents)

<!-- exlude toc -->
# Team Members 

- Zeeshan Jafri
- Shyam Dave
- Muhammad Rohan Uddin
- Muhammad Hashir
- Ann Baldonasa
- Matthew Francis
- Mackenzie Van Zanden
- Kevin Lin
- Jordan Bergen
- Janelle Tait
- Dayton Talarico
- David Rosien
- Brian Carvalho
- Arvin Benipal
- Arshdeep Sahi

# Revision History 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 13px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 13px;word-break:normal;}
.tg .tg-rk1c{background-color:#EFEFEF;color:#333;text-align:left;vertical-align:top}
.tg .tg-x015{background-color:#CCC;color:#333;font-weight:bold;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-x015"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Date</span></th>
    <th class="tg-x015"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Version</span></th>
    <th class="tg-x015"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Member</span></th>
    <th class="tg-x015"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Description</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1/20/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Janelle Tait</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Created SPMP layout</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1/23/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Janelle Tait</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Finished Section 1 and 5</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1/27/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann Baldonasa</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Added to Section 1 and completed sections 1, 2, 3, 4</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/1/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arshdeep Sahi</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Intro and Section 6</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/1/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Dayton Talarico</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Section 7</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/2/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann Baldonasa</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Revised Section 4</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/2/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Shyam Dave</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SQA for the Version 1 Doc</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/2/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Matthew Francis</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SQA for the Version 1 Doc</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/3/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Evan Surtel</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SQA for the Version 1 Doc</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/3/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arshdeep Sahi</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Revised Introduction, List of figures, and Section 6</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/3/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Janelle Tait</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Revised section 5 based on sqa suggestions</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/3/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Dayton Talarico</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Revised section 7 based on sqa suggestions</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/3/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann Baldonasa</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Revised section 1 based on SQA suggestions</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2/5/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">1.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann Baldonasa</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Revised sections 1, 2, 3, 4 based on SQA suggestions</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">3/30/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann Baldonasa</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Revised section 4 (Group organization, Project Responsibilities, &amp; Internal structure)</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">4/07/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Dayton Talarico</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Adjusted section 5.2.1 (Work activities and schedule allocation) to match actual deadlines</span></td>
  </tr>
  <tr>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">4/07/2021</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">2.0</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Janelle Tait</span></td>
    <td class="tg-rk1c"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Adjusted section 5.2.1 (Work activities and schedule allocation) to match actual deadlines</span></td>
  </tr>
</tbody>
</table>

# Preface 

The purpose of this document is to serve as a guide for development of the project and to ensure that all requirements are met and the product functions according to the requirements outlined in the specifications document. 

The SPMP will detail the **major activities, resources, schedules, and milestones** for developing *Study Space*. This will be accomplished with comprehensive descriptions and supplemental information for each aspect of the development process, being as thorough as possible.

# List of Figures/Tables 

<h2> Section 1 </h2>

- [1.1.6. Project Deliverables](#116-project-deliverables)
- [1.2. Evolution of the Software Project Management Plan](#12-evolution-of-the-software-project-management-plan)

<h2>Section 3</h2>

- [3.0 Definitions](#3-definitions)

<h2>Section 4</h2>

- [4.2.1.1 Internal Structure for Specifications and SPMP Phases Table](#4211-internal-structure-for-the-specifications-and-spmp-phases-table)
- [4.2.3.1 Group Organization Diagram](#4231-group-organization-diagram)
- [4.3. Project Responsibilities](#43-project-responsibilities)

<h2>Section 5</h2>

- [5.2.1.1 Work Activities and Schedule Allocation Table](#5211-work-activities-and-schedule-allocation-table)
- [5.4.1 Risk Map](#541-risk-map)

<h2> Section 8 </h2>

- [8.1. Appendix 1: Changes Made to Past Documents](#81-appendix-1-changes-made-to-past-documents)

# 1. Overview
_StudySpace is a web application that provides university students with access to virtual study spaces and several other useful tools to help them succeed in school._

## 1.1. Project Summary

### 1.1.1. Purpose, Scope, and Objectives

The StudySpace app is a multi-purpose web application that provides students with the following functions:
- Provide tools for similarly-minded students to connect and study together, thereby achieving a sense of unity.
- Create a space wherein students may buy or sell textbooks via an integrated 3rd party service.
- Create a space wherein students may chat on academic or non-academic topics, in private or public chat rooms. 
- Provide access to knowledgeable tutors.

The purpose of this document is to provide the developers of the StudySpace app easy access to the project's deliverables, scope, purpose, plans, processes, and the team's organizational structure.
- The objectives of the project are as described:
- Deploy a web application that provides the functions described above and those further expanded upon in the SRS document.
- Complete the project deliverables (documentation, implementation, testing) by the deadlines specified in StudySpace app's [Project Deliverables](#116-project-deliverables).
- Host all documentation onto the StudySpace app's documentation website.
- Fulfil all requirements stated in the Software Requirements Specifications Document.

Activities that fulfil the requirements are within the scope of this project.
  
### 1.1.2. Intended Audience

The team considers Mr. David Brown as the project client for the StudySpace app.

The team considers university students (as defined in the StudySpace Software Requirements Specifications document) as the target audience for the StudySpace app.

Possible indirect audiences may include:
- Universities that implement the StudySpace app as a supplementary learning tool.
- Students employed by StudySpace to become tutors to other students.
- University professors who may wish to participate in student discussions.
  
### 1.1.3. Constraints
The team is subjected to the following constraints.
- Schedule.
  - The deadlines are imposed by its primary audience.
  - There are set deadlines for each workflow, and the entire project must be done in less than four months.
- Budget and resources.
  - The developers of the StudySpace app are limited by course resources to free software.
- Inexperience.
  - Members of the team may have limited experience and knowledge of the methodologies, tools, techniques, and languages to be used in the completion of the StudySpace app.

### 1.1.4. Assumptions
The team has the following assumptions with respect to the completion of the StudySpace app.
- Documentation.

  Each documentation phase (SRS, SPMP, Requirements, Design, Analysis) will occur as described.
  - Part 1:
    - Management must establish deadlines, break down the product deliverable into tasks, and will publish the tasks onto Github's project tracking sheet.
  - Part 2:
    - Management must communicate with authors regarding the document expectations, deadlines, and any further relevant information such as template, formatting.
    - Authors must communicate with management regarding any potential difficulties or problems that could surface when making the Initial Draft.
  - Part 3:
    - Authors will create the initial draft.
  - Part 4:
    - Authors will hand the initial draft to the software quality assurance team (SQA) for potential revisions and suggestions to be implemented. 
  - Part 5:
    - SQA will conduct quality testing. For further information on the SQA team’s tasks during the documentation process, refer to section 4.2 for the team’s internal structure. 
  - Part 6:
    - Authors will make the appropriate changes to the document.
  - Part 7:
    - Management will inspect any potential room for revisions and final product.
    - Management will hand off the product to the Version Control team who will convert the document into HTML and host onto the website.
- Availability.
  - All group members are assumed to be available on class lecture times (Mondays and Wednesdays, 4:30 to 5:30 pm) for potential impromptu meetings and on Saturdays, 4 to 5 pm, for weekly meetings.
  - All group members are assumed to be available to help out with most workflows.
  - It is assumed that all group members can be reached via Discord on a regular basis.
  - It is assumed that all group members can obtain the necessary software and equipment needed to complete their assigned tasks.
- Skills.
  - It is assumed that not all group members have the same set of skills or abilities. However, it is assumed that regardless of level of expertise, all members are ready to learn and will contribute to the best of their ability.
### 1.1.5. Dependencies
The dependencies are:
  1. In order to begin the next workflow, at minimum, the first version of the previous workflow must be completed with high quality and detail.
  2. In order for the SQA team to perform quality assurance, the first draft/version of the document or code in question must already be complete.
  3. Before submitting a finalized version of a document or code, all concerns, suggestions, and mistakes pointed out by the SQA, Version Control, and Management must be addressed.
  4. If any changes are made to the project plan or certain specifications are not implemented, the appropriate updates must be made to existing documentation to ensure they align with the outcome of the project.
### 1.1.6. Project Deliverables 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-xqm4{background-color:#D9D9D9;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-ktyi{background-color:#FFF;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deliverables</span></th>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Date</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SPMP</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">February 5, 2021</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Software requirements specifications (SRS)</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">February 12, 2021</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Analysis</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">March 5, 2021</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Design</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">March 26, 2021</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Implementation</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">April 12, 2021</span></td>
  </tr>
</tbody>
</table>

## 1.2. Evolution of the Software Project Management Plan 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-sd4m{background-color:#CCC;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-ktyi{background-color:#FFF;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Goal</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deadline</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Initial draft</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">January 29, 2021</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Initial draft (SQA)</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">January 31, 2021</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Final draft</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">February 2, 2021</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Additional edits [1]</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">April 12, 2021</span></td>
  </tr>
</tbody>
</table>
 
**Notes:**
- This SPMP may be viewed in HTML or PDF format.
- Subsequence changes to the SPMP are controlled and monitored via git and Github as the primary version control tracking system used to develop the StudySpace app.
- [1] It is expected that updates may be made to the SPMP when various features, goals, or any other system changes occur.

# 2. Reference Materials
- _[StudySpace Documentation Website](https://study-space-docs.vercel.app/)_
- _IEEE Standard For Software Project Management Plans - IEEE Std 1058-1998_
- _[Project Risk Management Template](http://www.readysetpro.com/eval/risks.html)_
- _[Course Webpage](https://bohr.wlu.ca/cp317/)_
- _[StudySpace Software Requirements Specifications, CP317 Team 2, W21](https://study-space-docs.vercel.app/docs/specifications.html#)_
- _[Types of Software Testing](https://www.guru99.com/types-of-software-testing.html)_
- _[Difference between testing and quality assurance](http://www.differencebetween.net/business/planning-activities/difference-between-testing-and-quality-assurance/)_
- _Examples of properly documented API: [Twitter API for Searching a Tweet](https://developer.twitter.com/en/docs/twitter-api/v1/tweets/search/api-reference/get-search-tweets), [Github Overview](https://docs.github.com/en/rest/guides/getting-started-with-the-rest-api), [Github REST API](https://docs.github.com/en/rest)_
- _[API Testing](https://www.guru99.com/api-testing.html)_
- _[Database Testing - Types](https://www.tutorialspoint.com/database_testing/database_testing_types.htm)_


# 3. Definitions
 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-citn{background-color:#FFF;color:#333;text-align:left;vertical-align:top}
.tg .tg-dgl5{background-color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">API</span></th>
    <th class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Application Programming Interface.</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">APP</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">App refers to the product created by the team, the StudySpace app.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">CONSISTENT DESIGN</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Consistent design covers: color scheme, font sizes, font choices, and any other potential visual components.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">PROJECT CLIENT</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">This product was made for the use of Mr. David Brown, who is the initial User that is not part of the team to use and test this application.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SECONDARY AUDIENCE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Secondary audiences consist of StudySpace app Users that are not 1) the project client and 2) the target audience. Examples of those who may be part of the Secondary Audience include: tutors, university professors, and the university board of directors.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SRS</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A document that states the project's Software Requirements Specifications.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">STUDENT</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A student is a user enrolled in any Canadian university.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">STUDY SPACE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">StudySpace refers to the web application created by the team for the project client, Mr. David Brown.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">TARGET AUDIENCE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">This product was created to solve areas most commonly experienced by university students.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">TEAM</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Team refers to students in CP317's Team 2 for the Winter semester in 2021.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">TUTOR</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A tutor can be a student, professor, or a 3rd party that offers teaching services to any student(s).</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">UI</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">User interface. The StudySense app UI consists of various views such as the Profile View, the Search Bar View, the Create New Post View, the Live Discussion View, the Chat Box View, the Group Chat View.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">USER</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A user is someone who uses the application; likely a student. There are many possible Users. For example, there may be university professors wishing to participate in live student discussions by creating an account and are therefore Users of the app.</span></td>
  </tr>
</tbody>
</table>

_For further definitions, see: StudySpace Software Requirements Specifications document Section 1.3._

# 4. Project Organizations
## 4.1. External Interfaces
The acquiring organization of the project and the documentation(s) accompanying the project is Wilfrid Laurier University.

This project was produced to fulfil CP317 course requirements.

Entities that interact with the product will include students from the team but may include various students from other universities and indirect audiences. 
## 4.2. Internal Structure

### 4.2.1. Internal Structure for the Specifications and SPMP Phases
The team did not follow the structure (shown in the table documented below) for the first two phases (Software Requirements Specifications and Software Project Management Plan), so the group structure differs in terms of level of responsibility and the presence of a Management and Version Control teams further discussed in the Section 4.2.2.

#### 4.2.1.1. Internal Structure for the Specifications and SPMP Phases Table
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-xqm4{background-color:#D9D9D9;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-ktyi{background-color:#FFF;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deliverable</span></th>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Initial Authors</span></th>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Review (SQA)</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Specifications</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arvin, Brian, David, Mackenzie, Matthew, Muhammad Hashir, Shyam, Zeeshan, Janelle</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Rohan, Dayton, Ann</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SPMP</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arshdeep, Ann, Janelle, Jordan</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Shyam, Matthew, Evan, Zeeshan, David</span></td>
  </tr>
</tbody>
</table>

### 4.2.2. Internal Structure for Future Phases (Requirements, Analysis, Design)
In future phases, the team structure will differ to provide further organization and structure.

**Documentation**
  1. Authors
     - Formulates the initial draft of the document.
     - Ensures the document follows the project client's expectations in terms of template layout, formatting, and content.
     - Submits initial drafts early so that the SQA team may work on the draft with sufficient time for revisions and quality control.
1. Management
   - Establishes, manages, and updates team deadlines.
   - Heads meetings by creating the agenda, following up on issues, delegating tasks to specific teams.
   - Communicates to various team representatives to ensure that overall progress on the deliverable is made.
   - Manages project progress via git and Github.
   - Approves or suggests final revisions for the document.
   - May act as a potential back-up for other teams to complete tasks if a member has not completed their tasks.
   - Provides any final suggestions, corrections, and additions for all deliverables.
   - Provides frequent communication with other teams to ensure each team is aware of their own responsibilities, tasks, and deadlines.
   - Ensures that project deliverables are submitted to the project client.
2. Software Quality assurance (SQA)
   - Ensures that project client expectations are met and product quality is maintained by checking layout, formatting, and content guidelines set by the project client.
   - Tracks SQA revision history to be used in the SQA document.
   - Ensures that any succeeding documentation is consistent with previous documentations, with particular attention to the requirements specifications.
   - Revises any inconsistencies observed from the current documentation phase to previous phases.
   - Designs potential test cases for the current documentation phase.
    _An example scenario for the Requirements phase: the SQA team will determine a list of necessary actors to the StudySpace app and will make revisions to the initial draft if an actor deemed necessary to the app is not found within the initial draft._
   - Creates test cases without consulting the current phase's authors.
   - Validates results of designed test cases and suggests improvements based on results. 
3. Version control
   - Ensures that the final product is converted to HTML.
   - Ensures that all project documentation is neatly formatted, organized, and is made accessible to the project client.

**Implementation**
1. Frontend team
   - Collaboration
     - Informs the backend implementation team of the following:
       1. The various structures required for the frontend implementation of the StudySpace app.
       2. The attributes (fields) in each structure.
       3. The data type in which each attribute must be defined.
       4. The operations to perform for each field and structure as a whole.
   - Code
     - Implements the UI for the StudySpace app that fulfils all requirements and specifications as documented in the SRS, with particular attention to the external interfaces and layouts described in the document.
     - Designs the application in a way that allows all audiences to clearly determine the StudySense app's various functions, tools, services, and purpose.
     - Implements the application to be mobile-responsive and optimized for smart-phones.
     - Ensures that design choices are consistent throughout the whole application such that the StudySpace app looks unified as a product.
   - Documentation
     - Any decisions or agreements made between the frontend and backend team must be summarized and documented by any member of either team for future use and ease of accessibility.
   - Testing
     - Performs unit testing.
     - Performs integration testing to ensure that all software modules are integrated and tested to perform as a group as opposed to a single object, class, or function.
     - Performs UI testing.
     - Performs tests to determine that the product's user interfaces meet the requirements specifications.

2. Backend team
   - Collaboration
     - Informs the frontend team of any configuration procedures required to successfully access the database.
     - Informs the frontend team of any format requirements required to successfully query the database.
   - Code
     - Ensures that any user input is stored in the app's database.
     - Ensures that no unauthorized user may access the database and its contents.
     - Ensures that no user information is lost.
     - Designs database schema(s) in a way that fulfils and satisfies all data and formatting requirements set by the frontend team.
   - Documentation
     - Creates a properly documented API (see: Examples of properly documented API, Reference Materials) if a RESTful API is to be implemented.
     - Any decisions or agreements made between the frontend and backend team must be summarized and documented by any member of either team for future use and ease of accessibility.
   - Testing
     - Performs unit testing.
     - Performs integration testing to ensure that all software modules are integrated and tested to perform as a group as opposed to a single object, class, or function.
     - Performs schema testing.
     - Performs stored procedures and views testing.
     - Performs trigger testing.
     - Performs tables and columns testing.

3. Software Quality Assurance (SQA)
   - The SQA for the frontend will be conducted by the backend.
   - The SQA for the backend will be conducted by the frontend. 
   - Quality check
     - Ensures that code is properly commented.
     - Ensures that any written API is properly documented.
     - Ensures that variable names are meaningful.
   - Testing
     - Performs conformance testing, ensuring that the product conforms to the requirements specifications on which it is based.
     - Performs fuzz testing by providing invalid, unexpected, or random inputs to the frontend and backend applications. Fuzz testing will be conducted by both the frontend and backend teams by inserting random data inputs (normally, “Fuzz”) into various system inputs such as Sign-in forms and Search Bars to test if the system returns any unexpected results. If any unexpected results are returned, then the appropriate changes must be made to the frontend and backend components of the application. 
     - Performs interface testing, evaluating whether systems or components pass data and control correctly to one another.
     - Performs structural testing, considering the internal structure of a system or component and ensuring that each program statement performs its intended function.
     - Performs workflow testing, duplicating specific workflows which are expected to be utilized by the end-user.
     - Performs API testing, checking the functionality, reliability, and performance of the API.
     - Performs requirements testing, validating that the requirements are correct, complete, unambiguous, and logically consistent and allows designing a necessary and sufficient set of test cases from those requirements.

4. Documentation SQA
   - Documentation SQA refers to a team consisting of two members that will not participate in the Implementation phase and will edit various documents to ensure that all documents are consistent with respect to functionalities and requirements and reflective of any last-minute changes made in the Implementation phase. 
   - For an example of the changes made to past documents made by the Documentation SQA team, refer to Section [8.1: Appendex: Changes Made to Past Documents](#81-appendix-1-changes-made-to-past-documents)
### 4.2.3. Group Organization 
The diagram below should provide further clarification on the internal structure for future documentation phases and the Implementation phase. 

**Notes:**
- The numbers in brackets indicate the approximate number of people per subteam.
- The rectangles indicate the phase.
- The circles indicate the specific subteam in each phase. 
- The Documentation Phases mentioned in the diagram consist of the phases mentioned in Section 4.2.2. (Requirements, Analysis, Design) as the previous phases lacked an internal structure. 
- SQA for the frontend and backend teams were not indicated via circles because SQA for the frontend team will be conducted by the backend team and vice versa and is therefore considered redundant as notes were made on Section 4.2.1. 
 
#### 4.2.3.1. Group Organization Diagram

![](4231.png)

## 4.3. Project Responsibilities 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-lt9p{background-color:#F3F3F3;text-align:left;vertical-align:top}
.tg .tg-xqm4{background-color:#D9D9D9;font-weight:bold;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deliverable</span></th>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Authors (5-6)</span></th>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Review (SQA) (4)</span></th>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Management (1-2)</span></th>
    <th class="tg-xqm4"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Version Control (1-2)</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Specifications (SRS)</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arvin, Brian, David, Mackenzie, Matthew, Muhammad Hashir, Shyam, Zeeshan, Janelle, Ann</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Rohan, Dayton</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">N/A</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Rohan</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SPMP</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arshdeep, Ann, Janelle, Dayton</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Shyam, Matthew, Evan, Zeeshan, David</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">N/A</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Rohan</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Requirements</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mackenzie, Dayton, Arvin, Muhammad Hashir, Janelle, Rohan</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arshdeep, Shyam, Matthew, Evan, David</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann, Janelle</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Matthew</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Analysis</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arshdeep, Zeeshan, Brian, Matthew, Evan, Shyam</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Janelle, Arvin, Muhammad Hashir, Mackenzie, David</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Janelle, Dayton</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Design</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Arvin, Muhammad Hashir, Kevin, Zeeshan, Ann</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Rohan, Janelle, Mackenzie, Brian, David, Dayton</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Janelle, Dayton</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Rohan</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Implementation: Frontend</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Matthew, Zeeshan, Arvin, Muhammad Hashir, Rohan</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Backend team</span></td>
    <td class="tg-lt9p"></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Frontend team</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Implementation: Backend</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mackenzie, Kevin, Shyam, Ann, Evan, Brian, David</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Frontend team</span></td>
    <td class="tg-lt9p"></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Backend team</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Team Organization: Final</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Dayton, Janelle</span></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann</span></td>
    <td class="tg-lt9p"></td>
    <td class="tg-lt9p"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Ann</span></td>
  </tr>
</tbody>
</table>

# 5. Managerial Process Plans
## 5.1. Management Objectives and Priorities
The objective of this project is to produce a web application that provides post-secondary students with several tools, including virtual groups for studying and networking with new peers. The main target audience for this product is post-secondary students. However, secondary target audiences include tutors, alumni, and anyone looking to buy or sell textbooks. The main objective is to complete all workflows of the project by their respective deadlines, as determined by the professor. The main priorities are quality of work and time efficiency. Budget is not a priority because there is no intention for any amount of money to be spent on this project.
## 5.2. Work Plan
### 5.2.1. Work Activities and Schedule Allocation 
Each work activity has been scheduled in such a way that maximizes opportunities for different tasks to be done concurrently. Since each successive phase depends on having an established, agreed upon plan provided by the previous phases, it must be ensured that the next phase is never started before the deadline for SQA of the previous phase.

The resources used to complete the various work activities mentioned here include Google docs and GitHub. Google docs is used for writing the various drafts of each document and for the SQA team to make suggestions via the comment feature. GitHub is used to organize the documents and for general coordination of group processes.

#### 5.2.1.1. Work Activities and Schedule Allocation Table

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-kftd{background-color:#efefef;text-align:left;vertical-align:top}
.tg .tg-sd4m{background-color:#CCC;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-ktyi{background-color:#FFF;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Phase</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Starting</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deadline for first draft to be submitted to SQA</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deadline for SQA to finish Assessment</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deadline for final revision</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Convert document to HTML by</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Deadline to submit final product</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-kftd"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000">Specifications</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 18</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 23</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 25</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 28</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 29</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 29</span></td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000">SPMP</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 26</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Jan. 30</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 2</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 4</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 4</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 5</span></td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000">Requirements</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 5</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 9</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 10</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 11</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 11</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb. 12</span></td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000">Analysis</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb.20</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Feb.28</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 1</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 4</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 4</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 5</span></td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000">Design</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 6</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 18</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 23</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 25</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 26</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 26</span></td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000">Implementation</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Mar. 29</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">N/A</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">N/A</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Apr.11</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Apr.12</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Apr. 12</span></td>
  </tr>
</tbody>
</table>

## 5.3. Control Plan

### 5.3.1. Schedule Control Plan
Mechanisms used to measure progress and compare actual progress against planned progress include:
1. Weekly group meetings on Discord held every Saturday. These weekly meetings are intended to allow for regular check-ins and to ensure that all task forces are working on schedule.
2. Meetings amongst group members who are working together on a given workflow; scheduled as necessary by the respective management team.
3. For each workflow, there are 3 group members who are assigned the management role. The managers take ownership of the workflow and are responsible for establishing deadlines, heading meetings, reviewing the final documentation, and monitoring the progress of the workflow. The managers of a workflow must communicate to the rest of the group when issues with scheduling or completion arise.


When actual progress doesn’t meet planned progress, corrective actions include:
1. Making adjustments to scheduling to better suit the needs of the group members who require more time.
2. Assigning additional group members to the task that is demanding more time.
3. The management team responsible for the work devises an appropriate course of action that ensures everything gets done.


### 5.3.2. Quality Control Plan
Mechanisms used to control quality of work include:
1. An SQA team assigned to each individual phase of the project to ensure all work done by the authors is correct, detailed, and conforms to the plans established in the previous phases. If there has been an update to the project scope or plan, it is the responsibility of the SQA team to ensure that the version control teams of previous phases are notified in the event that their phase requires modifications due to this update.
2. Each workflow has a version control team (3 people) responsible for updating the documentation of their assigned workflow whenever changes are made in successive phases that do not conform to the plans as laid out in their documentation.
3. The management team is responsible for reviewing the editing process done in response to suggestions made by the SQA team. Managers must ensure that all quality assurance suggestions/concerns are properly addressed.
4. All contributors to a phase — whether an author, SQA, or manager — must review the documentation from all previous phases prior to starting to work on their assigned phase. This is to ensure that all members are aware of plans, goals, and vision for their phase, which have been laid out by the past phases of the project.
## 5.4. Risk Management Plan
### 5.4.1. Risk Map
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-sd4m{background-color:#CCC;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-ktyi{background-color:#FFF;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Likelihood/Impact</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Catastrophic</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Critical</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Significant</span></th>
    <th class="tg-sd4m"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Marginal</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Very Likely</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">R1</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">R2</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Likely</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">R3</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Unlikely</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
  </tr>
  <tr>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Very Unlikely</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
    <td class="tg-ktyi"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">none</span></td>
  </tr>
</tbody>
</table>

### 5.4.2. Risk Details

**R1: Could run out of time since we have a very tight schedule.**
_Mitigation strategy._
1. Start with a schedule that all group members can agree is reasonable.
2. Aim to get each phase done at least a day before its due date so there is a time buffer if needed.
3. For the implementation phase especially, plan for things to go wrong; allocate extra time.
4. The management team for each phase is responsible for establishing deadlines, tracking progress, and ensuring work is completed on time.

**R2: There will be many technical difficulties throughout the implementation phase because most group members are inexperienced with working on projects of this size.**
_Mitigation strategy._
1. Schedule enough time for more knowledgeable group members to guide others at first; anticipate a slow start as everyone learns.
2. Assign many group members to the SQA team and start SQA early on so that most bugs are identified while enough time is remaining for the programmers to actually fix them.
3. Make sure no programmer is given a workload that is too much for them to handle.
4. Group members who will be involved in the programming of the implementation phase should become familiar with the frameworks we plan to use ahead of time.


**R3: We might be underestimating the time, effort, and skills required to implement our project.**
_Mitigation strategy._
1. Compare our project with what has been accomplished in sample projects from previous years. If ours is a lot more complicated, consider which features are unnecessary and what can be removed.
2. Remember that the planning documents are all living documents -if, after writing them, we decide we won’t implement something we said we would, we can retroactively update previous documents. It is the job of the representatives of previous project phases to ensure the older documents are up to date with the current plan.

# 6. Technical Process Plans


## 6.1. Process Model

Development of the application is broken down into several documentation and implementation phases. Each phase is assigned a team of developers holding various roles that each focus on a specific work activity. Using the following organization, every aspect of development is streamlined and done effectively.

**Documentation**
- Authors
  - Writers of the initial draft; ensure content, format, and layout all follow standards and protocols.
- SQA Team
  - Review team that looks over initial draft, ensuring quality of work and standards are met according to the client’s expectations. 
- Management
  - Establishes, updates, and maintains project deadlines. Keeps the team on track and solves any potential issues that may arise.
- Version Control
  - Converts the final draft to proper HTML format, ensuring documentation is accessible and readable for the client. Also responsible for updating the document any time plans change.

**Implementation**
- Frontend Team
  - Implements the front end of the application, including UI/UX design. Tests code and ensures basic functionality before handing it over to the SQA team.
- Backend Team
  - Implements the back end of the application, including any database applications. Ensures code is free of glaring errors before it is handed to the testing team.
- Management
  - Has the same responsibilities as a documentation management team.
- SQA Team
  - Ensures all code follows the predetermined standards and protocols layed out in documentation. Tests the application rigorously.


The entire team will discuss the model and features we hope to implement and then assign each task to the appropriate team. Once major milestones are met, each teams’ work will be combined and a review team will ensure everything is working seamlessly. 

## 6.2. Methods, Tools, and Techniques

The developers will use Discord and Github to stay organized and coordinated. Developers will use VSCode along with any required plugins to write the code itself and use git commands to push any changes to the main project. All developers will agree to write code in a consistent style regarding things like brackets, comments, and indentation. A set standard will be agreed upon and all written code will be reviewed to ensure the standards are met. The appropriate database management software will be used to store and manage the user data and a schema of the database will be generated in said software.

# 7. Supporting Process Plans

## 7.1. Verification and Validation Plan

### 7.1.1. Verification Plan

The verification plan is to identify and ensure that features/activities establish abidance of the requirements.  Each features’ code will be tested by their original developers followed by another member of the development team and a final review given by a member of the software quality assurance team. Github will be used in order to track each document's revision history.

### 7.1.2. Validation Plan

The validation plan ensures that the application will meet customers’ expectations. Following the verification plan the same process will be met in validating that each activity on the front end of the application is working to the customers’ satisfaction.

## 7.2. Documentation Plan

Deadlines for each deliverable can be seen in the table displayed in [Section 5.2.1. Work Activities and Schedule Allocation.](#521-work-activities-and-schedule-allocation)

Each deliverable will be met by the following teams:

- **Authors:**
  - Formulate initial rough drafts on time in order to give the Quality Assurance team time to review
  - Edit documents based on Quality Assurance reviews


- **Quality Assurance Team (SQA):**
  - Review each version of the documents and leave comments for authors based on what can be improved
  - Edit grammar, punctuation, and spelling


- **Management Team:**
  - Establish deadlines
  - Create agenda for weekly meetings
  - Keep track of document progression
  - Communicate with all other teams to ensure each member is on the same page
  - Keep track of revision made for SQA document


- **Version Control Team:**
  - Ensures documents follow proper formatting
  - Coverts documents to HTML
  - Hosting documentation

## 7.3. Quality Assurance Plan

The Quality Assurance plan is managed by the quality assurance team of any given deliverable. This ensures that the final product of each deliverable complies to the satisfaction of the intended audience. 

## 7.4. Problem Resolution Plan

The Problem Resolution plan is managed by the management team of any given deliverable. This plan ensures that corrective actions will be taken when a problem occurs. 

- Corrective actions include:
- Timetable adjustments that benefit group members requiring additional time.
- Assigning the appropriate amount of group members to each task depending on the demands of said tasks.
- Communication with each team to confirm each task is completed according to the schedule.

These actions will be communicated via the team Discord server in which there are channels dedicated to each deliverable.

# 8. Appendix 

## 8.1. Appendix 1: Changes Made to Past Documents 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:9px 2px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:9px 2px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-nbj5{background-color:#FFF;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-c9ql{background-color:#D9D9D9;border-color:inherit;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-7btt{border-color:inherit;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg" style="undefined;table-layout: fixed; width: 1129px">
<colgroup>
<col style="width: 84px">
<col style="width: 94px">
<col style="width: 66px">
<col style="width: 66px">
<col style="width: 393px">
<col style="width: 57px">
<col style="width: 149px">
<col style="width: 114px">
<col style="width: 106px">
</colgroup>
<thead>
  <tr>
    <th class="tg-c9ql" colspan="9"><span style="font-weight:bold;background-color:#D9D9D9">SPMP</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-7btt"><span style="font-weight:bold">Date of </span><br><span style="font-weight:bold">Entry</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Contributor</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Version</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Section</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Description of Issue</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Status</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Comments</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Resolved by</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Date of </span><br><span style="font-weight:bold">Resolution</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.0</td>
    <td class="tg-c3ow">4.2.2</td>
    <td class="tg-c3ow">Elaborate on fuzz testing. He said, "Interesting reference to 'fuzz testing' - would like to see more detail about how that is to be done, tools used, etc."</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">3/30/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.0</td>
    <td class="tg-c3ow">4.2.2.</td>
    <td class="tg-c3ow">Unclear diagram for Group Structure. He said, "Not as clear on the diagram in section 4.2.2: 'Back End' shows up as both an oval and a rectangle, and I'm not clear on what the differences are."</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">3/30/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.0</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Formatting and hosting issue. He said, "List of Figures and Tables' should link directly to that figure, not the section, and the figure should be titled."</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.0</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Missing Group structure diagram to know who does what in all of the phases. He said, "Would like to see details of who is working on what section for material beyond the SPMP"</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">3/30/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.0</td>
    <td class="tg-c3ow">1.1.6</td>
    <td class="tg-c3ow">Change project deadline for Implementation to April 12, 2021</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">3/30/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">2.0</td>
    <td class="tg-c3ow">5.2.1</td>
    <td class="tg-c3ow">Make sure schedule is corrected, member allocation based on actual participation</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton, Janelle</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="9"></td>
  </tr>
  <tr>
    <td class="tg-c9ql" colspan="9"><span style="font-weight:bold;background-color:#D9D9D9">Specifications</span></td>
  </tr>
  <tr>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Entry</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Contributor</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Version</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Section</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Description of Issue</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Status</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Comments</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Resolved by</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Resolution</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.5</td>
    <td class="tg-c3ow">1.2</td>
    <td class="tg-c3ow">"Update Scope to clarify difference between StudySpace and something like MyLS (wrt chat rooms, discussions, groups)"</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Explained distinction from other applications</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">4/7/2021</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.5</td>
    <td class="tg-c3ow">1.2</td>
    <td class="tg-c3ow">"And be careful with the use of vague phrases such as "make it easier". As compared to what, specifically? What is it about this that is going to be easier?"</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Changed to "help" to be more concise </td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.5</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">Decide if we still need to have Private/Public Desks</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">In design we decided to keep this feature</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.5</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">Decide if we still need to have Private/Public Groups</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">This is no longer included (REMOVED)</td>
    <td class="tg-c3ow">Dayton </td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">4/7/2021</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">1.5</td>
    <td class="tg-c3ow">6</td>
    <td class="tg-c3ow">Version 1.1, 1.3, 1.5 and 1.6 sections missing from host</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow"></td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">1.6</td>
    <td class="tg-c3ow">2.2</td>
    <td class="tg-c3ow">Remove Public/Private groups and any mentioning of them in other defintions</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">4/7/2021</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">1.6</td>
    <td class="tg-c3ow">3.1</td>
    <td class="tg-c3ow">Remove layouts requirements because we decided not to support mobile devices</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Janelle </td>
    <td class="tg-c3ow">1.6</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">Removed voice chat and tutors definitions because they are not being implemented</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">1.6</td>
    <td class="tg-c3ow">3.2</td>
    <td class="tg-c3ow">Updated password requirements</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Password requirements now reflect those outlined in design data dictionary</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">4/7/2021</span></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">1.6</td>
    <td class="tg-c3ow">3.3</td>
    <td class="tg-c3ow">Update Logical Database Requirements based on design doc</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">4/7/2021</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">1.6</td>
    <td class="tg-c3ow">2.5</td>
    <td class="tg-c3ow">Remove mentioning of mobile device compatibility</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">1.6</td>
    <td class="tg-c3ow">3.4.2</td>
    <td class="tg-c3ow">Remove mentioning of mobile device compatibility </td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle </td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="9"></td>
  </tr>
  <tr>
    <td class="tg-c9ql" colspan="9"><span style="font-weight:bold;background-color:#D9D9D9">Requirements Specifications</span></td>
  </tr>
  <tr>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Entry</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Contributor</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Version</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Section</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Description of Issue</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Status</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Comments</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Resolved by</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Resolution</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/13/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">Remove mention of Tutors</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">3/24/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/19/2021</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">Add Interests definition and remove mentioning of "preferences"</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle/Dayton</td>
    <td class="tg-c3ow">3/24/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/24/2021</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">3.2</td>
    <td class="tg-c3ow">Update section 3.2 to match design document</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">3/24/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">2.1.1.</td>
    <td class="tg-c3ow">Update User Interfaces to be consistent from Design Section 9 (e.g. the color schemes are different)</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">4/10/2021</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">2.3</td>
    <td class="tg-c3ow">"Create Moderator and Delete Moderator are separate use cases so no line should connect between either use case"</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">2.3</td>
    <td class="tg-c3ow">Decide if Moderator and Administrators need to be removed</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Both are in the design doc, as long as they are used in implementation then they will remain in the requirements doc</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">2.3</td>
    <td class="tg-c3ow">"Not clear why the user has a password, but the 'User sign-in' (3.1) specifies "There are no password requirements"."</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/7/2021</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">1.3</td>
    <td class="tg-c3ow">Add Upvote/Downvote definition as it has been decided to keep</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">4/7/2021</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="9"></td>
  </tr>
  <tr>
    <td class="tg-c9ql" colspan="9"><span style="font-weight:bold;background-color:#D9D9D9">Analysis</span></td>
  </tr>
  <tr>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Entry</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Contributor</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Version</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Section</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Description of Issue</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Status</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Comments</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Resolved by</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Resolution</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/13/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Decide if Moderator and Administrators need to be removed</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">Both are in the design doc, as long as they are used in implementation then they will remain in the requirements doc</span></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/19/2021</td>
    <td class="tg-c3ow">Mackenzie</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow"></td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">Database design differs from UML class diagram</span></td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Replaced old UML class diagram with the diagram from section 7.1 in the design doc</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">3/19/2021</span></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">2.2</td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">Add Interests definition and remove mentioning of "preferences"</span></td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-nbj5"><span style="color:#000;background-color:#FFF">3/24/2021</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/24/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Decide on using New Posts vs Past Posts vs Posts </td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Decided on using the term "Posts" only</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/24/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">2.2</td>
    <td class="tg-c3ow">Clarify Top Groups definition</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">3/24/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/24/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">2.2</td>
    <td class="tg-c3ow">Decide naming, if using Top Suggested Groups or Top Groups</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">keep as Top Groups</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">3/24/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/24/2021</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">2.2</td>
    <td class="tg-c3ow">Remove mention of Tutors</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">3/24/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/24/2021</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">6</td>
    <td class="tg-c3ow">Update section 6 to match the chat class outlined in design doc </td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">3/24/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">2.1</td>
    <td class="tg-c3ow">Receive' is spelled incorrectly in the Object Diagram.</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow"><span style="font-style:normal">Naming approach is confusing. He said, "The naming approach for the UML Diagram (they are all UML diagrams - I gather this is a class diagram) is inconsistent and a bit odd.</span><span style="font-weight:bold;font-style:normal"> All attributes - except in the Main and Events classes - are preceded by the class name and period, e.g. 'Friend.id'. Since these attributes are given inside the class box, is there really a need to repeat the class name with every attribute,</span><span style="font-style:normal"> or is this a language naming requirement? If so, what is the language?"</span></td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Updated subheading to "UML Class Diagram". Now that this diagram has been replaced with the one from the design doc, the attribute naming issue is resolved.</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">3.1</td>
    <td class="tg-c3ow">Vague statements. He said, "The description of the User Controller Event Loop, "The loop goes through the different classes", is a somewhat vague."</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Removed this description as it is redundant</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">4</td>
    <td class="tg-c3ow">Vague statements. He said, "So are statements like "User will see when disconnecting from a DESK." in the Non Functional Attributes. See what, exactly? "</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Fixed wording to clarify that the system is able to see when users are disconnected from a desk</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">4</td>
    <td class="tg-c3ow">Incorrect understanding of Non-functional attributes. He said, "And seeing message boxes are functional. Non functional attributes are more along the lines of timing expectations - things the user doesn't directly see."</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Not quite sure the meaning of this, I went in and made a few changes to our bullet points but honestly don't know</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow">Repetitious and incorrect UML class diagrams. He said, "The UML diagram is repetitious in terms of attributes. e.g. the 'has' association between Events and Chat shows that an Events object has a Chat object (and that should be 0..1 not 'many to one'). Since the association shows this, you do not need a 'Chat' attribute given in the Events class box. The Page to Post 'has' association correctly demonstrates this."</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Fixed in design doc, copied over here.</td>
    <td class="tg-c3ow">Janelle</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-c3ow">3/30/2021</td>
    <td class="tg-c3ow">Dbrown</td>
    <td class="tg-c3ow">1.4</td>
    <td class="tg-c3ow">6</td>
    <td class="tg-c3ow">Unfinished and unclear Message Protocol. He said, "The entire Message Protocol section is a bunch of hierarchical bullet points with no explanatory text, and refers only to the Chat class. This seems very unfinished."</td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow">Removed due to redundancy with class diagram</td>
    <td class="tg-c3ow">Dayton</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="9"></td>
  </tr>
  <tr>
    <td class="tg-c9ql" colspan="9"><span style="font-weight:bold;background-color:#D9D9D9">Design</span></td>
  </tr>
  <tr>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Entry</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Contributor</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Version</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Section</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Description of Issue</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Status</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Comments</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Resolved by</span></td>
    <td class="tg-7btt"><span style="font-weight:bold">Date of Resolution</span></td>
  </tr>
  <tr>
    <td class="tg-c3ow">4/10/2021</td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">3.0</td>
    <td class="tg-c3ow">4, 5</td>
    <td class="tg-c3ow">Change chosen database from SQLite to PostgreSQL, include explanation that SQLite isn't production-level and doesn't have good integration integration Heroku. </td>
    <td class="tg-c3ow">done</td>
    <td class="tg-c3ow"></td>
    <td class="tg-c3ow">Ann</td>
    <td class="tg-c3ow">4/10/2021</td>
  </tr>
  <tr>
    <td class="tg-0pky" colspan="9"></td>
  </tr>
</tbody>
</table>
