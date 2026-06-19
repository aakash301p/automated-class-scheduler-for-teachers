# automated-class-scheduler-for-teachers

# Smart Class Scheduler

An automated class scheduling and notification system built using **n8n, Google Sheets, Gmail**.

## Overview

Smart Class Scheduler helps teachers schedule classes through a conversational interface instead of filling lengthy forms.

The system automatically:

* Collects class details
* Schedules classes
* Generates class sessions
* Stores records in Google Sheets
* Sends confirmation notifications
* Sends automated reminders before class starts

---

## Features

### Teacher Scheduling Flow

* Select Board
* Select Class
* Select Section
* Select Subject
* Select Date
* Select Start Time
* Select End Time

### Automation

* Automatic class scheduling
* Automated confirmation notifications
* Automated reminder notifications
* Google Sheets integration
* Teacher information management
* Conversation-based data collection

### Notifications

* Schedule confirmation
* Class details summary
* Reminder notifications before class starts

---

## System Architecture

Teacher
↓
Telegram / WhatsApp Bot
↓
n8n Workflow Engine
↓
Google Sheets Database
↓
Notification Service
↓
Teacher

---

## Workflow

### Class Scheduling

1. Teacher starts conversation
2. System asks for Board
3. System asks for Class
4. System asks for Section
5. System asks for Subject
6. System asks for Date and Time
7. Class information is stored
8. Confirmation notification is sent

### Reminder Workflow

1. Scheduled workflow runs every few minutes
2. Upcoming classes are checked
3. Reminder notifications are sent
4. Reminder status is updated

---

## Tech Stack

* n8n
* Google Sheets
* Gmail
* Telegram Bot API
* JavaScript
* Workflow Automation

---



## Author

Aakash kumar

Workflow Automation | Python | FastAPI | PostgreSQL | n8n | Machine Learning
