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

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/BDp1UjJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The ticket lifecycle begins when a user submits a support request. This can happen through the web portal, by sending an email, or via an API integration. Once created, the ticket enters the system with an Open status. osTicket can automatically route tickets to the appropriate department or team using help topics, filters, or SLA plans. Staff can also manually assign the ticket to a specific agent for handling.


</p>
<br />

<p>
<img src="https://i.imgur.com/FbRuaaO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once assigned, the agent begins working on the issue, responding to the user and adding internal notes as needed. The ticket may switch between statuses like Open and Answered, depending on whether the next action is expected from the agent or the user. This back-and-forth process can repeat several times until the issue is fully understood and addressed. osTicket helps keep all communication logged and organized within the ticket thread.


</p>
<br />

<p>
<img src="https://i.imgur.com/9cS7wBe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When the issue is resolved, the agent sends a final response and closes the ticket. Tickets can be closed manually or automatically after a certain period of inactivity. Once closed, the ticket becomes read-only but remains stored for reporting, auditing, or reference. Optional features like customer satisfaction surveys or SLA tracking can be triggered at this stage to evaluate support performance and ensure service quality.


</p>
<br />
