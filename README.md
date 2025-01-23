<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

This document provides a step-by-step guide to creating and managing tickets within the osTicket system to demonstrate their lifecycle. Each scenario includes steps for creating tickets, observing their properties, setting their attributes, and working them to completion.

Admin/Analyst Login Page: [Admin Login](http://localhost/osTicket/scp/login.php)

End Users osTicket URL: [End Users Ticketing Page](http://localhost/osTicket)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Scenarios</h2>

<h3> Scenario 1: Entire Mobile/Online Banking System is Down</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: [http://localhost/osTicket](http://localhost/osTicket)
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: Entire Mobile/Online Banking System is Down
  - Details: Provide a brief description of the issue.

**As a Help Desk Agent (John)**
- Navigate to the Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- Log in as "john."
- Locate the newly created ticket and observe its properties:
  - Priority
  - Department
  - SLA
  - Assigned To
- Set the ticket properties as follows:
  - Priority: Sev-A (1 hour, 24/7)
  - Department: Online Banking Department
- Attempt to observe the ticket again as "john" and note whether you can view or change it.

**As a Help Desk Agent (Jane)**
- Log in as "jane."
- Work the ticket to completion.

<h3>Scenario 2: Accounting Department Needs Adobe Upgrade, Broken</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: http://localhost/osTicket
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: Accounting Department Needs Adobe Upgrade, Broken
  - Details: Provide a brief description of the issue.

**As a Help Desk Agent (John)**
- Navigate to the Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- Log in as "John."
- Locate the newly created ticket and observe its properties:
  - Priority
  - Department
  - SLA
  - Assigned To
- Set the ticket properties as follows:
  - Priority: Sev-B (4 hours, 24/7)
  - Department: Support
- Work the ticket to completion.

<h3>Scenario 3: CFO’s Laptop Will No Longer Turn On</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: http://localhost/osTicket
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: CFO’s Laptop Will No Longer Turn On
  - Details: Provide a brief description of the issue.

**As a Help Desk Agent (John)**
- Navigate to the Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- Log in as "John."
- Locate the newly created ticket and observe its properties:
  - Priority
  - Department
  - SLA
  - Assigned To
- Set the ticket properties as follows:
  - Priority: Sev-B (4 hours, 24/7)
  - Department: Support
- Work the ticket to completion.

<h2>Purpose of This Repository</h2>
This repository serves as a practical guide and example of the lifecycle of a ticket within the osTicket system. By following these steps, users can better understand ticket creation, assignment, and resolution workflows in a help desk environment.
