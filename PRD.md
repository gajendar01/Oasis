PRODUCT REQUIREMENTS DOCUMENT (PRD)

Project Name

Oasis – College Event & Activity Management Platform

Tagline :- "One Platform for Every Campus Event"

1. Product Vision

What are we building?

Oasis is a centralized web platform that enables students, organizers, and college administrators to manage the complete lifecycle of college events and activities through a single system.
The platform replaces fragmented tools such as WhatsApp groups, Google Forms, Excel sheets, and emails with a unified event management solution.

Why are we building it?

Most colleges currently use multiple disconnected tools for event management.

This creates challenges such as:

- Manual registration management
- Attendance tracking issues
- Communication gaps
- Certificate distribution difficulties
- Lack of centralized records
- Limited event monitoring

Oasis solves these problems by providing a centralized platform for event creation, registration, attendance management, and certificate distribution.

Product Goals :

- Simplify event management
- Reduce manual administrative work
- Improve event visibility
- Automate attendance tracking
- Centralize event records
- Improve student participation

2. Target Users

Primary Users :

Students

- Discover events
- Register for events
- Track participation
- Download certificates

Event Organizers

- Create and manage events
- Manage participants
- Track attendance
- Upload certificates

Club Coordinators

- Organize club activities
- Manage club events
- Monitor participation

Secondary Users :

College Administration

- Monitor platform activity
- View statistics
- Manage users

3. Problem Statement

Colleges regularly organize:

- Workshops
- Hackathons
- Competitions
- Seminars
- Cultural Events
- Club Activities

Current management relies on:

- WhatsApp Groups
- Google Forms
- Excel Sheets
- Emails
- Google Drive

These tools operate independently and fail to provide a complete event management workflow.

4. Core Modules

Student Module

Features:

- Registration and Login
- Browse Events
- View Event Details
- Register for Events
- View Registered Events
- Download Certificates

Organizer Module

Features:

- Create Events
- Edit Events
- Delete Events
- View Participants
- Upload Certificates

Admin Module

Features:

- Manage Users
- View Events
- View Platform Statistics
- Monitor Activity

5. User Workflow

Student Journey :

Login

↓

Browse Events

↓

View Event Details

↓

Register

↓

Receive Confirmation

↓

Attend Event

↓

Download Certificate


Organizer Journey :

Login

↓

Create Event

↓

Publish Event

↓

Manage Registrations

↓

Attendance Tracking

↓

Upload Certificates

↓

View Participation Data

6. Website Structure

Landing Page

Hero Section

- Project Name
- Tagline
- Explore Events Button
- Create Event Button

About Section

- Problem Statement
- Platform Overview
- Benefits

Features Section

- Event Discovery
- Event Registration
- Attendance
- Certificate Distribution
- Centralized Dashboard

How It Works Section

Discover Event

→ Register

→ Attend

→ Receive Certificate

Contact Section

- Contact Form

Footer

7. Functional Requirements

Authentication

Users can:

- Register
- Login
- Logout

Role-Based Access:

- Student
- Organizer
- Admin

Event Management

Organizers can:

- Create Events
- Edit Events
- Delete Events
- Set Event Details
- Manage Registrations

Event Fields

- Title
- Description
- Date
- Time
- Venue
- Category
- Registration Deadline

Registration System

Students can:

- Register for Events
- View Registered Events

System should:

- Prevent Duplicate Registrations
- Store Participant Records

Attendance Management

Organizers can:

- Activate Attendance For An Event
- Set Attendance Availability Time Window
- View Attendance Records

Students can:

- Access Attendance Button When Activated
- Mark Attendance During Active Window

System should:

- Mark Attendance Automatically
- Store Attendance Records Securely
- Prevent Duplicate Attendance Entries
- Disable Attendance Access After Time Expiry

Certificate Management

Organizers can:

- Upload Certificates

Students can:

- Download Certificates

System should:

- Associate Certificates With Registered Participants

Dashboard

Student Dashboard

- Registered Events
- Event History
- Certificates

Organizer Dashboard

- Created Events
- Participant Lists
- Attendance Records

Admin Dashboard

- Total Users
- Total Events
- Platform Statistics

8. Non-Functional Requirements

Performance

- Fast Page Loading
- Optimized API Requests
- Responsive Dashboards

Security

- JWT Authentication
- Password Hashing
- Protected Routes
- Role-Based Authorization

Responsiveness

- Mobile Devices
- Tablets
- Desktop Screens

9. Technical Requirements

Frontend

- React.js
- Tailwind CSS

Backend

- Node.js
- Express.js

Database

- MongoDB

Authentication

- JWT

Certificate Storage

- Cloudinary or Local Storage

10. Business Model

Business Model Overview

Oasis follows a B2B (Business-to-Institution) SaaS model targeting colleges, universities, and educational institutions.

Revenue Streams

Institutional Subscriptions

Premium features:

- Advanced Analytics Dashboard
- QR-Based Attendance
- Certificate Automation
- Custom Branding
- Enhanced Administrative Controls

White Label Solutions:

Institutions can deploy a customized version of Oasis using their own branding, domain, and event portal.

Event Sponsorship Partnerships:

Companies can sponsor campus events through the platform. Oasis may earn commission fees by facilitating sponsorship opportunities.

Certificate Verification Services:

Digitally issued certificates can be verified through Oasis using verification links or QR codes.

Go-To-Market Strategy

Phase 1

- Free MVP rollout
- Product validation
- User feedback collection

Phase 2

- Premium institutional plans
- Custom deployment services

Phase 3

- Sponsorship partnerships
- Value-added services

11. MVP Scope

The MVP will include only:

- User Authentication
- Role-Based Access
- Event Creation
- Event Listing
- Event Registration
- Participant Management
- Certificate Upload
- Certificate Download
- Basic Dashboards

Features outside MVP:

- AI Recommendations
- Student Portfolio
- Placement Integration
- Sponsorship Management
- Inter-College Networking
- Advanced Analytics

12. Success Metrics

The MVP will be considered successful if:

- Organizers can create events
- Students can register successfully
- Attendance is recorded
- Certificates can be uploaded and downloaded
- Event workflow operates digitally without manual intervention

13. Development Constraints

Team Size:

- 4 Members

Development Duration:

- 6–7 Days

Development Approach:

- AI-Assisted Rapid MVP Development

Objective:

Deliver a fully functional and deployable MVP demonstrating centralized college event management.

14. Future Scope

Future versions may include:

- AI-Based Event Recommendations
- Student Achievement Portfolio
- QR Attendance
- Internship & Placement Integration
- Inter-College Event Network
- Mobile Application
- Advanced Analytics

15. Expected Outcome

Oasis will provide colleges with a centralized platform for managing events, registrations, attendance, and certificates.

The MVP will reduce manual work, improve event organization, and create a streamlined experience for students, organizers, faculty coordinators, and administrators.