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
- Configure Roles <br>
- Configure Departments <br>
- Configure Agents (workers) <br>
- Configure Users (customers)
- Configure SLA <br>
- Configure Help Topics


<h2>Configuration Steps</h2>
<p>
- Log into osTicket as admin with credentials created in the previous repo. This will bring up the admin panel.
</p>
<p>
<img width="510" alt="Screenshot 2023-09-16 at 4 47 48 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/dba4e02b-d57b-45cb-81f4-c0013c00ce67"><br>
<img width="707" alt="Screenshot 2023-09-16 at 4 49 13 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/fe466dff-0a12-4565-a363-2e9978f957f3"> <br>
<img width="794" alt="Screenshot 2023-09-16 at 4 30 37 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/a0f10644-0d5d-4d51-8afa-71795f5a4ca0"> <br>
</p>
<p>
- Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a><br>
</p>
<p>
<img width="625" alt="Screenshot 2023-09-16 at 5 00 41 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/9cc391fb-678c-4c05-8955-3104923cc230"><br>
</p>
<p>
- Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html">Departments</a><br>
</p>
<p>
<img width="656" alt="Screenshot 2023-09-16 at 5 04 30 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/d2678638-e1fe-4511-a087-063b7e0a6153"><br>
</p>
<p>
- Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html">Teams</a><br>
- Add Level I Support & Level II Support <br>
</p>
<p>
<img width="633" alt="Screenshot 2023-09-16 at 5 08 36 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/ced861f1-c692-4de6-805e-050f7e9bba3d"><Br>
</p>
<p>
- Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html">Agents</a><br>
</p>
<p><img width="620" alt="Screenshot 2023-09-16 at 5 10 54 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/60dbda44-2784-48c4-95af-292d28421998"><br>
</p>
<p>
- Configure <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html">Users</a><br>
- Add Jane & John for practice
</p>
<p> <img width="610" alt="Screenshot 2023-09-16 at 5 12 24 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/718a500b-53b7-4325-887d-815d5fb554f0">
<br>
</p>
<p>
- Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html">SLA</a><br>
- Create Sev-A (1 hour, 24/7)<br>
- Create Sev-B (4 hour, 24/7) <br>
- Create Sev-C (8 hours, business hours)<br>
</p>
<p></p><img width="1609" alt="Screenshot 2023-09-16 at 5 14 16 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/be0f56cc-af71-4b4a-988e-5e03075c6d4c"><br>
<img width="737" alt="Screenshot 2023-09-16 at 5 18 03 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/86ec224b-426f-49fd-9ec7-0648a96bb20e"><br>
</p>
<p>
- Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html">Help Topics</a><br>
- Create help topics to simulate real-world work place issues such as: <br>
  - Business Critical Outage <br>
  - Personal Computer Issues <br>
  - Equipment Request <br>
  - Password Reset <br>
- These help topics will be used later when creating and addressing tickets.<br>
</p>
<p>
<img width="1578" alt="Screenshot 2023-09-16 at 5 20 49 PM" src="https://github.com/MariahTali/post-install-config/assets/76408932/650489d5-5201-454d-8eec-b3a575951d64">
<br>
</p>
