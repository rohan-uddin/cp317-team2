- [1. Introduction](#1-introduction)
  - [1.1. Purpose](#11-purpose)
  - [1.2. Scope](#12-scope)
  - [1.3. Definitions](#13-definitions)
  - [1.4. References](#14-references)
  - [1.5. Overview](#15-overview)
- [2. Overall Description](#2-overall-description)
  - [2.1. Product Perspective](#21-product-perspective)
    - [2.1.1. User Interfaces](#211-user-interfaces)
      - [2.1.1.1. Landing Page (logged out)](#2111-landing-page-logged-out)
      - [2.1.1.2. Sign Up View](#2112-sign-up-view)
      - [2.1.1.3. Home Page (Logged In)](#2113-home-page-logged-in)
      - [2.1.1.4. Groups Home Page](#2114-groups-home-page)
      - [2.1.1.5. Desk View](#2115-desk-view)
      - [2.1.1.6. Posts View](#2116-posts-view)
      - [2.1.1.7. User Profile Page](#2117-user-profile-page)
      - [2.1.1.8. Profile Page (another user)](#2118-profile-page-another-user)
      - [2.1.1.9. User Match View](#2119-user-match-view)
  - [2.2. Product Functions](#22-product-functions)
  - [2.3. Actors and Use Cases](#23-actors-and-use-cases)
    - [2.3.1. Administrator Functions](#231-administrator-functions)
    - [2.3.2. Moderator Functions](#232-moderator-functions)
    - [2.3.3. User Functions](#233-user-functions)
  - [2.4. User Characteristics](#24-user-characteristics)
  - [2.5. Constraints](#25-constraints)
  - [2.6. Assumptions and Dependencies](#26-assumptions-and-dependencies)
- [3. Specific Requirements](#3-specific-requirements)
  - [3.1. Function Requirements](#31-function-requirements)
  - [3.2. Logical Database Requirements](#32-logical-database-requirements)
  - [3.3. Software System Attributes](#33-software-system-attributes)
    - [3.3.1. Performance Requirements](#331-performance-requirements)
    - [3.3.2. Security](#332-security)
    - [3.3.3. Portability](#333-portability)
- [4. Version History](#4-version-history)
  
# 1. Introduction
StudySpace is a web application that provides post-secondary students with access to virtual spaces that foster unique social learning environments. The purpose of this project is to promote a sense of unity and community among students by helping them meet new peers, connect, and study together.

## 1.1. Purpose
The purpose of this document is to establish the requirements of the project from an implementation perspective. Additionally, this document lays the foundation for all group processes from start to finish by outlining the vision for the project. This document is intended to be used by developers, users, and any other individual who wants to learn the concept of this application and how its features work.

## 1.2. Scope
StudySpace allows users to search for and join virtual study groups. User benefits include improving academic success, making friends, and gaining a sense of community among peers. The objective of StudySpace is to help students find groups of like-minded individuals with whom they can collaborate — regardless of their physical locations. Through the use of this product, students who are enrolled in online courses do not miss out on the benefits of group work and peer discussion.


## 1.3. Definitions
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-citn{background-color:#FFF;color:#333;text-align:left;vertical-align:top}
.tg .tg-dgl5{background-color:#FFF;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">DESK</span></th>
    <th class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Desk is a virtual space wherein students may collaborate. Each Desk is temporary; it only exists as long as the Desk is in use. After everyone leaves the Desk, it is removed from memory. Each Desk has an admin who can set a limit to the number of members and can add signifiers such as language, age category, and other factors.</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">FRIEND</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Any two Users can become Friends if one sends a Friend Request and the other accepts it. When two Users are Friends, they can send private chats directly to one another.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">GROUP</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Group is a collection of two or more users who have connected through StudySpace either by Invitation or a User Match. All members of a Group automatically have access to a Chat upon joining.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">GROUP NAME</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Group Name is the name of a Group. The Group Name is set by a member of the Group. The Group Name must be unique so that other Users can easily discover the Group via Search.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">INITIAL AUDIENCE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">This product is for David Brown, who is the initial User and the project client.</span></td>
  </tr>
  <tr>
    <td class="tg-1wig"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">INTERESTS</span></td>
    <td class="tg-0lax" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Interests refer to the parameters that the user has chosen and the ranking of these parameters. The choice and ranking of parameters are key to determining User Matches.</span><br><span style="font-weight:400;font-style:italic;text-decoration:none;color:#000;background-color:transparent">Example.</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">Alice has chosen the following parameters: Co-op, Friends, CP104, Programming and she has the following Interests:</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Co-op</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Friends</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. CP104</span><br><span style="font-weight:400;font-style:normal;text-decoration:none;color:#000;background-color:transparent">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. Programming</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">INVITATION</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">An Invitation is the opportunity for a User to join a Group. Any member of a Group can choose to send an Invitation to a User who isn’t already a member.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">PAGE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Page is where Posts are viewed. Each Group can have one or more Pages.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">POST</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Post is an object which can include photos and text. Posts are created by Users for all members of a Group to see. Users can make a Post about anything they wish, including: buying/selling textbooks, asking questions, looking for advice, etc. Users can also write a Response to a Post.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">PROFILE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Profile is a page with personal information about the user. The Profile also provides functionality such as managing group memberships and accessing chats.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">RESPONSE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Response is a text message which is linked to a Post.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">SEARCH</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Search is a function of the app where Users can search and discover Groups by Group Name or Users by Username.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">STUDYSPACE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">StudySpace refers to the web application created by the Team for the Initial Audience, David Brown.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">TARGET AUDIENCE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Students are the intended users of this product.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">USER</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A User is someone who uses the application, such as a Student.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">USER MATCH</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Users have the option to enter their Interests, such as various preferences, courses they are enrolled in, and their study habits. Users who are both members of the same group have the possibility of getting matched. The more common Interests, the more likely they are to be matched. When a User Match occurs, the matched users show up in each other’s list of user matches, found on the page of the group they were matched in.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">USERNAME</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">A Username is part of a User’s account information. A Username is the name by which a User is referred to on the app.</span></td>
  </tr>
  <tr>
    <td class="tg-dgl5"><span style="font-weight:700;font-style:normal;text-decoration:none;color:#000;background-color:transparent">UPVOTE/DOWNVOTE</span></td>
    <td class="tg-citn" colspan="8"><span style="font-weight:400;font-style:normal;text-decoration:none;color:#333;background-color:transparent">Users can express whether or not they like a post or agree with it by giving it an Upvote or Downvote. Upvoting is equivalent to “liking” the post, and Downvoting is the same as “disliking” the post.</span></td>
  </tr>
</tbody>
</table>

## 1.4. References
- _IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society, 1998_

## 1.5. Overview
The rest of this document contains details about the overall description and specific requirements of the project. Section 2 contains information about the product perspective, product functions, user characteristics, constraints, and dependencies. Section 3 discusses external interfaces, functions, logical database requirements, and software system attributes.

# 2. Overall Description

## 2.1. Product Perspective
StudySpace is an independent, self-contained web application. Core features are personalized profiles, groups, chats, and pages in each group. It is a web application with 2 components: user interfaces (frontend), and software interfaces (backend).

### 2.1.1. User Interfaces

#### 2.1.1.1. Landing Page (logged out)

![](landing_page.png)
![](2111.png)

#### 2.1.1.2. Sign Up View

![](signupview.png)
![](2112.png)


#### 2.1.1.3. Home Page (Logged In)

![](homepage_loggedin.png)
![](2113.png)


#### 2.1.1.4. Groups Home Page

![](groupshomepage.png)
![](2114.png)

#### 2.1.1.5. Desk View

![](deskview.png)
![](2115.png)

#### 2.1.1.6. Posts View

![](postsview.png)
![](2116.png)

#### 2.1.1.7. User Profile Page

![](userprofilepage.png)
![](2117.png)

#### 2.1.1.8. Profile Page (another user)

![](profilepage_anotheruser.png)
![](2118.png)

#### 2.1.1.9. User Match View

![](usermatchview.png)
![](2119.png)


## 2.2. Product Functions
Users can create their own group with a desired set of members or a specific topic. New groups may not share a name with existing groups. Users can create posts, comment on posts, chat, log in, and send friend requests to other users. 

##  2.3. Actors and Use Cases
![](actorsandusecases.png)

### 2.3.1. Administrator Functions

- **Create Moderator:** Involves selecting the “Create User” option and adding a username and password to the list of users with moderator rights to the website.
- **Delete Moderator:** Involves selecting the “Remove Moderator” option and entering the username of the moderator to be removed from the moderator list.
- **Delete User Profile:** Involves selecting the “Delete User” option and entering the username of the general user to be deleted.
- **Edit Home Page:** Involves selecting “Edit Page” and then select “Home Page” and change the text, photos, posts, and other content on the Home Page.

### 2.3.2. Moderator Functions

- **Report User:** Involves selecting the “Manage User” option and entering the username of the user to be reported.
- **Send Warning:** Involves selecting the “Manage User” option and entering the username of the user who needs to be sent a warning.
- **Remove User:** Involves selecting the “Manage Group” option and entering the name of the group from which a user needs to be removed. From there, select the user from the list of group members that needs to be removed from the group.
- **Delete Group Chat:** Involves selecting the “Manage Group” option and entering the name of the group from which the group chat needs to be deleted.

### 2.3.3. User Functions

- **Search**: Involves using the search bar to find groups, posts, and users.
- **Create Group**: Involves selecting the “Create” option and filling in the name of the new group and selecting moderators.
- **Join Group:** Involves searching for a group and selecting “join”, or accepting an invite to the group.
- **Create Post:** Involves navigating to a group page and selecting “create new post” and entering a title and body text.
- **Edit Post:** Involves selecting the post to be edited and selecting “edit”. Note: only the author of a post can edit it.
- **Delete Post:** Involves selecting the post to be edited and selecting “delete”. Note: only the author of a post can delete it.
- **View Post:** Navigate to the page where the post has been published.
- **Comment:** Navigate to the post, select the post, then select “comment”.
- **Create Profile:** If not already logged in, the user will be presented with the sign-up page where they can select “sign up” and from there they will create a new profile.
- **Edit Profile:** Involves selecting “Profile”, selecting “Edit Profile” and allows users to edit their username, password, educational institute, Interests, and other personal information.
- **Delete Profile:** Involves selecting “Profile”, selecting “Edit Profile”, and then selecting “Delete Profile”.
- **Send Invite:** Involves searching for a user from the group page, selecting their profile, and then selecting “Send Invite”. This will send the user an invitation to the group from which the invitation was sent.
- **View Recommended Users:** Involves navigating to a group’s main page. The list of recommended users based on membership in this group will appear on the right side of the screen.
- **Match with Recommended Users:** Involves selecting a user from a list of recommended users and then after getting redirected to their profile, selecting “Accept Match”.
- **Pass on Matching with Recommended User**: Involves selecting a user from a list of recommended users and then after getting redirected to their profile, selecting “Decline Match”.
- **Send Chat**: Involves navigating a chat box (direct message or group chats), entering a message, and selecting “Send”.
- **Add Friend:** Involves selecting a user account and selecting “Add Friend” to add that profile to the user's friend list.
- **Remove Friend:** Involves selecting a friend’s profile and selecting “Remove Friend” to remove that profile from the user's friend list.


## 2.4. User Characteristics
Post-secondary students are the intended users of this product. As such, it is assumed that the user has experience using a web browser and navigating websites. It is helpful — but not necessary — for the user to have experience with common social media applications, such as Reddit, Instagram, or Twitter. This experience should aid the user in learning how certain features of StudySpace work, such as chat, due to the similarities to other social media applications.

## 2.5. Constraints
A large number of users must be able to access the website at once. To ensure the website is reliable, smooth, and feels responsive to the user, chat logs should update within a second whenever a user sends a chat.

## 2.6. Assumptions and Dependencies
It is assumed that users have a functioning, web-capable computer (desktop or laptop) with a browser installed. Users are expected to have an internet connection for the entire duration of their session. StudySpace should be compatible with any desktop operating system.

# 3. Specific Requirements

## 3.1. Function Requirements

- **Creating, editing, deleting posts**
  - Once a user has created a post, they can edit or delete the post by accessing it via the group page where it is posted.
- **Searching**
  - Any additional spaces or misspelled words in the search bar must be understood. For example “CP31 7 Wilfred” must show the intended results of “Cp317 Wilfrid”.
  - Implemented by a Full-Text-Search in the relational database which is part of the backend.
- **User sign-in**
  - When users sign in, the email form must be in proper email format (eg; having “@” in their email address”). 
  - Passwords must contain at least 8 characters, one symbol, and one number.
  - Users stay logged in until they sign out. 

## 3.2. Logical Database Requirements

![](users.png)
![](friends.png)
![](groups.png)
![](posts.png)
![](responses.png)
![](user_groups.png)

## 3.3. Software System Attributes

### 3.3.1. Performance Requirements
The website must be quick and responsive to all screens above 320px to meet usability requirements. From the front-end perspective, content must load quickly and transitions between pages should be seamless. 95% of the transactions shall be processed in less than 1 second.

### 3.3.2. Security
Any access to the StudySpace backend needs to be verified to ensure that only authorized administrators/moderators have access. Authorization involves entering a valid username and password to an account with administrator privileges. When an administrator or moderator logs into the system, they are granted permissions to edit, create, and delete content.
	
###  3.3.3. Portability 
StudySpace must be accessible on any desktop device that is web-capable and has a browser. Therefore, StudySpace must be compatible with any operating system, including Windows, macOS, and Linux. The product must also be compatible with any browser, including Chrome, Firefox, Internet Explorer, Edge, and Safari.

# 4. Version History
<h3> Version 1.0 - 09/02/2021 </h3>

Initial Requirements document created

- Dayton Talarico
- Rohan Uddin
- Arvin Benipal
- Muhammad Hashir
- Mackenzie Van Zanden

<h3>Version 1.1 - 10/02/2021 </h3>

Document reformatted and expanded use case definitions 

- Dayton Talarico
- Janelle Tait

<h3>Version 1.2 - 11/02/2021</h3>

Adjusted document upon SQA suggestions

- Dayton Talarico
- Janelle Tait
- Rohan Uddin
- Arvin Benipal
- Muhammad Hashir

Thanks to SQA by

- Ann Baldonasa
- Arshdeep Sahi
- Shyam Dave
- David Rosien
- Matthew Francis
- Evan Surtel

<h3>Version 1.3 - 24/03/2021</h3>

Performed SQA on consistency with previous docs and grammar checks

- Ann Baldonasa

Removed mention of tutors as this will no longer be a part of the software

- Dayton Talarico

Added Interests definition and changed any previous mentioning of “user preferences” to “Interests”

- Janelle Tait
- Dayton Talarico

Updated section 3.2 to match the Design document

- Janelle Tait

<h3>Version 1.4 - 07/04/2021</h3>

Added Upvote/Downvote definition to be consistent with other documents

- Dayton Talarico

<h3>Version 1.5 - 10/04/2021</h3>

Updated Section 2.1.1 User Interfaces to match the Design document

- Dayton Talarico

Updated Section 2.3 Use Case Diagram based on David Brown’s suggestion to separate Create Moderator and Delete Moderator cases

- Dayton Talarico

Updated Section 3.1 to clarify password requirements

- Janelle Tait

Reformatted and converted to HTML

- Ann Baldonasa

