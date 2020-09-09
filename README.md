# task-scheduler
A basic task scheduler with a web interface for logging in and creating a calendar with reminders

# Project description
We'll be making a website for users to make a calendar with scheduled tasks.
Users would log in and be able to add short descriptions for a task and what day and time they'd like to add it to.
Tasks can be checked/crossed off and each day can be viewed individually. The calendar can also be exported as a PDF to be printed.
Paid customers can opt into ad-free viewing and have the option to enable schedule reminders through email or SMS.

# Team
I'm looking for one or two others to join the team.

# SQL
Likely SQLite. A relational, table based database would let us store the information and join columns to get user data easily.

# No-SQL
Likely MongoDB. I'm thinking a column-oriented database but we'll have to explore our options.

# Business
This will be a two tiered business.
Free tier allows users to create an account, login, create a calendar, and export it as a pdf.
Paid tier would remove ads and add reminder functionality through email and/or SMS.

# Legal
I'm not sure but an LLC sounds like the most simple.

# Technical
As a basic outline, we would be creating a basic web frontend using Vue which would send requests to the backend database.
Database tables could include created users and their registered information, logged in users and their authentication tokens, and their calendar data. (these are three separate tables)
