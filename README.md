<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

![image](https://github.com/CopaceticWill/post-install-config/assets/137100082/d5dae9f3-5fc3-48dd-bf30-99a6d309497a)

</p>
<p>
In this image, I configured Roles, Departments, and Teams to begin our workflow. After creating these roles I updated Agents and Users to have the corresponding permissions on their profiles. 

</p>
<br />

<p>

![image](https://github.com/CopaceticWill/post-install-config/assets/137100082/e0503c99-b00c-431e-abe4-61bc5abdb696)

</p>
<p>
In this portion, I reviewed and configured the SLA expectation by using the tiers below:

  - SEV-1 (1 hour, 24/7)
  - SEV-2 (4 hours, 24/7)
  - SEV-3 (8 hours, business hours)
</p>
<br />

<p>

![image](https://github.com/CopaceticWill/post-install-config/assets/137100082/c72ed192-f452-48c3-b1cb-5867d5ede187)
  
</p>
<p>
Finally, I updated the Help topics to ensure we had a baseline to help users with FAQ. These topics are the following: 

  - Business Critical Outage
  - Password Reset
  - Personal Computer Issues

</p>
<br />
