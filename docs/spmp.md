

<h1>  Software Project Management Plan (SPMP)  </h1>

<h2> Signature page </h2>

<h2> Revision history </h2>

<h2> Table of Contents </h2>

- [1. Overview](#1-overview)
  - [1.1. Project Summary](#11-project-summary)
    - [1.1.1. Purpose, Scope, and Objectives](#111-purpose-scope-and-objectives)
    - [1.1.2. Assumptions and Constraints](#112-assumptions-and-constraints)
    - [1.1.3. Project Deliverables](#113-project-deliverables)
    - [1.1.4. Schedule and Budget Summary](#114-schedule-and-budget-summary)
  - [1.2. Evolution of the Plan](#12-evolution-of-the-plan)
- [2. Reference materials](#2-reference-materials)
- [3. Definitions](#3-definitions)
- [4. Project Organizations](#4-project-organizations)
  - [4.1. Organizational structure](#41-organizational-structure)
  - [4.2. Roles and Responsibilities](#42-roles-and-responsibilities)
- [5. Managerial process plans](#5-managerial-process-plans)
  - [5.1. Management Objectives and Priorities](#51-management-objectives-and-priorities)
  - [5.2. Assumptions, Dependencies and Constraints](#52-assumptions-dependencies-and-constraints)
  - [5.3. Work plan](#53-work-plan)
    - [5.3.1. Work activities and schedule allocation](#531-work-activities-and-schedule-allocation)
  - [5.4. Control plan](#54-control-plan)
    - [5.4.1. Schedule control plan](#541-schedule-control-plan)
    - [5.4.2. Quality control plan](#542-quality-control-plan)
  - [5.5. Risk management plan](#55-risk-management-plan)
    - [5.5.1. Risk map](#551-risk-map)
    - [5.5.2. Risk details](#552-risk-details)
- [6. Supporting process plans](#6-supporting-process-plans)
  - [6.1. Configuration management plan](#61-configuration-management-plan)
  - [6.2. Verification and validation plan](#62-verification-and-validation-plan)
  - [6.3. Documentation plan](#63-documentation-plan)
  - [6.4. Quality assurance plan](#64-quality-assurance-plan)
  - [6.5. Problem resolution plan](#65-problem-resolution-plan)
- [7. Index](#7-index)
- [8. Versions](#8-versions)
  - [8.1. Version 1.0](#81-version-10)
  - [8.3. Version 2.0](#83-version-20)
  
<h2> List of figures </h2> 
<h2> List of tables </h2>

---

## 1. Overview

### 1.1. Project Summary
#### 1.1.1. Purpose, Scope, and Objectives
#### 1.1.2. Assumptions and Constraints
#### 1.1.3. Project Deliverables
#### 1.1.4. Schedule and Budget Summary
### 1.2. Evolution of the Plan

---

## 2. Reference materials

--- 

## 3. Definitions

--- 

## 4. Project Organizations 
### 4.1. Organizational structure
### 4.2. Roles and Responsibilities

--- 
## 5. Managerial process plans

### 5.1. Management Objectives and Priorities
The objective of this project is to produce a web application that provides university students with several tools, including virtual study groups. The main objective is to complete all workflows of the project by their respective deadlines, as determined by the professor. The main priorities are quality of work and time efficiency. Budget is not a priority because there is no intention for any amount of money to be spent on this project.

### 5.2. Assumptions, Dependencies and Constraints
The assumptions of this project are:
1. Each workflow has 2 groups of contributors.
  a. Those who write/code (the authors).
  b. Those who make suggestions for revisions and look for defects (the SQA team).
  c. The authors and SQA group members will vary between workflows, but each group member will, in some way, contribute to MOST workflows.
2. Availability.
  a. All group members are assumed to be available to help out with most workflows.
  b. It is assumed that all group members can be reached via discord on a regular basis.
  c. It is assumed that all group members have/can obtain the necessary software and equipment needed to complete their assigned tasks.
3. Skills.
   It is assumed that not all group members have the same set of skills or abilities. However, it is assumed that regardless of level of expertise, all members are ready and willing to learn and continuously try their best to help out and contribute however they can.

The dependencies are:
1. In order to begin the next workflow, at minimum, the first version of the previous workflow must be completed and of high quality and detail.
2. In order for the SQA team to perform quality assurance, the first draft/version of the document or code in question must already be complete.
3. Before submitting a finalized version of a document or code, all concerns, suggestions, and defects pointed out by the SQA team must be addressed.
4. If any changes are made to the project plan or certain specifications are not implemented, the appropriate updates must be made to past documentation to ensure they align with the outcome of the project.
  
The constraints are:
1. Time. 
   There are set deadlines for each workflow, and the entire project must be done in less than four months.
2. Inexperience.
   As third year undergraduate students, most group members are inexperienced in developing large software projects as part of a group. Some group members are inexperienced with the software, programming languages, and other technology that will be used for the implementation of the project.


### 5.3. Work plan
#### 5.3.1. Work activities and schedule allocation

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

### 5.4. Control plan
#### 5.4.1. Schedule control plan
Mechanisms used to measure progress and compare actual progress against planned progress include:
1. Weekly group meetings on discord that are held every Saturday. These weekly meetings are intended to allow for regular check-ins and to ensure that all task forces are working on schedule.
2. Teams assigned to write and perform SQA on individual project phases are appointed a “communicator” member, who is responsible for communicating to all outside members if their team is having an issue with timing or scheduling.
   
When actual progress does meet planned progress, corrective actions include:
1. Making adjustments to scheduling the better suit the needs of the group members who require more time.
2. Assign additional group members to the task that is demanding more time. 

#### 5.4.2. Quality control plan
Mechanisms used to control quality of work include:
1. An SQA team assigned to each individual phase of the project to ensure all work done by the authors is correct, detailed, and conforms to the plans established in the previous phases. If there has been an update to the project scope or plan, it is the responsibility of the SQA team to ensure that the representatives of previous phases are notified in the event that their phase requires modifications due to this update.
2. Each project phase has a representative who is responsible for updating the documentation of their phase whenever changes are made in successive phases that do not conform to the plans as laid out in their own documentation.
3. All contributors to a phase -whether an author or SQA team member- must review the documentation from all previous phases prior to starting to work on their own phase. This is to ensure that all members are aware of plans, goals, and vision for their phase, which have been made by the past phases of the project.

### 5.5. Risk management plan
#### 5.5.1. Risk map

| Likelihood/Impact | Catastrophic | Critical | Significant  | Marginal |
|-------------------|--------------|----------|--------------|----------|
| Very Likely       | none         | R1       | R2           | none     |
| Likely            | none         | none     | R3           | none     |
| Unlikely          | none         | none     | none         | none     |
| Very Unlikely     | none         | none     | none         | none     |

#### 5.5.2. Risk details
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

### 8.1. Version 1.0
-   [2021-01-19] Janelle Tait (Layout)
-   [2021-01-25] Janelle Tait (Author)
-   [2021-01-??] 

### 8.3. Version 2.0