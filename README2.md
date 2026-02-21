# Project Guide


## Problem 4: Personalized Follow-Up Generator**
Sales reps waste time writing generic follow-ups. 
Generate personalized email/SMS/LinkedIn options they can edit and send quickly.

**Challenge Question**:

How can you generate contextual follow-ups fast enough that reps prefer it to writing
from scratch?

**Expected Outcomes**:
1. Lead profile + 2+ message templates (email, SMS)
2. Highlighted personalization slots + edit UI
3. Send simulation with confirmation


## Project Overview
This project is a locally runnable AI-powered Follow-Up Automation Manager 
designed for sales professionals.

Instead of building a full frontend dashboard initially, the system runs 
entirely inside n8n, which acts as both:
- Workflow engine
- Temporary user interface

Users simply:
1. Install n8n locally
2. Import the provided workflow JSON
3. Configure credentials
4. Start generating follow-ups


## Techstack
Javascript

n8n



## Project Requirements
npm

nodejs (v20.19 to v24.x)


## Project Setup
**Install n8n**: Run npm install -g n8n

**Start n8n**: Run n8n start

Now all you need to do is upload the required workflows and start using the project!

Use setup_db.json to setup the database for the first time

Use add_user.json to add users to the database

To use View_Edit_Users.json goto http://localhost:5678/webhook-test/customers.
Here you can edit database information easily. Use CTRL+F to search for emails/text