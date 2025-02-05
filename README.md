<h1>osTicket - Post Installation Configuration</h1>

- <b>This tutorial outlines the post-installation of the open-source help desk ticketing system osTicket</b>

<h2>Environments and Technologies Used</h2>

- <b>Microsoft Azure</b> 
- <b>Virtual Machine</b>
- <b>Remote Desktop</b>
- <b>Internet Information Services (IIS)</b>

<h2>Operating Systems</h2>

- <b>Windows 10</b>

<h2>Post-Install Configuration Objectives</h2>

- <b>Configure Roles</b>
- <b>Configure Departments</b>
- <b>Configure Teams</b>
- <b>Configure Agents</b>
- <b>Configure Users</b>
- <b>Configure SLA</b>

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/2d8729c7-deaf-4e26-8540-1f239b434773)
- <b>Login to osTicket and select Admin Panel</b>

![image](https://github.com/user-attachments/assets/3eca7aa8-34eb-4755-8864-7a1b2c67bb74)
- <b>Select Agents>Roles</b>
- <b>Add New Role</b>

![image](https://github.com/user-attachments/assets/513a1eb4-5be5-4abe-b960-766faa92ec86)
- <b>Name: Supreme Admin</b>
- <b>Select Permissions</b>

![image](https://github.com/user-attachments/assets/7a3d2e8e-e271-42b2-8574-a388496fd6ea)
![image](https://github.com/user-attachments/assets/899d2ff0-9c2b-4f8a-b550-99b1e68e8e66)
![image](https://github.com/user-attachments/assets/600cb817-886a-4349-8183-94355752368b)

- <b>Check all the boxes for Tickets, Tasks, and Knowledgebase</b>
- <b>Select Add Role</b>

![image](https://github.com/user-attachments/assets/0c14b3c7-b370-49d8-ae82-79cc40c02350)
- <b>Supreme Admin Created</b>

![image](https://github.com/user-attachments/assets/62cbf793-ac7a-4548-b665-61081dd673ec)
- <b>Select Departments and Add New Department</b>
- <b>Name: System Administrators</b>
- <b>Click access and create department</b>

![image](https://github.com/user-attachments/assets/04c7fd43-81a2-4cc5-a403-25bf0510a80d)
- <b>Systems Administratiors Created</b>

![image](https://github.com/user-attachments/assets/28286a99-47e9-4b6f-bd06-6865e00a529e)
- <b>Select Teams and add new team</b>
- <b>Name: Level II Support</b>
- <b>Click Members and create team</b>

![image](https://github.com/user-attachments/assets/147d7ff4-6dc6-4d6a-9a3a-d7fa20a438bd)
- <b>Level II Support Created</b>

![image](https://github.com/user-attachments/assets/cd103f2d-4143-4b36-94f1-0ab4580562f1)
- <b>Select Settings>Users</b>
- <b>Select require registration and save changes</b>

![image](https://github.com/user-attachments/assets/81b7ec87-513f-4d19-bbda-1fb14ca70092)
- <b>Click agents and add new agent</b>
- <b>Name: Jane Doe</b>
- <b>Email: jane.doe@helpdesk.com</b>
- <b>Username: jane_doe</b>
- <b>Click set password</b>

![image](https://github.com/user-attachments/assets/e0707956-366b-4042-bbe6-f0a6c461216f)
- <b>Click access</b>
- <b>Set department to support: limited access</b>
- <b>Click create</b>

![image](https://github.com/user-attachments/assets/7cdc5694-045b-424f-9001-bf9ecb45658f)
- <b>Jane Doe agent created</b>

![image](https://github.com/user-attachments/assets/d6b32ed9-4f5c-42c5-bc1c-6f981feb059b)
- <b>Click agents and add another agent</b>
- <b>Name: John Doe</b>
- <b>Email: john.doe@helpdesk.com</b>
- <b>Username: john</b>
- <b>Click set password</b>

![image](https://github.com/user-attachments/assets/e1560b6d-c774-438b-b341-4faa24ca1927)
- <b>Set maintenance: Supreme Admin</b>
- <b>Click create</b>

![image](https://github.com/user-attachments/assets/99cf74f0-9d11-45fb-8238-59d8210cc42f)
- <b>John Doe agent created</b>

![image](https://github.com/user-attachments/assets/418e13b4-4194-406d-a15c-489450eee9be)
- <b>Select agent panel>users>add user</b>
- <b>Email address: karen@osticket.com</b>
- <b>Full Name: karen_karen</b>
- <b>Click add user</b>

![image](https://github.com/user-attachments/assets/b13a4ef4-ec74-4c94-8ab7-70f01b7ba452)
- <b>Karen user created</b>

![image](https://github.com/user-attachments/assets/63c26b19-25db-46db-962b-1c9fcd6f7ec7)
- <b>Select agent panel>users>add user</b>
- <b>Email address: ken@osticket.com</b>
- <b>Full Name: ken_ken</b>
- <b>Click add user</b>
- <b>Ken user created</b>

![image](https://github.com/user-attachments/assets/f3c2fde5-eb1f-4a3b-82cb-92ec25926ebd)
- <b>Select Admin Panel>Manage>SLA>Add New SLA Plan</b>
- <b>Name: Sev-A</b>
- <b>Grace Period: 1</b>
- <b>Schedule: 24/7</b>
- <b>Click add plan</b>

![image](https://github.com/user-attachments/assets/9b687eae-7a28-46f2-82ac-44ba73f17df6)
- <b>Add a second SLA Plan</b>
- <b>Name: Sev-B</b>
- <b>Grace Period: 4</b>
- <b>Schedule: 24/7</b>
- <b>Click add plan</b>

![image](https://github.com/user-attachments/assets/526e1834-7ce2-4dc8-97b4-d5607a15325d)
- <b>Add a third SLA Plan</b>
- <b>Name: Sev-C</b>
- <b>Grace Period: 8</b>
- <b>Schedule: Monday - Friday: 8 AM - 5 PM with U.S. Holidays</b>
- <b>Click add plan</b>

![image](https://github.com/user-attachments/assets/626b58cf-1cb5-4fbb-a293-4caf2699cc19)
- <b>SLA Plans created</b>

![image](https://github.com/user-attachments/assets/055411b4-ba73-40dd-8f05-31efa1768d84)
- <b>Click Help Topics and add a new help topic</b>
- <b>Topic: Business Critical Outage</b>
- <<b>Click add topic</b>

![image](https://github.com/user-attachments/assets/1d1f1e0a-dfcc-43be-b940-e98b723eb4d5)
- <b>Create 3 more help topics: Personal Computer Issues, Equipment Request, and Password Reset</b>
