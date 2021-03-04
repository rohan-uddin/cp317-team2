<h2> Analysis </h2>

*Version 1.3*

<h2> Table of Contents </h2>

- [1. Introduction](#1-introduction)
	- [1.1. Project Summary](#11-project-summary)
	- [1.2. Project Purpose](#12-project-purpose)
- [2. Object Classification](#2-object-classification)
	- [2.1. Object Diagram](#21-object-diagram)
	- [2.2. Entity Objects](#22-entity-objects)
	- [2.3. Control Objects](#23-control-objects)
	- [2.4. Boundary Objects](#24-boundary-objects)
- [3. Controller Diagrams](#3-controller-diagrams)
	- [3.1. User Controller Event Loop](#31-user-controller-event-loop)
	- [3.2. User Controller Class](#32-user-controller-class)
	- [3.3. Group Controller Class](#33-group-controller-class)
	- [3.4. Event Controller Class](#34-event-controller-class)
- [4. Non Functional Attributes](#4-non-functional-attributes)
- [5. Classes](#5-classes)
- [6. Message Protocol](#6-message-protocol)
- [7. Versions](#7-versions)

# 1. Introduction

## 1.1. Project Summary
StudySpace is a web application that provides post-secondary students with access to virtual spaces that foster unique social learning environments, promoting a sense of unity among students by helping them meet new peers, connect, and anstudy together.

## 1.2. Project Purpose
The following document will cover the analysis portion of StudySpace. It will explain features of the application and their respective uses. This document is intended to be used by developers, users, and any other individual who wants to learn the concept of this application and how it’s features work.

# 2. Object Classification
## 2.1. Object Diagram

![StudySpace Object Diagram](CP_317_Analysis_Object_Diagram_V4-1.jpg)

## 2.2. Entity Objects

1. **DESK**
  A Desk is a virtual space wherein students may collaborate privately or publicly.
	Each desk is temporary; it only exists so long as there are people using it. After everyone leaves the desk, it is purged from memory.
	Each desk has an admin who can set a limit to the number of members and add signifiers such as language, age category, and other factors.
	Users can sort desks based on their preferences (see: Private Desk), or join a random one (see: Public Desk).
2. **FRIENDS**
   Any two Users can become Friends if one sends a Friend Request and the other accepts it. When two Users are Friends, they are able to send private chats directly to one another.
3. **GROUP**
   A Group is a collection of two or more users who have connected through StudySpace either by Invitation or a User Match. All members of a Group automatically have access to a Chat upon joining.
4. **USER**
   Typically a Student is a user enrolled in any Canadian university, who seeks the use of a Desk.
5. **POST**
   A Post is an object which can include photos and text. Posts are created by Users for all members of a Group to see. Users can make a Post about anything they wish, including: buying/selling textbooks, searching for a tutor, asking questions, looking for advice, etc. Users can write a Response to a Post.
6. **PAGE**
   A Page is where Posts are viewed. Each Group can have one or more Pages.
7. **PROFILE**
  A page with personal information about the user. The Profile also provides functionality such as managing group memberships and accessing chats.

## 2.3. Control Objects
- **Authenticator**
  Authenticates the user, provided an email and password.
- **User Interface**
	Controls the interface that the user interacts with, allowing them to perform various functions such as Chat, Send, Receive, Show, Usermatch, Search, and Invite.

## 2.4. Boundary Objects
- **SEND**
Enables Users to send chat messages to each other and amongst groups with the chat feature. Chat messages are sent, received and viewed through a chat box.
- **RECEIVE**
Users can receive messages from other users directly and from fellow group members in a group-wide discussion. Chat messages are sent, received and viewed through a chat box.
- **SEARCH**
Using a search bar, Users can search and discover Groups by Group Name or Users by Username. The search function uses full-text-search to search for results in the database that match the Search query.
- **POST**
Creates or edits a post for the group. When creating a new post, the user is prompted to enter the content of their post in a text box, and the title of their post in another text box.
- **INVITE**
Invites a member to the group. An Invitation is the opportunity for a User to join a Private Group. Any member of a Private Group can choose to send an Invitation to a User who isn’t already a member. Through the group page, members are invited by clicking an “Invite” button next to their username in the search results for the user to be invited.
- **USERMATCH**
Matches user with another user. Suggested user matches are displayed in a list on a group page. To match with one of these suggested matches and add them as a friend, the user must click a “Match” button next to their username in this list.
- **SHOW**
	- Shows a room that users can join when a ‘Desk’ is created.
	- Shows a user’s profile and their info.
	- Shows all of a user’s friends.
	- Shows information about a group.
	- Shows all members in a group.
	- Shows posts in groups, the contents of a post, the person who posted it, and the comments on the post.
- **AUTHENTICATE**
Authenticates a user; verifies their identity by requiring the entry of a correct email and password combination. Upon logging in, the user will be required to enter their email and password in two separate text boxes.
- **CHAT**
  A Chat is a feature where all members of a Group can send text messages to each other. Two users can also send direct chats to one another if they are friends. The Chat is viewed through a chat box on the Group’s page, or through the user’s main page in the case of direct chat conversations.
 
# 3. Controller Diagrams

## 3.1. User Controller Event Loop

The loop goes through the different classes. 

![User Controller Event Loop](User%20Controller%20Event%20Loop.png)

## 3.2. User Controller Class

Handles all functions regarding profiles and friends.

![User Controller Class](User%20Controller%20Class.png)

## 3.3. Group Controller Class

Handles all functions regarding groups. 

![Group Controller Class](Group%20Controller%20Class.png)

## 3.4. Event Controller Class
Handles all the events triggered regarding posts, chats and friends functionalities.

![Event Controller Class](Event%20Controller%20Class.png)

# 4. Non Functional Attributes
- User will see a screen when joining a DESK.
- User will see when disconnecting from a DESK.
- Messages will pop up on the screen when sent.

# 5. Classes

![UML Class Diagram](UML_class_CP317_4-1.png)

# 6. Message Protocol
-  user_authentication (email, password)
- Chat Class
  - storeMessage()
  - receiveMessage()
  - sendMessage()
    - ChatInfo(String)
      - firstName(String)
      - lastName (String)
      - onlineStatus(string)
      - userId(int)

# 7. Versions
<h5> Version 1.0 - 02/20/2021 </h5>

Author(s)

Initial Analysis document created.
- Shyam Dave
- Matthew Francis
- Arshdeep Sahi
- Zeeshan Jafri
- Evan Surtel
- Brian Carvalho

<h5>Version 1.1 - 03/03/2021 </h5>

Adjusted document upon SQA suggestions.

- Brian Carvalho
- Shyam Dave
- Matthew Francis
- Evan Surtel
- Arshdeep Sahi

Thanks to SQA by
- Janelle Tait
- David Rosien
- Arvin Armin
- Mackenzie van Zanden
- Muhammed Hashir

<h5> Version 1.2 - 03/03/2021 </h5>
	
Adjusted object diagram according to SQA suggestions
- Brian Carvalho

Thanks to SQA by
- Janelle Tait

<h5> Version 1.3 - 03/04/2021 </h5>

Adjusted object diagram according to SQA suggestions
- Brian Carvalho

Thanks to SQA by
- Janelle Tait





