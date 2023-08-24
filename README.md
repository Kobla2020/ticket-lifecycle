<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Creating Tickets as Guest
- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

![Screenshot 2023-08-24 124321](https://github.com/Kobla2020/ticket-lifecycle/assets/127445078/36ce1f2b-2be3-4f43-8ec1-4fda0386095c)

</p>
<p>
We will be working osTicket as both the "users" and the "agents". Access osTicket on the user sign in page to create a ticket and after you click on "Open a new Ticket", you type in the user information that you made up (the email and the users name). After filling in the user credentials, you decide on a help topic. Remember we made a few help topics to choose from: "Business Critical Outage", "Equipment Request", "Password Reset", and "Personal Computer Issues". After picking one of those help topics, type in the summary of the issue then explain the issue in more detail so the agent knows exactly how to deal with/ fix the issue. Try creating a ticket for each of the help topics using your two users.
</p>
<br />

![Screenshot 2023-03-16 041130](https://github.com/Kobla2020/ticket-lifecycle/assets/127445078/e14d2d5f-c3d1-4493-9dfe-4b3f7d09723e)
</p>
<p>
After creating the tickets, sign in to your agent that has administrative control and observe the tickets you made as your users. After obseving them, click on one to open it up and you will see the ticket in its entirety.
</p>
<br />

![Screenshot 2023-03-16 044132](https://github.com/Kobla2020/ticket-lifecycle/assets/127445078/e8a04c37-d122-450f-9532-a258c08be9f4)
</p>
<p>
Notice how we changed the priority to "low", who the ticket is assigned to and the SLA plan. Being an administrator like Justin is, you are able to change how servere the issue is in your opinion as well as who to assign the ticket to. I even wrote a response to Ken as Justin in the space at the bottom basically telling him that my coworker Sarah will handle the problem as soon as possible. In the ticket on the right hand side, I labelled it as an emergency and gave it a "SEV-A" SLA which means 1 hour max response time and it needs to be worked on 24-7. Notice how I also changed the department to "System Adminitrators" because this would not be a problem that the support team would be able to handle alone. I also assigned this ticket to myself as Justin. 
</p>
<br />

<p>
<img src="https://i.imgur.com/u0NxlSr.png"  height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we sign in as your agent Sarah and work the tickets. When you initially sign on as Sarah, you should see the two tickets that were assigned to you via the system administrator which in my case, is Justin. Since Sarah is not a system adminitrator, she should not be able to change any of the options like the Priority, who the ticket is assigned to, SLA, etc. You can write a reply as Sarah saying whatever you need to say but you can not label the ticket as "closed" or "resolved" as Sarah.
</p>
<br />

![Screenshot 2023-03-16 052525](https://github.com/Kobla2020/ticket-lifecycle/assets/127445078/1bb5a5ac-05f0-4542-a60e-b934b0d727db)

</p>
<p>
After signing back in to our system administrator, take a look at the tickets. If you click on one of the tickets that you handed off to sarah, you can see that she wrote a response and successfully fixed the users' issue so as the administrator you can write off the ticket as "resolved" and close the ticket. Similarly you can close the resloved ticket that you assigned to yourself as the system administrator(Notice how the ticket says "Marked Overdue" this is because I assigned the SLA SEV-A to this ticket and took more than 1 hour to resolve this issue). Once every Ticket is resolved you can go into your "Tickets" tab and then inside of the "Closed" option should be all the tickets that you resolved. 
