# Task_Scheduler

# 1.Introduction
## 1.1 Purpose
The purpose of this document is to provide a detailed description of the Task Scheduler, a desktop application aimed at efficiently managing tasks for both administrators and users. This document outlines the functionalities, features, and requirements of the system.
## 1.2 Scope
The Task Scheduler is designed to assist users and administrators in managing tasks effectively. It provides features such as adding, updating, deleting, and searching tasks. The application includes separate landing pages for administrators and users, each with unique functionalities.
## 1.3 Definitions, Acronyms, and Abbreviations
SRS: Software Requirements Specification
Admin: Administrator
User: End user of the application 

# 2.System Overview
## 2.1 System Description
The Task Scheduler is a desktop application that allows administrators and users to manage tasks efficiently. It includes authentication features, separate landing pages for administrators and users, and functionalities such as task manipulation and record management.
## 2.2 System Features
User Authentication: Users and administrators must log in to access the system.
Landing Pages: Separate landing pages for administrators and users.
Admin Dashboard: Admins can view, add, search, and modify user records.
User Dashboard: Users can view records but cannot modify them.
Task Management: Add, update, delete, and search tasks.

# 3.Functional Requirements
## 3.1 User Authentication
The system shall provide a login page for both administrators and users.
Users and administrators must provide valid credentials to access the system.
## 3.2 Landing Pages
The application shall have two landing pages: one for administrators and one for users.
The landing page for administrators shall include links to the admin dashboard.
The landing page for users shall provide access to the user dashboard.
## 3.3 Admin Dashboard
Admins shall be able to view user records.
Admins shall be able to add new user records.
Admins shall be able to search for user records based on specific criteria.
Admins shall be able to modify existing user records.
## 3.4 User Dashboard
Users shall be able to view existing records.
Users shall not be able to modify records.
## 3.5 Task Management
Administrators shall be able to add tasks.
Administrators shall be able to update tasks.
Administrators shall be able to delete tasks.
Administrators shall be able to search for tasks based on specific criteria.

# 4.Non-Functional Requirements
## 4.1 Usability
The user interface shall be intuitive and easy to navigate.
Response time for task operations shall be within acceptable limits.
## 4.2 Security
User credentials shall be securely stored.
Access to functionalities shall be role-based.
## 4.3 Reliability
The system shall be available for use during standard working hours.
Data integrity shall be maintained during all operations.
# 5.System Interface
## 5.1 User Interfaces
The application shall have visually appealing and user-friendly interfaces for the login page, admin dashboard, user dashboard, and task management.
## 5.2 Hardware Interfaces
The system shall be compatible with standard desktop hardware.
## 5.3 Software Interfaces
The application shall be compatible with common desktop operating systems such as Windows, MacOS, and Linux.

# 6.Problem Statement 

In today's workplaces, effectively managing tasks is crucial for keeping things running smoothly. However, many existing desktop task scheduling apps fall short in delivering a complete set of features and personalized functions, leading to less-than-optimal user experiences. The lack of role-based access control and clear interfaces for administrators and users makes these issues even more challenging.

# Main Concerns:
## 6.1 Insufficient Task Management Tools:
Current desktop apps lack important features for easy task handling, like adding, updating, deleting, and searching for tasks.
## 6.2 User Interface and Access Challenges:
The absence of dedicated pages for administrators and users creates confusion and makes the user experience less straightforward.
Existing systems don't offer role-based access control, putting the security and integrity of user data at risk.
## 6.3 Authentication and Authorization Issues:
The authentication processes in current task scheduling apps might not be strong enough, potentially leading to security vulnerabilities.
A lack of authorization controls allows users to modify records freely, posing risks to the integrity of the data.
## 6.4 Limited Administrative Control:
Administrators currently lack a central hub for handling tasks comprehensively, modifying user records, and efficiently searching through records.

# 7.Problem Solution: Task Scheduler Desktop Application
The Task Scheduler desktop application aims to tackle these challenges head-on by offering a robust, user-friendly solution for task management. With essential features like adding, updating, deleting, and searching for tasks, the application ensures a smooth and easy-to-understand experience. The addition of separate pages for administrators and users, along with role-based access control, boosts security and tailors interactions to each user's needs. The goal of the proposed application is to establish a unified and efficient platform for both administrators and users to manage tasks on their desktops.

# 8.Conclusions 
This Software Requirements Specification outlines the features and functionalities of the Task Scheduler desktop application. It serves as a guide for the development team to ensure that the final product meets the specified requirements and satisfies the needs of both administrators and users.

# link:https://youtu.be/W5l5rJ3OrhE
