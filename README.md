<img width="410" height="309" alt="image" src="https://github.com/user-attachments/assets/45fb5012-ebe6-47a6-8e7d-5e47a396ba7e" />


<h1>Ticketing System</h1>
A ticketing system is a software platform designed to manage and track service requests using records called tickets. These requests can include changes, incidents or problems that users are experiencing. They allow IT teams to resolve issues in a strcutured format by avoiding duplication, tracking ownership and sorting by serverity. The most common ticketing systems seen today are tools like ServiceNow, Jira or Zendesk.
<h2>Description</h2>
In this lab, we will be simulating a real-world IT support environment using Spiceworks Help Desk. The goal is to configure, customize, and operate a functional ticketing system that mirrors enterprise-level workflows. The lab emphasizes hands-on experience with user management, ticket lifecycle stages, and service request handling.
<br />

<h2>Technologies Used</h2>

- <b>VirtualBox</b> 
- <b>Windows 11</b>
- <b>Spiceworks</b>

<h2>Lab walk-through:</h2>

Spiceworks Set-up

1. Log on to Windows VM > Open Web Browser > Search for "Spiceworks" and click first link > Create a free account with email.
 <br/>
<img width="1024" height="771" alt="image" src="https://github.com/user-attachments/assets/6b7998cc-9e64-4590-a733-027922d23a66" />
<br />
<br />

2. Once signed in with your new account, at the top of the main menu click on "IT tools" > Cloud Help Desk. You will brought to another page to set up your ticketing system.
 <br/>
<img width="1022" height="769" alt="image" src="https://github.com/user-attachments/assets/d90c9a0e-dbea-4b0f-af9a-d8acf8659ebd" />
 <br/>
<br />

 3. Fill out the necessary information and once finsished you will have access to the system.
 <br/>
<img width="1022" height="769" alt="image" src="https://github.com/user-attachments/assets/438321df-bf8a-4d26-a5bb-ce538925904e" />
<img width="1918" height="1012" alt="image" src="https://github.com/user-attachments/assets/9140a298-6224-4605-b987-ee6bc19ac722" />
 <br/>
<br />

Ticket Creation

First, we will demonstrate ticket creation. The goal is to understand how tickets are created and categorized. For this ticket, we will simluate a user creating a ticket because they got locked out of thier account.

1. On main menu, click "New Ticket". A new window  will pop up asking us to fill it in with information.
 <br/>
<img width="653" height="752" alt="image" src="https://github.com/user-attachments/assets/7da64ed8-4047-463d-b82b-65c14c0f9340" />
 <br/>
<br />

2. Fill in the details about the issue. The more details the better. The user will put their information in the contact box. For the summary, give an overview of the issue and also put the computer name if possible to make it easier for the tech. In the description, exaplin the issue and everything you have done so far. Also, list all the programs, apps or hardware involved. You can also add a time when you are available to speak and where they can find you. For the priority level, it depends on the user by how they feel the issue should be priroitized. Fill in the category(e.g hardware, software, network) based on the issue. Lastly, you can add an picture to give more information. Click create.
 <br/>
<img width="600" height="731" alt="image" src="https://github.com/user-attachments/assets/a04840a7-6445-46a8-b75b-4b84804a2529" />
 <br/>
<br />

3. The ticket will populate in the ticketing queue will all the other tickets.
 <br/>
<img width="1599" height="740" alt="image" src="https://github.com/user-attachments/assets/a2b654ad-99f1-422a-9773-28627ced4c55" />
 <br/>
<br />

Resolving a Ticket and Documentation

Now, we will demonstrate how properly resolve a ticket and close it. In this task, we will document steps for resolution with the user, update the ticket notes, and close the ticket. We will use previous ticket created.

1. As a tech, you will see all the tickets in the ticketing queue. We will solve the ticket dealing with the user with a locked account. Click on ticket.
 <br/>
<img width="1600" height="876" alt="image" src="https://github.com/user-attachments/assets/57304423-88bf-44a4-b0ee-b1ab37fd199d" />
 <br/>
<br />

2. In the ticket chat, the tech will respond to the user with the root issue they found and the steps they took to fix it. They must explain it in a way that is clear and easy to understand. If you want to add more details about the issue that you would like only your team to see, you can change "public response" to "internal note" in the bottom left corner. These notes can be used for reference if a similar issues occurs in the future. Always verify with user that the issue has been resolved.
 <br/>
<img width="1913" height="820" alt="image" src="https://github.com/user-attachments/assets/bad807f6-d4b1-4491-8264-cc0ce01a7ad1" />
 <br/>
<br />

3. If the user responds back that the issue has been fixed, the ticket can now be closed.
 <br/>
<img width="1913" height="874" alt="image" src="https://github.com/user-attachments/assets/2ebf205e-0944-49d0-81ed-f102c27a7c59" />
 <br/>
<br />

4. To close the ticket, your have to click the "close" button on the right-hand side of the screen. Once closed, the ticket will be removed from the ticketing queue.
 <br/>
<img width="1534" height="616" alt="image" src="https://github.com/user-attachments/assets/27575e14-6582-47ba-a49c-fde4a9acd711" />
 <br/>
<br />

5. If you want to see closed tickets, you can filter your tickets from "open" to "closed".
 <br/>
<img width="1660" height="604" alt="image" src="https://github.com/user-attachments/assets/843f7c19-0cad-4ff1-ba15-2829007909a2" />
 <br/>
<br />

Escalation Process

Lastly, we will demonstrate the process of escalation. You may encounter an issue you can't resolve on your level because of limited access so you must escalate the issue to a different team or a higher team. 

1. For this scenario, users are experiencing wi-fi connectivity issues in their floor and they create a ticket in the queue.
 <br/>
<img width="602" height="640" alt="image" src="https://github.com/user-attachments/assets/dba6883d-4e99-4079-9815-5ec73905ed5a" />
 <br/>
<br />

2. As a level 1 tech, you go through all your troubleshooting steps to find the issue. You find that multiple users are not able to connect to the internet and it may be a network infrastructure issue. This requires higher permissions to be able to fix.
 <br/>
<img width="1526" height="726" alt="image" src="https://github.com/user-attachments/assets/cfe6ac8b-c057-4e00-9841-fa6b008f7ee1" />
 <br/>
<br />

3. To escalate to issue, you change the assignment of the ticket to a memeber of the proper team. In this sceanrio, it would be the network team. You would do this by navigating to the ride side and chossing the memeber under "Assignee". After, you would write a message in the ticket chat to the user and team member you are escalating the ticket.
 <br/>
<img width="1539" height="486" alt="image" src="https://github.com/user-attachments/assets/c84603c3-b318-410f-80b2-69254d719af1" />
 <br/>
<br />

