<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial is a continuation of my other osTicket tutorials and outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

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

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.gyazo.com/603980ac1c9a3653cb0324efc95af721.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The End User onTicket URL is : [Here](http://localhost/osTicket/)
For this example, Karen's customers are reporting a 404 error when browsing online banking. 
</p>
<br />

<p>
<img src="https://i.gyazo.com/ab37560b9c2a400a3eeb7b50921d7b1a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents will be able to see live tickets in the agent panel. Queue managers will assign priority tickets to the appropriate agents as well as assigning proper SLAs. Currently all tickets default to normal priority. 

</p>
<br />

<p>
<img src="https://i.gyazo.com/8da34f3bfd261f5d356ef0f5504175f1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this example we need to set the priority level of the ticket. The priority will need to be set to Emergency since we are dealing with an issue that can effect an entire portion of the business. We have changed the SLA plan and assigned the ticket to a top level technician. In some ticketing system customers can set their own SLA plans.


</p>
<br />

<p>
<img src="https://i.gyazo.com/1b0c329f8f87148569d7b90538170739.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Agents can leave replies or updates below, once resolved an agent can change the ticket status to resolved and the ticket will be closed. 

</p>
<br />
