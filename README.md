# CS 255 System Analysis and Design: DriverPass

This repository holds two artifacts from SNHU CS 255:

- **Business Requirements Document** (Project One): `CS255_Project_One_Business_Requirements_Document_Noah_Kersey.docx`
- **System Design Document** (Project Two): `CS255_Project_Two_System_Design_Document_Noah_Kersey.docx`

## Reflection

**Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?**

The client was DriverPass, a company that wanted to help students pass their DMV driving tests. Its owner, Liam, saw that many people fail the test because they lack good preparation. DriverPass wanted a cloud-based system, usable on the web and on phones, that offers online practice tests and classes, lets customers and the secretary book, change, and cancel in-car driving lessons with trainers, and gives the owner and IT officer reports, activity logs, and control over user accounts and lesson packages.

**What did you do particularly well?**

I think I did well at turning a casual interview into clear, organized requirements. I separated functional requirements from nonfunctional ones, tied each one back to something the client actually said, and carried those requirements straight into my UML diagrams. In the design document, the use case, activity, sequence, and class diagrams all describe the same system consistently, and the technical requirements section lays out the hardware, software, tools, and infrastructure the developers would need.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**

I would revise the class diagram. It has 16 classes, which makes it dense and hard to read on one page. I would split it into smaller views, such as one for users and roles and one for scheduling and payments, and I would recheck each relationship's multiplicity against the requirements so a developer could build the database from it with no guesswork.

**How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?**

I read the interview transcript closely and listed what each type of user needed. Customers needed easy online booking and progress tracking. The secretary needed to book appointments for people who call in. The owner needed reports and a log of who changed reservations. The IT officer needed to manage access and reset passwords. Each of those became a use case, and the most important ones, like scheduling a lesson and registering an account, became activity and sequence diagrams. Considering the user's needs matters because a system can work perfectly from a technical point of view and still fail if it doesn't solve the client's real problems. Fixing a missed requirement after the system is built costs far more than getting it right during design.

**How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?**

I start by understanding the problem and the people involved before thinking about technology. In the future I would keep using interviews and requirement lists, then UML diagrams to check my understanding: use case diagrams for the big picture, activity and sequence diagrams for key processes, and class diagrams for the data. I would also use a blended approach that mixes object and process modeling, build in time for client feedback through iterative reviews, and plan the schedule with tools like a Gantt chart so the whole team can see how the work fits together.
