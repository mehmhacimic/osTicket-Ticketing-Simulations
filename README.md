
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket-Ticketing-Simulations</h1>
This tutorial simulates some real-world ticketing examples that we might see in the day-to-day of a help desk employee. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Closing the Ticket
---
1.  Navigate to [localhost/osTicket](http://localhost/osTicket/) in your Virtual Machine.

   <img src="https://github.com/mehmhacimic/osTicket-Ticketing-Simulations/assets/157438082/bfabeae9-b2bb-454c-8e39-41949a08009f" width="350" height="320">
   <img src="https://github.com/mehmhacimic/osTicket-Ticketing-Simulations/assets/157438082/3c38b3a2-ae31-487a-b550-3202002b05b6" width="350" height="320">

2.  Create tickets based on the provided examples:

* Sev-A Ticket

    * Subject: "Entire mobile banking system is down"
    * Description: Provide additional details if needed.
    * Help Topic: Business Critical Outage

      <img src="https://github.com/mehmhacimic/osTicket-Ticketing-Simulations/assets/157438082/22d5cccc-a059-422e-92c8-ea981d890fe6" width="350" height="320">
      
* Sev-B Ticket

    * Subject: "Accounting department needs Adobe upgrade"
    * Description: Include relevant information.
    * Help Topic: Business Critical Outage

* Sev-B/C Ticket

    * Subject: "CFO’s laptop seems a bit slow"
    * Description: Specify the issue with the CFO’s laptop.
    * Help Topic: Equipment Request

3. Triaging tickets

   - Log in as your *Admin* agent
   - Access the osTicket dashboard and navigate to the ticket list

     <img src="https://github.com/mehmhacimic/osTicket-Ticketing-Simulations/assets/157438082/3dd7c579-3c81-4f83-b9d1-37e54d0953b6" width="350" height="320">
   - For each ticket:
      - Review the ticket details
      - Confirm the severity level and priority
      - Assign the ticket to the appropriate team or individual(especially as an agent with limited capabilities, such as only being able to assign and reply to tickets)

        <img src="https://github.com/mehmhacimic/osTicket-Ticketing-Simulations/assets/157438082/2f811bcb-bc8a-46f7-b907-1c67711705ba" width="350" height="320">

4. Ticket Lifecycle Management
Update the ticket status as it progresses through the lifecycle:

   - Open: Ticket is created and awaiting action.
   - In Progress: Team is actively working on a solution.
   - Resolved: The issue has been addressed and resolved.
   - Closed: Confirm closure of the ticket.

5. Communication and Collaboration
   - Utilize the comment section in each ticket to communicate updates, solutions, or additional information.
   - Collaborate with team members through comments to share insights or request assistance.
6. Monitor and Review
   - Regularly review the ticket dashboard to monitor the status of all tickets.
   - Conduct periodic reviews to analyze the resolution time and identify areas for improvement.

7. Practice and Iterate
   - Repeat the process with additional tickets to practice and refine your ticket management skills.
   - Make adjustments to the workflow or priorities based on the lessons learned during the practice.
   

   
