# Research-Collaboration-Network

## Overview

**Research-Connect** is a web-based platform designed to connect researchers, collaborators, institutions and academic resource providers in one centralized system. The platform supports research project management, collaboration requests, dataset sharing, funding opportunities, grant applications, lab equipment booking, academic resource discovery, AI-based collaborator matching and real-time communication.

The goal of this project is to simplify research collaboration by providing a structured digital environment where users can manage projects, find suitable collaborators, access academic resources, apply for funding and track research-related activities efficiently.

## Live Links

* **Vercel:** https://research-collaboration-network-lqf3.vercel.app/home
* **Render:** https://research-collaboration-network-1.onrender.com/home

## Features

1. Users can create, edit, delete, and view research projects with details such as title, abstract, research field, and status (ongoing/completed).

2. Users can send collaboration requests to other researchers for specific projects. The recipient can accept or reject the request.

3. Users can upload research datasets with descriptions, category tags, and download access control.

4. Users can create and manage research funding opportunities including grant title, funding amount, deadline and eligibility criteria.

5. Users can update project milestones and progress percentage. The system shows a timeline view of project progress.

6. Users can submit structured feedback on projects (review comments + rating scale).

7. Users can search researchers by: interest, skills. Implemented AI chatbot.

8. The system provides a centralized directory of research resources including journal databases, institutional access services (e.g., OpenAthens), plagiarism checkers, reference managers and academic tools. Users can search, bookmark resources, and rate their usefulness.

9. Researchers can list lab equipment for renting with availability schedule and booking request system. Equipment owners can approve/reject booking requests and track usage history.

10. Users can book equipment by paying through secure online transactions. The system integrates a Payment Gateway API (e.g.,SSLCommerz) to process payments, store transaction history, and automatically update user access permissions based on subscription status.

11. Online chat system with researchers and collaborators.

12. Users can add research interests and skill tags. The system suggests potential collaborators based on similarity using OpenAI API for intelligent matching.

13. Users can view upcoming academic conferences and add events to their Google Calendar.

14. Users receive automated notifications and can track all past submissions in a dashboard.

15. The system allows researchers to submit grant applications online, including proposal documents and structured forms with project title, abstract, requested funding and research field. It implements a multi-stage workflow: Submitted → Under Review → Approved/Rejected.

16. Users receive automated reminders for grant deadlines. (API:Email API)


## Tech Stack

### Frontend

* React.js
* Tailwind CSS / CSS
* Axios
* React Router

### Backend

* Node.js
* Express.js
* MongoDB
* REST API

### APIs and Integrations

* OpenAI API for AI-based collaborator matching
* SSLCommerz Payment Gateway API for online payments
* Google Calendar API for conference event scheduling
* Email API for automated grant deadline reminders

