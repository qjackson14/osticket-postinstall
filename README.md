<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=TVGglFS-yq8)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- osTicket
- Create SIM Environment
- SIM Lifecycle of tickets

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Azure
</p>
<br />

<p>
<img width="718" alt="roles" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/513d18c9-faef-4364-8bcc-80e3efd0476c">
</p>
<p>
Create Supreme Admin Role -> Give all permissions
</p>
<br />

<p>
<img width="718" alt="dept" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/43562f67-9fda-4b24-982b-4bdb2a46e68f">
</p>
<p>
Click Departments -> Add New Department -> Create System Admins
</p>
<br />

<p>
<img width="717" alt="teams" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/35757d27-0fbf-4def-925e-39874d4ee70b">
</p>
<p>
Click Teams -> Add New Team -> Create Level II Support -> Add Members
</p>
<br />

<p>
<img width="719" alt="user settings" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/8eae8406-79a3-4d49-847f-36c74d009d23">
</p>
<p>
Click Settings -> Users -> Make sure user settings look like picture above
</p>
<br />

<p><img width="721" alt="agents" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/d841d74b-f9fd-4b4c-98ab-8d6f3d913f95">
</p>
<p>
Click Agents -> Add New Agent -> Create as many agents as wanted & setup passwords (Password1) -> Assign Roles & Teams
</p>
<br />

<p>
<img width="482" alt="new user" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/8199d270-1727-4ae5-8dc3-db407fae1070">
</p>
<p>
CLick Agent Panel -> Users -> Add Users -> Create as many users as wanted
</p>
<br />

<p>
<img width="719" alt="SLAs" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/00e9fa5a-5573-4a9d-a31b-524702427380">
</p>
<p>
Click Manage -> SLAs -> Create New SLA -> SEV-A/SEV-B/SEV-C
</p>
<br />

<p>
<img width="715" alt="help topics" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/5cdd2902-d6a6-4a20-bb8b-183d78c3fd33">
</p>
<p>
Click Manage -> Help Topics -> Create new Help Topic -> Create as many Help topics as wanted
</p>
<br />

<p>
<img width="625" alt="ticket" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/17d19db9-7230-44ac-8087-20987f13fca5">
</p>
<p>
Open Support System link -> Open new ticket ->
</p>
<br />

<p>
<img width="712" alt="delegate ticket before" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/1a1191f2-c679-4b96-bebc-d8c4fa0867d2"><img width="715" alt="delegate ticket after" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/7daa3bbf-3ddf-4fe4-ba06-dfbd1df5620f">
</p>
<p>
View tickets that were just made -> Delegate tickets as you see fit (play role of System Admin)
</p>
<br />

<p>
<img width="708" alt="close out ticket" src="https://github.com/qjackson14/osticket-postinstall/assets/156969011/ff1ef518-ce77-46ab-8b46-b1c6d809230a">
</p>
<p>
Simulate handling of ticket/Corroborate with customer let them know ticket has been taken care of
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

