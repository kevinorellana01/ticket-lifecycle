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

<h2>Before you Start</h2>

Disable/Delete Maintenance Department so tickets don't end up there.
To do this:
  - Navigate to Admin Panel -> Agents -> Departments.
  - Click on Maintenance and delete
<img width="697" alt="Screenshot 2025-01-23 at 12 47 17 PM" src="https://github.com/user-attachments/assets/d3fe9911-a79f-485c-a811-9638988602fe" />


<h2>Scenarios</h2>

<h3> Scenario 1: Entire Mobile/Online Banking System is Down</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: [http://localhost/osTicket](http://localhost/osTicket)
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: Entire Mobile/Online Banking System is Down
  - Details: Provide a brief description of the issue.
 
<img width="554" alt="Screenshot 2025-01-23 at 12 43 13 PM" src="https://github.com/user-attachments/assets/5bb136eb-0c51-460b-8c90-ce253227ae62" />


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

<img width="699" alt="Screenshot 2025-01-23 at 12 50 13 PM" src="https://github.com/user-attachments/assets/cc07d927-c0cf-4c44-9dc1-ca2318a48668" />
<img width="721" alt="Screenshot 2025-01-23 at 12 50 57 PM" src="https://github.com/user-attachments/assets/1b5a7f6d-38d2-4c29-82f0-cae9cef8165b" />
<img width="617" alt="Screenshot 2025-01-23 at 12 51 13 PM" src="https://github.com/user-attachments/assets/caa286da-b752-416c-b7ec-d3cf605d9560" />
<img width="645" alt="Screenshot 2025-01-23 at 12 51 58 PM" src="https://github.com/user-attachments/assets/01c5d815-749c-4148-8529-8d096664442a" />

**As a Help Desk Agent (Jane)**
- Log in as "jane."
- Work the ticket to completion.

<img width="506" alt="Screenshot 2025-01-23 at 12 52 58 PM" src="https://github.com/user-attachments/assets/762b038c-28d6-4208-b24c-01e28742543a" />
<img width="560" alt="Screenshot 2025-01-23 at 12 53 28 PM" src="https://github.com/user-attachments/assets/666e54e5-251e-48e4-ab9d-1f510544fb7f" />
<img width="683" alt="Screenshot 2025-01-23 at 12 53 48 PM" src="https://github.com/user-attachments/assets/b825da0b-185e-4ac1-8ef0-3044327ca86f" />
<img width="715" alt="Screenshot 2025-01-23 at 12 54 29 PM" src="https://github.com/user-attachments/assets/bf1fd582-d1ba-478d-b42c-e6786ab1b769" />
<img width="694" alt="Screenshot 2025-01-23 at 12 54 50 PM" src="https://github.com/user-attachments/assets/cf3944a6-d5cb-436f-858b-d33165b21d82" />
<img width="516" alt="Screenshot 2025-01-23 at 12 55 29 PM" src="https://github.com/user-attachments/assets/da9fb803-4894-4497-a18b-8bf861033ef9" />

<h3>Scenario 2: Accounting Department Needs Adobe Upgrade, Broken</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: http://localhost/osTicket
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: Accounting Department Needs Adobe Upgrade, Broken
  - Details: Provide a brief description of the issue.

<img width="586" alt="Screenshot 2025-01-23 at 12 56 22 PM" src="https://github.com/user-attachments/assets/7fc5f595-e71d-40e2-8619-5ff58528e3c7" />


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

<img width="731" alt="Screenshot 2025-01-23 at 12 56 52 PM" src="https://github.com/user-attachments/assets/e995e00a-25e7-4eb8-941b-74408b006a41" />
<img width="594" alt="Screenshot 2025-01-23 at 12 57 10 PM" src="https://github.com/user-attachments/assets/8a5e8ba1-be18-410d-b2bf-fb75cfc6d68d" />
<img width="517" alt="Screenshot 2025-01-23 at 12 57 34 PM" src="https://github.com/user-attachments/assets/950aa431-a83a-4688-9fb1-2acfb8fecfa7" />
<img width="668" alt="Screenshot 2025-01-23 at 12 57 53 PM" src="https://github.com/user-attachments/assets/8645e6ec-7bc5-4c2e-b013-35c46c29b7be" />
<img width="659" alt="Screenshot 2025-01-23 at 12 58 10 PM" src="https://github.com/user-attachments/assets/22438fc0-c427-4262-ab4c-2d2788d6bf12" />
<img width="502" alt="Screenshot 2025-01-23 at 12 58 44 PM" src="https://github.com/user-attachments/assets/dc2f93e5-b092-47e5-b581-89429feff721" />

<h3>Scenario 3: CFO’s Laptop Will No Longer Turn On</h3>

**As an End-User**
- Navigate to the End Users osTicket URL: http://localhost/osTicket
- Log in as an end-user.
- Create a new ticket with the following details:
  - Subject: CFO’s Laptop Will No Longer Turn On
  - Details: Provide a brief description of the issue.

<img width="608" alt="Screenshot 2025-01-23 at 12 59 14 PM" src="https://github.com/user-attachments/assets/83f8ebdb-9ddd-4974-bb61-5c2f4ee22e09" />

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

<img width="687" alt="Screenshot 2025-01-23 at 12 59 51 PM" src="https://github.com/user-attachments/assets/a852b748-90c1-4e34-b160-92d4f08c8f39" />
<img width="671" alt="Screenshot 2025-01-23 at 1 00 15 PM" src="https://github.com/user-attachments/assets/0d9f1fb3-dde0-424d-9a31-05e10ee44599" />
<img width="549" alt="Screenshot 2025-01-23 at 1 00 34 PM" src="https://github.com/user-attachments/assets/cc0c62c9-9643-441d-8783-607d14291194" />
<img width="684" alt="Screenshot 2025-01-23 at 1 00 57 PM" src="https://github.com/user-attachments/assets/10ac4f58-82c4-4d72-adc6-d5193358128f" />
<img width="513" alt="Screenshot 2025-01-23 at 1 01 21 PM" src="https://github.com/user-attachments/assets/8204ce0e-db7e-4b70-a625-01950ef3de5c" />

<h2>Purpose of This Repository</h2>
This repository serves as a practical guide and example of the lifecycle of a ticket within the osTicket system. By following these steps, users can better understand ticket creation, assignment, and resolution workflows in a help desk environment.
