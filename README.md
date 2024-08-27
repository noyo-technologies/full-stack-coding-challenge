# Coding Challenge: Employee Enrollment Management Application

## Overview
Build a simple enrollment management application where users can create, update, delete, and view insurance enrollments for a group of employees.

**Group** - A group is a collection of individuals covered under a single insurance policy.  
**Employee** - An employee is defined as an individual who works for an employer and is eligible to participate in the employer's group insurance plan.  
**Enrollment** - The start and end dates where a particular plan covers an employee.

## Data Modeling
- A group must have a name, for example, "Noyo Corporation."
- Each employee must have a first and last name.
- Each employee must be a member of a group.
- Each group can offer 1 - 3 types of plans. Medical, Dental, or Vision
- Each employee can enroll in any of the plans.
- Each plan has a start and end date.

![Figure 2](/data.png)


## Requirements

### Front-End
**Stories**  
- As a Noyo admin, I want to create a group to add employees.
- As a Noyo admin, I want to create employees so I can enroll them in coverage
- As a Noyo admin, I want to update employee names to correct errors.
- As a Noyo admin, I want to delete employees in case I add one by mistake.
- As a Noyo admin, I want to delete enrollments if I accidentally add one.
- As a Noyo admin, I want to enroll an employee in Medical, Dental, or Vision coverage as offered by its group.
- As a Noyo admin, I want to see a list of all my groups.
- As a Noyo admin, I want to see an individual employee and their enrollments.

**Technical Requirements:**  
- React.js: Build the user interface using React.js.
- Next.js: Use Next.js to handle server-side rendering and routing.
- You can style and construct the UI however you see fit.

### Back-End

**API Routes:** Use Next.js API routes to create a RESTful API for managing all domain objects. Implement the CRUD operations (Create, Read, Update, Delete) for employees and enrollments.  
**Database:** Store data in a database (e.g., MongoDB, PostgreSQL, or a cloud solution like Firebase Firestore).  


**Technical Requirements:**

**TypeScript**: Use TypeScript for type safety.  
**Code Quality**: Write clean, maintainable code following SOLID principles and best practices. Include comments where necessary and ensure the code is well-structured and extensible (you will have to extend it in your onsite)

## Deliverables
- Zip up the application and email it to coding-challenge at noyo dot com.
- Deploy the application to a platform like Vercel, Netlify, or any cloud provider.


## Live Coding Extention
During your onsite, you will discuss and demo your take-home solution. As part of this, there will be a live coding extension where you will implement additional functionality.