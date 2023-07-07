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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Permissions
- Create Agents
- Create Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<dl>
  <dt>Configure Roles</dt>
  <dd>
    <li>Admin Panel>Agents>Departments</li>
    <li>Click on "Create New Role" and name the role "Head Admin"</li>
    <li>Go to permissions and for this role give them access to do everything</li>
  </dd>
</dl>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<dl>
  <dt>Configure Departments</dt>
  <dd>
    <li>Admin Panel>Agents>Teams</li>
    <li>Click "Add New Department" and name the new department "Systems Administrator"</li>
  </dd>
</dl>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<dl>
  <dt>Configure Teams</dt>
  <dd>
    <li>Admin Panel>Agents>Teams</li>
    <li>Click "Create New Team" and create two teams. One called "Level I Support" and the other called "Level II Support" </li>
  </dd>
</dl>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<dl>
  <dt> Allow Anyone to Create Tickets</dt>
  <dd>
    <li>Admin Panel>Agents>User Settings</li>
    <li>Make sure the box that says "Require registration and login to create tickets" is NOT ticked</li>
  </dd>
</dl>
</p>
<br />

</p>
<p>
<dl>
  <dt>Configure Agents</dt>
  <dd>
    <li>Admin Panel>Agents>Add New</li>
    <li>Click "Add New Agent"</li>
    <li>Make a couple of Agents. For example "Lisa" and "Milhouse"</li>
    <li>On the "Access" tab you can add Lisa to a department and asign a role (System Admins/Head Admin)</li>
  </dd>
</dl>
</p>
<br />

</p>
<p>
<dl>
  <dt>Configute Users</dt>
  <dd>
    <li>Agent Panel>Users>Add New</li>
    <li>Click "Add New User" and add users such as Homer and Luan</li>
  </dd>
</dl>
</p>
<br />

</p>
<p>
<dl>
  <dt>Configure SLA</dt>
  <dd>
    <li>Admin Panel>Manage>SLA</li>
    <li>Select "Add New SLA Plan"</li>
    <li>Create three different SLA's with different timeframes based on its severity: SEV-A(1 hour,24/7), SEV-B (4 hours, 24/7), and SEV-C (8 hours, business days)</li>
  </dd>
</dl>
</p>
<br />

</p>
<p>
<dl>
  <dt>Configure Help Topics</dt>
  <dd>
    <li>Admin Panel>Manage>Help Topics</li>
    <li>Select "Add New Help Topic" and create the following topics:</li>
    <li>Business Critical Outage</li>
    <li>Personal Computer Issue</li>
    <li>Equipment Request</li>
    <li>Password Reset</li>
  </dd>
</dl>

You can configure the settings more or add more topics and users but this covers the basics and would be enough to function and practice using
</p>
<br />
