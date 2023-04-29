# Tickets-and-Ticket-Lifecycle
In this lab I will use osTicket to practice creating, prioritizing , and solving tickets.

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

<h2></h2>

- Ticket Lifecycle Stages
- Severity levels
- How End Users Create Tickets
- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Ticket Lifecycle Stages</h2>

<P>A ticket may go through six different stages in its lifecycle.
<P>
<img src="https://i.imgur.com/KiIui2q.png" 70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>Severity levels</h4>

<p>Sev-A (1 hour, 24/7) [entire mobile/online banking system is down] -> SysAdmins
Sev-B (4 hours, 24/7) [accounting department needs adobe upgrade, broken]
Sev-B/C (2 hours, business hours) [CFO’s laptop seems a bit slow]
<p>

<h4>How End Users Create Tickets</h4>

<p>Use the URL http://localhost/osTicket/ and paste it into your web browser
<p>

<p>I used the no password or login required which would allow any user to create tickets.
To create a new ticket:  Open a New Ticket
Enter your contact information, help topic, issue summary and select create ticket
<P>

<p>Creat a new ticket
<p>
<img src="https://i.imgur.com/aYh0W31.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/eyKxAk5.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/ZRqJKcN.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The "Business Critical Outage" ticket was created
<p>
<img src="https://i.imgur.com/MSNrHmM.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Create the tickets “Accounting department” and the “CFO” from the list above.
The Accounting department ticket
Create a new ticket
<p>
<img src="https://i.imgur.com/BOxGnrI.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/OuY1dv2.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/AS1rNR3.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The new ticket for Accounting was created/
<p>
<img src="https://i.imgur.com/3XCDhCk.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>


<p>The CFO ticket
Create a new ticket
<p>
<img src="https://i.imgur.com/B3xow15.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/HkolWkB.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/W5GLkAb.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>End Clients can check the status of their tickets by selecting the green check ticket status button.
Provide your email and ticket number
<p>
<img src="https://i.imgur.com/YFe43OC.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>


<h4>Intake</h4>

<p>An agent will logon to the osTicket portal as an admin to review the new tickets that were created.  The tickets will be assigned to other agents according to complexity and severity.
<p>
<p>Here are the three tickets that were created,
<p>
<img src="https://i.imgur.com/eJOECNL.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>I will examine each ticket and assign an SEV priority to each ticket.  All tickets are currently priority normal
Start with ticket #622392.  This looks like a critical system failure, this has a financial impact on the business. This ticket will have top priority.

Ticket #860628 will be next on the priority list because the entire accounting department is affected.

Ticket #280913 will have the lowest priority.
<p>

<p>Ticket 622392 priority was changed to Emergency and has an SEV-A designation
<p>
<img src="https://i.imgur.com/5ZMaVba.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Here is example of how to document a change in a tickets priroty
<p>
<img src=""70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Ticket 860628 will be upgraded to High priority and SEV-B
<p>
<img src="https://i.imgur.com/2qFzomE.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/p8idLgA.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>


<p>Ticket 280913 will have a normal priority and an SEV-B 
<p>
<img src="https://i.imgur.com/sliSR76.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/YPJDXjU.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Here are the updated tickets
<p>
<img src="https://i.imgur.com/jjXIKqM.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>Working the Issue</h2>
  
<p>Agents can use the ticket ID to track the progress of a ticket from start to finish. Communicate with the user and provide them with timely updates. If a ticket status is escalated or assigned to a higher represensitive, let the customer know about the change and what new timelines they can expect. 
  
<h4>Resolution</h2>
  
<p>When the tickets have been resolved
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>For ticket 622392, I change the status to resolved, not closed.  The ticket will remain in this state until verification that all commence traffic is flowing.
You can see that the ticket has been removed from the list.
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The remaining ticket will be resolved in the similar manner, starting with ticket 860628.  Ticket 280913 will have the a lowwer priorty.
<p>


