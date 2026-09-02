# Smart Leave Approval System

## Project Overview

This project automates the employee leave approval process using **Google Forms, Google Sheets, Zapier, Airtable, and Gmail**.

Employees submit leave requests through a Google Form. The responses are stored in Google Sheets and automatically transferred to Airtable using Zapier. Managers can review the requests and update the leave status as **Approved** or **Rejected**. Based on the manager's decision, Zapier automatically sends the appropriate email notification to the employee.

The automation reduces manual work, improves the leave approval process, and keeps leave records organized.

## Workflow

Employee
↓
Google Form
↓
Google Sheets
↓
Zapier (Zap 1)
↓
Airtable
↓
Manager Updates Status
↓
Zapier (Zap 2)
↓
Approved / Rejected
↓
Gmail Notification

## Node Structure

### Zap 1: Leave Request Creation

Google Forms
↓
Google Sheets
↓
Zapier
↓
Airtable (Create Leave Record)

### Zap 2: Leave Approval Notification

Airtable
↓
Manager Updates Status
↓
Zapier
↓
Status Check
↓
Approved → Approval Email
Rejected → Rejection Email

## Tools & Technologies

* **Google Forms** – Collect leave requests from employees
* **Google Sheets** – Store form responses
* **Zapier** – Automate the workflow between applications
* **Airtable** – Store and manage leave requests and approval status
* **Gmail** – Send automated approval and rejection emails

## Key Features

* Automated leave request collection
* Automatic transfer of leave data to Airtable
* Manager-based approval and rejection
* Automated email notifications
* Centralized leave request tracking
* Reduced manual administrative work
* Two-Zap workflow architecture



