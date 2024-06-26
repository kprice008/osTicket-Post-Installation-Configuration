# osTicket-Post-Installation-Configuration
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
- Allow Anyone to Create Tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src=https://private-user-images.githubusercontent.com/170815251/333830051-12f08740-50c9-4ebc-ac35-f01784d9d67e.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY2Njk0MjgsIm5iZiI6MTcxNjY2OTEyOCwicGF0aCI6Ii8xNzA4MTUyNTEvMzMzODMwMDUxLTEyZjA4NzQwLTUwYzktNGViYy1hYzM1LWYwMTc4NGQ5ZDY3ZS5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyNVQyMDMyMDhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lNWYzNDY1M2RiNzI0MmQwNzY4NjhiODA3ZDhmZDhjNjE3OTIwMGJjZDJlMDE0MDA4YzczODRmY2JkN2ExNTE3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.__Ubv6u-wvoYpVL3cipZBqDJ_vIA5rfFtvLFHRPK4S8/>
</p>
<p>
Once you log in to osTicket, choose the Admin Panel option. Cick on the Agents tab, followed by Roles. Create a new Role under Supreme Admin. Under the Permissions tab, check all boxes for Tickets, Tasks, and Knowledgebases.
</p>
<br />

<p>
<img src=https://private-user-images.githubusercontent.com/170815251/333830049-84b2283c-9cf0-4b8f-8c1c-728c154b3f90.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY2Njk2MzQsIm5iZiI6MTcxNjY2OTMzNCwicGF0aCI6Ii8xNzA4MTUyNTEvMzMzODMwMDQ5LTg0YjIyODNjLTljZjAtNGI4Zi04YzFjLTcyOGMxNTRiM2Y5MC5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyNVQyMDM1MzRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yYzBmNDQ0YWMyN2E1YjY2M2QxYzgxNmJiNzRlMjg2NTVlMjZhYWUyOTM2OWI5M2NjZmJiZmJmOTNkYmZhMjZkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.oHsh1OsKlxQWhYnPDioMdtiSFB9Y0K18jq12v2IM-PE/>
</p>
<p>
Return to the Agents tab and choose Departments. Click the "Add a New Department" buton. Name the new department "System Administrators" and create the new Department.
</p>
<br />

<p>
<img src=https://private-user-images.githubusercontent.com/170815251/333830053-69331609-4997-4e48-8086-9d5d12f41105.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY2Njk2MzQsIm5iZiI6MTcxNjY2OTMzNCwicGF0aCI6Ii8xNzA4MTUyNTEvMzMzODMwMDUzLTY5MzMxNjA5LTQ5OTctNGU0OC04MDg2LTlkNWQxMmY0MTEwNS5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyNVQyMDM1MzRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kMTIyNTgzY2NjYTM5M2M2ZTliMDMwN2EyYjU4Zjk4NjU3MTdmZTZlNmUzNjQ3MDNiZTZlNjU0ZDczMzk0NWNhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.-ZzHL7S4wb7tt8ghICa84RV2lvwk1rXehgsZhWeojZQ/>
</p>
<p>
Return to the Agents tab and choose Teams. Click the "Add New Team" button. Name the new Team "Level II Support". Under the Admin Panel, go to Settings, Users, then Authentication Settings. Check the "Require Registration and Login" box then save changes.
</p>
<br />

<p>
<img src=https://private-user-images.githubusercontent.com/170815251/333830048-c38940f6-07a2-4c05-bbe2-07dea94fcad1.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY2Njk2MzQsIm5iZiI6MTcxNjY2OTMzNCwicGF0aCI6Ii8xNzA4MTUyNTEvMzMzODMwMDQ4LWMzODk0MGY2LTA3YTItNGMwNS1iYmUyLTA3ZGVhOTRmY2FkMS5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyNVQyMDM1MzRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jMzk5ODY4MDg2ZWUxNzc1NTg3YjJhM2NkZmRkOTZmZjMyYTIwMTMzMjY5ZjAxMjk0OGM2ZmNiY2Y2NThmZjFkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Rby85C4hS2ks5bYwOopUae9S1F6Fv-kaG0VgEsShlYo/>
</p>
<p>
Under the Agents tab, choose Add New Agents and create both "John Doe" and "Jane Doe". Set passwords for both new Agents.
</p>
<br />

<p>
<img src=https://private-user-images.githubusercontent.com/170815251/333830047-40ddb538-3de3-4ebb-a3c6-30845a0e2b79.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY2NzAwNDUsIm5iZiI6MTcxNjY2OTc0NSwicGF0aCI6Ii8xNzA4MTUyNTEvMzMzODMwMDQ3LTQwZGRiNTM4LTNkZTMtNGViYi1hM2M2LTMwODQ1YTBlMmI3OS5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyNVQyMDQyMjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wZWY5MDQxOWI0ZTg1YTZkYTUzNDBhMDIzY2IxNzJhOTY5MTliM2U3Mzk0MTA1NDNhMmJlZDY5NWQ5ZGMyMzQ4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.4uxMzMZ2YLEppBCYqAaSczGEnTYczblGwAvi8Lcp01c/>
</p>
<p>
Under the Agent Panel, choose Users tab and add both "Karen" and "Ken" Users. 
</p>
<br />

<p>
<img src=https://private-user-images.githubusercontent.com/170815251/333830055-9f2b3187-75dd-4097-b618-93f0795fd1be.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY2NzAwNDUsIm5iZiI6MTcxNjY2OTc0NSwicGF0aCI6Ii8xNzA4MTUyNTEvMzMzODMwMDU1LTlmMmIzMTg3LTc1ZGQtNDA5Ny1iNjE4LTkzZjA3OTVmZDFiZS5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyNVQyMDQyMjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jYzg3MjhiYzdmMzFiOGE2YWIzMjQ5N2M3MGZhODFmODg4MWZiZTYxNWQwMDI2M2YyMzc1ZTMzZGVkYjg2Zjg1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.n2XNRhqVdlQ2R2QEFRMv5p5cw3yBy8uvO82lZu61R7Y/>
</p>
<p>
Under the Admin Panel, under the Manage Tab, choose SLA and click the New SLA PLan button. Create the following SLAs with the appropriate Grace Periods and Schedules: SEV-A (1 hour, 24/7), SEV-B (4 hours, 24/7), SEV-C (8 hours, business hours).
</p>
<br />

<p>
<img src=https://private-user-images.githubusercontent.com/170815251/333830050-49e90eef-814f-4a4d-a697-3598cf12cffb.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY2NzAwNDUsIm5iZiI6MTcxNjY2OTc0NSwicGF0aCI6Ii8xNzA4MTUyNTEvMzMzODMwMDUwLTQ5ZTkwZWVmLTgxNGYtNGE0ZC1hNjk3LTM1OThjZjEyY2ZmYi5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyNVQyMDQyMjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wMWNmNWQ5Mjk1NjI1MjZmYmRlYjBkODczMzA3ODU1ZDljYzU2NDgxM2M0M2QwMmM0YTM1OWQxM2NiMDRkYzAxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.AB8EnG8hoSJSpr35hRKmrUuM8wWzAiAfeFCqn0SoyTA/>
</p>
<p>
Under the Admin Panel, under the Manage Tab, choose Help Topics and create the following Help Topics: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.
</p>
<br />
