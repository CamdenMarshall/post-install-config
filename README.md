<h1>osTicket - Post-Install Configuration</h1>
This is a post-install configuration setup after the osTicket ticketing system is installed and functioning.

<h2>Materials Used</h2>

-  Microsoft Azure (Virtual Machines/Computers/Network)
-  Remote Desktop
-  Internet Information Services (IIS)
-  Windows 10 OS (Operating System)
-  osTicket

<h2>Post-Install Configuration Objectives</h2>

-  Setup a complete control role
-  Configure departments
-  Determine team setups Example:(Level 1 or Level 2)
-  Ensure anyone can create tickets
-  Setup helpdesk Agents
-  Configure Users within the system
-  Determine SLA
-  Configure Help Topics

<h2>Create a Head Role</h2>
Start off creating a role that has full access and permissions

In the Admin Panel click the "Agents" tab and then select "Roles"
![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/a408918a-2f39-4ad1-8dbc-05dd7bd12bcb)

From here click "Create New Role" and create a name and set it to have full permissions

This will include all boxes under "Tickets, Tasks, and Knowledgebase"

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/3636b163-f89a-483c-be37-27267d9dc2c9)
![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/c9344307-6cf8-4739-abc3-c04fea0c797c)
![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/fcdfadca-c1e0-4862-befb-618c4dab77e8)

Once all the boxes are checked click "Add Role"



<h2>Configure Departments</h2>
Create a new department with default settings

Under the Agents tab click on "Departments" and then select "Add New Department"

Creating a new default department will look like this

Name the new department as you require and then click "Create Department" at the bottom of the page

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/a9999b69-632a-4369-969e-10ca09e2a1f1)


<h2>Creating Teams</h2>
Create a team that will allow for the consolidation of experienced members into a group to help with issues

Under the Agents tab click on "Teams" and then select "Add New Team"

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/4f5e78ca-30c2-4226-b574-2cb602c8d59a)

- Name the Team as required and add the appropiate members on the tab labeled Members

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/eaf12be5-6264-4525-9f1c-d76e417f0310)

- Then hit "Create Team"

<h2>Ticket Creation Standards</h2>
Certain configurations can allow for tickets to be made without registration in the system or make users regsiter to be able to create tickets

Click on "Settings" in the top tabs and then select "Users" in the subtab

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/6d6146db-bf4b-4768-b73b-deca8afaadce)


Under Authentication Settings check the checkbox of "Require registration and login to create tickets" and finish by selecting "Save Changes" at the bottom of the page

<h2>Setting up Helpdesk Agents</h2>
Creating the agents to handle the tickets coming into the system and assign them into departments and roles

Click on "Agents" in the top tabs and then select "Agents" in the subtab

Click "Add New Agent" and create them as needed

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/ffe97e1c-e5e8-491a-864e-8c1d29ee9bfb)

- Set the Passwords as required for Example:

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/34e5e5ed-eef3-4c15-ae09-be9e315cb514)

- Once passwords are set click on the "Access" Tab and set the Agent's Deparment and Role as required

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/29a48933-d26e-4298-a9ed-b7628b186540)

- It is possible to assign the Agents to their proper team in the system by clicking "Teams" tab and assigning them correctly

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/058c8592-d115-486d-b9d8-74b1fe05ef52)


- Once complete click "Create"

<h2>Configuring Users</h2>
Create users to view in the system

To do this switch out of the Admin Panel up at the top right and enter into the Agent Panel

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/537fbc91-ec65-4969-a3bf-8ca9f9b49cef)

- This indicates that the user is in the Agent Panel

- Once in the Agent Panel go to the "Users" tab and click "Add User"

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/42e00e7a-8b97-481d-a7fc-fe91b25fc003)


- Fill out the User box as required to enter users and then click "Add User"

<h2>Service Level Agreements (SLA)</h2>
Creating and configuring the SLAs that are to be used in osTicket

Enter into the Admin Panel once more and navigate to the "Manage" tab an click "SLA"

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/5fa20d37-a64e-40e5-8d8b-541aa88240e6)

- Click on "Add New SLA Plan" and create the following SLA plans

-  Severity-A
![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/7096ed3c-3f46-43f5-97f5-73b94e95b8cf)

-  Severity-B
![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/c8d3be2e-229e-4a98-8461-a0a827d3b6fc)

-  Severity-C
![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/2521d267-becc-4b2c-8e79-6c28345a42a3)

- The SLA plans can be configured as needed

<h2>Configure Help Topics</h2>
Creating Help Topics that will allow users to streamline their issues and allow for the helpdesk to assist them quicker

Under the "Manage" tab click on "Help Topics" and create the following:

Example Help Topics to create
-  Business Critical Outage
-  Personal Computer Issues
-  Equipment Request
-  Password Reset

![image](https://github.com/CamdenMarshall/post-install-config/assets/153537343/a9ceefad-2d22-4ca3-b8fa-0a4e84e931ac)

- Follow this setup till all Help Topics have been created as required

<h2>Post Install Configuration Completed</h2>
