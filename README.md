# Story Pitch Management System
SPMS was created for Project 1 of Revature's training curriculum in Java with Automation.

## Project Description
SPMS is used by authors to sumbit pitches for story ideas and editors to review and approve/reject them.
First, a user must log into the application.
Editors can view and approve/reject pending story pitches/drafts on the View Submissions page.
When rejecting a submission, the editor must provide a reason for doing so.
Once a submission has met the requirements for approval, its status is changed to approved and a draft of the pitch is created.
If an editor would like to request more information from another editor, they can do so on the Requests page.
This page also displays an inbox of requests for them from other editors.
After submitting a pitch, users may view all of their submitted pitches.
This page shows the iformation, status, approvals, and editor's notes on all of their submissions.

## Technologies Used
* PostgreSQL
* Bootstrap
* Javalin
* Jasmine
* Hibernate
* Java
* JavaScript
* HTML
* CSS

## Features
* Login page
* My Submissions
    * Submit new pitches
    * View previous submissions
* View Submissions (Editors only)
    * View all pending submissions
    * Approve pending submissions
    * Reject pending submissions and provide the author with notes
* Request Manager (Editors only)
    * View request inbox
    * Send requests
* Profile Page
    * View your profile information
    * Change your profile information
To-do list:
* Additional draft functionality

## Getting Started
>$ git clone http://github.com/bhufnagel/SPMS
You will need to create your own PostgreSQL database (either locally or on AWS) and configure hibernate.cfg.xml file to the database.

## Usage
Run the Project1Javalin.java file (found in srs/main/java/com/revature/app) as a java application. Open your browser and go to localhost:8080.

## Contributors
* Brodie Hufnagel

## License
This project uses the following license: <MIT_LICENSE>.
