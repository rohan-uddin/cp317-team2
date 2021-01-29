<h2> StudySpace Software Requirement Specification </h2>

- [1. Introduction](#1-introduction)
  - [1.1. Purpose](#11-purpose)
  - [1.2. Scope](#12-scope)
  - [1.3. Definitions](#13-definitions)
  - [1.4. References](#14-references)
  - [1.5. Overview](#15-overview)
- [2. Overall Description](#2-overall-description)
  - [2.1. Product Perspective](#21-product-perspective)
    - [2.1.1. User Interfaces](#211-user-interfaces)
    - [2.1.2. Software Interfaces](#212-software-interfaces)
  - [2.2. Product Functions](#22-product-functions)
  - [2.3. User Characteristics](#23-user-characteristics)
  - [2.4. Constraints](#24-constraints)
  - [2.5. Assumptions and Dependencies](#25-assumptions-and-dependencies)
- [3. Specific Requirements](#3-specific-requirements)
  - [3.1. External Interface](#31-external-interface)
  - [3.2. Functions](#32-functions)
  - [3.3. Logical Database Requirements](#33-logical-database-requirements)
- [4. Software System Attributes](#4-software-system-attributes)
  - [4.1. Security](#41-security)
  - [4.2. Portability](#42-portability)
- [5. Versions](#5-versions)
  - [Version 1.0 - 19/01/2021](#version-10---19012021)

### 1. Introduction
StudySpace is a web application that provides post-secondary students with access to virtual spaces that foster unique social learning environments. The purpose of this project is to promote a sense of unity and community among students by helping them meet new peers, connect, and study together.

#### 1.1. Purpose
The purpose of this document is to establish the requirements of the project from an implementation perspective. Additionally, this document lays the foundation for all group processes from start to finish by outlining the vision for the project. This document is intended to be used by developers, users, and any other individual who wants to learn the concept of this application and how it’s features work.

#### 1.2. Scope
StudySpace allows users to search for and join virtual study groups. User benefits include improving academic success, making friends, and gaining a sense of community among peers. The objective of StudySpace is to make it easier for students to find groups of like-minded individuals who they can collaborate with -regardless of their physical locations. Through the use of this product, even students who are enrolled in online courses do not miss out on the benefits of group work and peer discussion.


#### 1.3. Definitions
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

#### 1.4. References
IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998

#### 1.5. Overview
The rest of this document contains details about the overall description and specific requirements of the project. Section 2 contains information about the product perspective, product functions, user characteristics, constraints, and dependencies. Section 3 discusses external interfaces, functions, logical database requirements, and software system attributes.

### 2. Overall Description

#### 2.1. Product Perspective
StudySpace is an independent, self-contained web application. Core features are personalized profiles, groups, chats and pages in each group. It is a web application with 2 components: user interfaces (front end), and software interfaces (back end).

##### 2.1.1. User Interfaces

**Search bar** 
StudySpace has a search bar along the top, icons to log in, and a home page with general information that appears upon entering the site. Users can use the search bar to navigate to groups that interest them. 

**Profile** 
Once logged in, a user will see a link to their profile. This link remains present as the user navigates the website. On the left side of this page, users can view/edit their preferences and other personal information. On the right, there are two lists: a list of groups the user is a part of, and a list of users they are friends with. By clicking on one of the groups, the user is taken to the group page for that specific group. By clicking on one of the users, the user is taken to the profile page of that user. Since the users are friends, the friends’ profile page will contain a button near the top, labelled “Message”, which the User can click to send a direct chat to that friend.

**Create new post** 
On the group page, there is a button at the top that allows the user to create a new post. Taking up the centre of the group page is a list of titles corresponding to previously-published posts belonging to the group. The posts are sorted by popularity.  

**Full-screen view of the post**
Clicking on the title of a post brings the user to a page containing a full-screen view of the post, with the title and total number of upvotes/downvotes at the top, and the body of the post underneath. On either side of the upvotes/downvotes count are two arrow-shaped buttons; one pointing up and one pointing down. To upvote this post, the user must simply click the upward-pointing arrow. To downvote the post, the user must click the downward-pointing arrow. From this view, the responses to the post are also visible; they are displayed below the body of the original post. In between the body of the post and its responses, there is a textbox and a “Reply” button to the right of it. These features allow the user to submit a response to the post. 

**Chat box**
On the right-hand side of the group page is a chat box where members of the group can send text messages for others members to see.

**User pop-up**
Any post, response, or chat displays a link which is the username of the user who sent/posted it. For posts, the username is displayed at the top next to the title. For responses and chat messages, the username of the sender is displayed directly above the body of the message. Clicking on the username brings the user to the profile of the user who sent/posted the item. Users can view the preferences and personal information of another user via their profile. While viewing another user’s profile, a user also has the option to request to be their friend via a button in the top-right corner labelled “Send Friend Request”.

**User match bar**
Along the left side of any group page is a list of user matches. User matches are based on the number of preferences two users have in common. Clicking on an entry in this list will bring the user to the profile of the matched user/suggested friend’s page where they can send a friend request if they would like.

##### 2.1.2. Software Interfaces
On the backend, clicking on groups, profiles, or posts sends a request to the database containing all information required by the site. The database must return said required information.

The chat function is also handled by the backend.

#### 2.2. Product Functions

Users can create their own group with a desired set of members or a specific topic. New groups may not share a name with existing groups. Users can create posts, comment on posts, chat, log in, and send friend requests to other users. 


**Private Group - Signed In Users**
Posts are only visible to users who have joined the group. Thus, users who have not joined the group cannot vote, comment on, or create any posts.

**Private Group - Users Who Are Not Signed In**
Posts are not visible. Thus, users who have not signed in cannot vote or comment on any posts. 

**Public Group - Signed In Users**
Posts are visible to everyone. Users who have not joined the group may still view the   group’s posts. Thus, any user can vote and comment on any posts. Any user could also make a post in the group. 

**Public Group - Users Who Are Not Signed In**
Posts are visible to everyone. Users who are not signed in can only view the posts. They cannot comment or vote.

**Voting and Commenting On A Post**
All users, including the post’s author, can upvote or downvote only once. Only users who are members of a private group can vote and comment on posts in said private group. All signed-in users can vote on posts and make comment(s) in a public group. 


#### 2.3. User Characteristics
Post-secondary students are the intended users of this product. As such, it is assumed that the user is educated and has experience using a web browser and navigating websites. It is helpful -but not necessary- for the user to have experience with common social media platforms, such as Reddit, Instagram, or Twitter. This experience should aid the user in learning how some features of StudySpace work, such as chat, due to the similarities to other social media.

#### 2.4. Constraints
A large number of users must be able to access the website at once. To ensure the website is reliable, smooth, and feels responsive to the user, chat logs should update within a second whenever a user sends a chat.

#### 2.5. Assumptions and Dependencies
It is assumed that users have a functioning, web-capable device with a browser installed. Users are expected to have an internet connection for the entire duration of their session. StudySpace should be compatible with any operating system and it does not matter whether a mobile device or desktop is used. 

### 3. Specific Requirements

#### 3.1. External Interface
Layouts
- Mobile-responsive and adaptive for screens 320px in width (smallest screen for a device) and above.

Posts
- Beside each post, there is an “upvote” or “downvote” icon.  
Upvoting a post increases the total number of upvotes/downvotes by 1, and downvoting decreases the total by 1. 
- Any user, including the author of the post, can only upvote or downvote a post once. The total number of upvotes/downvotes can be less than 0 if the number of downvotes exceeds the number of upvotes.
- Only loading in a small amount of posts initially. More posts will load as the user scrolls up.
- If no posts have been made to a group, a message is displayed which says, “There are no posts here.”
- When creating a post, there are requirements that must be met before it can be published. All posts need a title and at least one character of body text.

#### 3.2. Functions
Creating, editing, deleting post
- Once a user has created a post, they can edit or delete the post by accessing it via the group page where it is posted.
  
Searching
- Any additional spaces or misspelled words in the search bar must be understood. For example “CP31 7 Wilfred” must show the intended results of “Cp317 Wilfrid”.
Implemented by a Full-Text-Search in the relational database which is part of the backend.

User sign-in
- When users sign in, the email form must be in proper email format (eg; having “@” in their email address”). 
- There are no password requirements.
- Users stay logged in until they sign out. 

#### 3.3. Logical Database Requirements
| USERS:  |   contains a record for every user that has created a profile                                                                                             |
|--------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| Fields                                                             | A User ID unique to the User A User’s preferences  A User’s personal information (name, major) |
| Relationships                                                      |  The user id is the primary key of the USERS table.                                            |


| FRIENDS:   |  contains a record for every friendship relation                                                                                                           |
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Fields                                                    | A unique Friendship ID for each Friendship Two User ID fields, one for each User involved in the friendship |
| Relationships                                             |  The friendship ID is the primary key of the FRIENDS table.                                                 |

| GROUPS: |  contains a record for every group in the system                                                                                                                                                                     |
|---------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Fields                                                  | A unique Group ID Group name Group members  Note: the group members field contains all the members of a group assigned to a record, which is a multivalued attribute |
| Relationships                                           | The group ID is the primary key of the GROUPS table.                                                                                                                 |


| POSTS:  | contains a record for every post that has ever been published                                                                                                                                                                                |
|----------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Fields                                                               | A unique Post ID for each Post The ID of the group it was posted in The Post title The Post’s body text The Post’s total number of upvotes The Post’s total number of downvotes |
| Relationships                                                        |  The post ID is the primary key of the POSTS table.                                                                                                                             |

| RESPONSES:  |  contains a record for every response that has ever been made to a post                                                                                             |
|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Fields                                                                            | A unique Response ID The text stored in the Response The ID of the Post it is associated with |
| Relationships                                                                     |  The response ID is the primary key of the RESPONSES table.                                   |

### 4. Software System Attributes
	
#### 4.1. Security
Any access to the StudySpace backend needs to be verified to ensure that only authorized administrators/moderators have access. Authorization involves entering a valid username and password to an account with administrator privileges. When an administrator or moderator logs into the system, they are granted permissions to edit, create, and delete content.
	
#### 4.2. Portability 
StudySpace must be accessible on any mobile or desktop device that is web-capable and has a browser. Therefore, StudySpace must be compatible with any operating system, including Windows, Mac OS, Linux, iOS and Android. The product must also be compatible with any browser, including Chrome, Firefox, Internet Explorer, Edge, and Safari.

### 5. Versions

#### Version 1.0 - 19/01/2021 

Author(s)

- Arvin
- Brian
- David
- Mackenzie
- Matthew
- Muhammed
- Shyam
- Zeeshan

Document conversion, re-formatting according to known standards, and cleanup
- Rohan 

<h5> Version 1.2 - 25/01/2021 </h5>

SQA
- Dayton 

Revision edits made by

- Janelle 

Document conversion, re-formatting according to known standards, and cleanup

- Janelle 
- Mackenzie
- Matt
- Ann

<h5> Version 1.4 - 28/01/2021 </h5>

SQA
- Dayton 

Revision edits made by

- Janelle 

Document conversion, re-formatting according to known standards, and cleanup

- Ann

