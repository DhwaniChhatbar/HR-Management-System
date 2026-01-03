# HR-Management-System
🚀 DayFlow – Human Resource Management System
Every workday, perfectly aligned.
#️⃣ About the Project

DayFlow is a fully functional, offline-capable Human Resource Management System (HRMS) developed as a hackathon-ready project. The system focuses on real-world HR workflows such as employee management, attendance tracking, leave approvals, salary viewing, and notifications.

The application uses a local SQLite database and implements complete backend logic with strict role-based access control. No mock data, demo logic, or cloud services are used.

#️⃣ Hackathon Objectives

Build a real and fully working HRMS

Avoid UI-only or simulated implementations

Enforce server-side authorization

Use SQLite for persistent local storage

Maintain a clean and professional UI

Keep the code simple, readable, and extensible

#️⃣ Team Members
Name	Role
Dhwani Chhatbar	Team Lead
Mahek Mungra
Drashti Gondha
Palak Kansagara
#️⃣ Mentor

Mentor Name: Akshat Trivedi
Role: Technical Guide

#️⃣ User Roles

Employee

HR Officer

Admin

All permissions and restrictions are enforced strictly at the backend level.

#️⃣ Authentication & Security

Secure user registration with:

Unique Employee ID

Full Name

Company Name

Unique Email

Password and Confirm Password

Role selection

Passwords are securely hashed

Input sanitization applied on all forms

New users are created with is_verified = false

Login is blocked until verified by Admin or HR

Same error message for invalid login attempts

No hardcoded credentials or dummy users

#️⃣ Employee Features

View personal profile details

Edit limited profile fields:

Address

Phone number

Avatar upload

Daily attendance check-in and check-out

Apply for leave and track leave status

View salary details (read-only)

Receive in-app notifications

Access strictly limited to own data only

#️⃣ Admin / HR Features

View and manage all employees

Verify newly registered user accounts

Edit complete employee profiles

View attendance records of all employees

Approve or reject leave requests with comments

Create and update salary records

Full system-wide access and control

#️⃣ Attendance Management

One check-in allowed per employee per day

Check-out allowed only after check-in

Attendance statuses include:

Present

Absent

Half-day

Leave

Past attendance records cannot be edited

Approved leave automatically updates attendance

#️⃣ Leave Management

Leave types supported:

Paid

Sick

Unpaid

Overlapping leave requests rejected at backend level

Leave statuses:

Pending

Approved

Rejected

Leave records cannot be modified after submission

Attendance records updated automatically after approval

#️⃣ Salary Management

Salary stored strictly in Indian Rupees (₹)

Salary values stored as integers

Employees can only view salary details

Admin and HR can create and update salary records

No payroll, tax, or deduction calculations

#️⃣ Notifications & Reports

In-app notifications stored in database

Notifications for leave decisions and profile updates

Attendance and leave summary reports

No email, SMS, or external services

#️⃣ Tech Stack

Frontend: HTML, CSS, Vanilla JavaScript

Backend: Node.js with Express

Database: SQLite

Authentication: Local session or JWT-based

File Storage: Local file system

#️⃣ Project Status

✔ Fully Implemented
✔ Offline Ready
✔ Secure & Role-Based
✔ Hackathon Friendly

#️⃣ Hashtags

#DayFlow #HRMS #HumanResourceManagement
#HackathonProject #NodeJS #ExpressJS
#SQLite #VanillaJavaScript #OfflineApplication
#RoleBasedAccess #TeamProject
