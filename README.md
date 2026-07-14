# Content Planner

A lightweight internal content management application built with Next.js and TypeScript to streamline marketing content production.

This project was created to explore workflow-driven application design, CRUD operations, and dashboard development by modelling a real content production pipeline used by internal marketing teams.

Unlike traditional project management platforms, this application intentionally focuses on a single shared workspace where team members collaborate on content creation, assign ownership, update progress, and move tasks through predefined production stages.

Rather than trying to become a full-scale project management system, the application focuses on solving one business problem exceptionally well: managing the lifecycle of marketing content.

## Live Demo

https://team-task-calendar.onrender.com/

## Screenshots

### Dashboard

(Add screenshot)

### Task Management

(Add screenshot)

### Workflow Board

(Add screenshot)

### Mobile View

(Add screenshot)

## Features

* Create new content tasks
* Edit existing tasks
* Delete tasks
* Assign internal team members
* Track production progress
* Organize content by workflow stage
* Filter tasks by status
* Responsive dashboard
* Modal-based task management
* Lightweight monolithic architecture

## Workflow

Tasks progress through a structured content production pipeline:

```text
Idea
   ↓
Draft
   ↓
Ready
   ↓
Posted
```

Content can also be categorized by type, including:

* Reels
* Carousels

This workflow was designed to mirror a real marketing team's content production process, making it easier to visualize work in progress and identify bottlenecks.

## Technologies Used

* Next.js
* React
* TypeScript
* Tailwind CSS
* Render

## Architecture Highlights

This application was intentionally designed as a lightweight internal business tool.

Instead of supporting multiple organizations, user accounts, or complex permission systems, it operates as a shared workspace protected by a single application password. Team members are selected from predefined internal users, keeping the application simple, efficient, and aligned with its intended use case.

This design decision demonstrates an important software engineering principle: choosing an architecture that fits the business problem instead of introducing unnecessary complexity.

## What I Learned

During this project I gained experience with:

* Building internal business applications
* Designing workflow-oriented user interfaces
* Creating reusable CRUD operations
* Managing application state
* Building dashboard-style interfaces
* Designing reusable modal components
* Structuring applications around business processes
* Organizing data using workflow-driven models
* Building focused software that solves a specific operational problem

## Challenges

Some of the challenges encountered during development included:

* Designing an intuitive content production workflow
* Keeping the interface simple while supporting multiple production stages
* Managing form interactions efficiently
* Building reusable modal components
* Organizing application state across multiple views
* Creating a dashboard that remained lightweight and easy to use
* Designing around a real business workflow instead of generic task management

These challenges reinforced the importance of balancing usability, maintainability, and business requirements during application development.

## Installation

```bash
git clone https://github.com/axce-j/team-task-tracker.git

cd team-task-tracker

npm install

npm run dev
```

## Looking Back

This project marked an important shift in my development journey from building general-purpose applications to designing software around real business operations.

Rather than adding features simply for complexity, I focused on creating a lightweight internal tool that solved a clearly defined operational need for managing marketing content production.

Since completing this project, I have continued building larger systems involving:

* Full-stack business applications
* Workflow automation
* Authentication and authorization systems
* AI-powered platforms
* Database architecture
* Cloud deployment
* Scalable application design
* Product and platform engineering

It reinforced one of the most valuable lessons in software engineering: the best architecture is not always the most complex one, but the one that best fits the problem being solved.

I have intentionally preserved this project as part of my software engineering journey and as a record of my growth in designing business-focused applications.

## Future Improvements

Potential future enhancements include:

* Calendar-based content scheduling
* Drag-and-drop workflow management
* File and media attachments
* Content approval workflows
* Team notifications
* Analytics dashboard
* Role-based permissions
* Search and advanced filtering
* Activity history
* Integration with social media publishing platforms

## Author

**Obinna Jachike Ezeani**

Software Engineer | Product Builder | Co-Founder

GitHub: https://github.com/axce

LinkedIn: https://www.linkedin.com/in/obinna-jachike-ezeani-a072b9284/
