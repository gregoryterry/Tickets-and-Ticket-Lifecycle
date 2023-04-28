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

<h2>Ticket Lifecycle Stages</h2>

- Severity levels
- How End Users Create Tickets
- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<P>A ticket may go through six different stages in its lifecycle.
<P>
<img src="" 70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>Severity levels</h4>


<p>Sev-A (1 hour, 24/7) [entire mobile/online banking system is down] -> SysAdmins
Sev-B (4 hours, 24/7) [accounting department needs adobe upgrade, broken]
Sev-B/C (2 hours, business hours) [CFO’s laptop seems a bit slow]
<p>

<h4>How End Users Create Tickets</h4>

<p>Use the URL http://localhost/osTicket/ and paste it into your web browser
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>I used the no password or login required which would allow any user to create tickets.
To create a new ticket:  Open a New Ticket
Enter your contact information, help topic, issue summary and select create ticket
<P>Creat a new ticket
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The "Business Critical Outage" ticket was created
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Create the other tickets “Accounting department” and the “CFO” from the list above.
The Accounting department ticket
Create a new ticket
<p>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The CFO ticket
Create a new ticket
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>For end users, when you create a new ticket you will get the screen that show that you have a new ticket.
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h2>Intake</h2>

<p>An agent will logon to the osTicket portal as an admin, to review the new tickets that were created.  The tickets will be assigned to other agents according to complexity and severity.
<p>
<p>Here are the three tickets that were created,
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>I will examine each ticket and assign an SEV priority to each ticket.  All tickets are currently priority normal
Start with ticket #622392.  This looks like a critical system failure, this has a financial impact on the business. This ticket will have top priority.
Ticket #860628 will be next on the priority list because the entire accounting department is affected.
Ticket #280913 will have the lowest priority.
<p>

<p>Ticket 622392 priority was changed to Emergency and has an SEV-A designation
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Ticket 860628 will be upgraded to High priority and SEV-B
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Ticket 280913 will have a normal priority and an SEV-B 
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Here are the updated tickets
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>When the tickets have been resolved
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<h4>
<p>Change status to resolve, not closed.  The ticket will remain in this state until we verify that all commence traffic is flowing.
You can see that the ticket has been removed from the list.
<p>
<img src="" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>The remaining ticket will be resolved in the same manner, starting with ticket 860628.
<p>


