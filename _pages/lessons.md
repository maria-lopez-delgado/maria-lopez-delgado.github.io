---
layout: archive
title: "Top 6 Lessons Learned"
permalink: /lessons/
author_profile: true
---
This page summarizes some of the lessons I learned while working as UX designer in some wonderful projects. Please explore the different approaches and learning moments that I feel were more significant for me as a UX designer.

[[1] Mental model alignment as a designer](#lesson-1)
[[2] Adapting to user goals for interaction](#lesson-2)
[[3] Understanding current users](#lesson-3)
[[4] Identifying potential user problems](#lesson-4)
[[5] Improving usability, but not aligning with users’ mental model](#lesson-5)
[[6] Translate requirements](#lesson-6)

---

### [1] Mental model alignment as a designer {#lesson-1}
* As a designer, I was **lost** in understanding and **aligning my mental model** when tasked to design Nexus, a data catalog to support the digital twin life cycle. I **researched examples** and **expected interactions**. And found it is similar to a library catalog, something I’m very familiar with. Because I was able to align my mental model to the design requirements, I was **able to design better**, and it aligned with the expected interaction. 
  * For example, when **designing** the **advanced search section**, I leverage my **own mental models** of interacting with a library catalog to align it with Nexus. In particular, focusing on **interaction users are familiar** with using, like being able to determine filters, add text they want to look for, and use Boolean operators.
* So as designers, we need to make sure we truly **understand** what we are task is, look at the competitors and potential users' familiarity. 

![Mockup advance search Nexus](/images/Lesson-2.png "Advance search")
###### Mockup design for advance search with all filters added

---

### [2] Adapting to user goals for interaction {#lesson-2}
* It is key to **understand how users will want to interact** with the tool. There might be circumstances for limited or no interaction with potential or current users. In speaking with the project owner, it might be an option to gauge an understanding of how the tool might be useful for users to interact with. 
  * For example, when designing for Nexus, a data catalog to support the digital twin life cycle, in particular, the data catalog landing page, the **initial understanding** was that users would only want to search within one project. After conversing with the project owner, the UX team realized that there might be **other use cases** where users would like to do data discovery across several projects. Adding the ability to easily select in what projects users want to search was an excellent example of **anticipating and adapting to user needs**.
* There is still a need to talk to potential users and see if the anticipated use case is needed and would improve the user experience. 

![Mockup data discovery multiple projects](/images/Lesson-3.png "Data discovery multiple projects")
###### Mockup design for data discovery across several projects

![Mockup data discovery all projects](/images/Lesson-4.png "data discovery all projects")
###### Mockup design for data discovery across all projects user is part of

---

### [3] Understanding current users {#lesson-3}
* When starting a **new project**, it is fundamental to get to **know** and understand **current users**. 
* When starting redesign work for DeepLynx, a data lake tool to support the life cycle of digital twins. The UX team was concerned that we needed to know more about your current users. 
    * When proposing a meeting with current users, the development team indicated there was a short deadline and limited resources. In so the UX team, in **collaboration** with the development team, created a **survey** for **current users**. We wanted to **understand** what **tools** they were **familiar** with, their role in the company, their work style, their experiences, and how they **interacted** with the **current version of the DeepLynx**. 
    * From this data, we developed **user personas** that help **guide** mockup **redesign**. It also helped the development team **understand** the **reasoning behind** some of the **design** decisions. 

![Persona 1](/images/Lesson-5.png "Persona 1")
###### Elle, is an engineer that has some knowlege about data warehouses, and mostly uses DeepLynx weekly for building Ontology and Quering features. 

![Persona 2](/images/Lesson-6.png "Persona 2")
###### James, is a manager that uses DeepLynx monthly for it's Graph and Model viewer to see the progress of the data containers.

![Persona 3](/images/Lesson-7.png "Persona 3")
###### Sherlock, is a research  that uses DeepLynx monthly for it's Graph and Model viewer to gather data for this projects.

---

### [4] Identifying potential user problems {#lesson-4}
* In redesigning DeepLynx, the UX team was **unable** to **meet** 1-1 with **current users** to gather their **issues** with the user interface. 
* To **identify** the **problems** we needed to address in the redesign, we leveraged **Nielsen’s Heuristic Evaluation**. 
* This evaluation also **helped justify** to the development **team** **why** we needed to address those changes. 
* We share the **findings** of the Heuristic Evaluation for adding a class in DeepLynx and our **proposed redesign**. 

![Existing UI](/images/Lesson-8.png "Existing UI")
###### Existing UI for editing a class
![Heuristic Evaluation](/images/Lesson-9.png "Heuristic Evaluation")
###### Summary of Heuristic Evaluation and changes
![Redesign UI](/images/Lesson-10.png "Redesign UI")
###### Redesign UI

---

### [5] Improving usability, but not aligning with users’ mental model {#lesson-5}
* When redesigning DeepLynx, the UX team **identified** some **complex interactions** and **proposed** a **simplified redesign**. 
* During **user testing**, using the **think-aloud method**, it was clear that the proposed redesign did **not align with their mental model** and expected interaction. 
    * For example, they would click on gray out sections added for context information to add a new edge and click on a gray out save button instead of clicking on the blue save button inside the box they were editing in. 
* Sadly, it was at the end of the internship, and we could not address another design solution. But it was a **great opportunity** to reinforce the **need for user testing before implementation**, and especially when redesigning a complex interaction. 

![New edge 1](/images/Lesson-11.png "New edge 1")
###### Creating a new edge, users got confused and clicked on the gray out information up top instead of the blue plus buttons.

![New edge 2](/images/Lesson-12.png "New edge 2")
###### Users would want to click on a gray out save button instead of clicking on the blue save button inside the box they were editing in

![New edge 3](/images/Lesson-13.png "New edge 3")
###### Users were confused on what save button to click on. 

---

### [6] Translate requirements {#lesson-6}  
*Understand requirements as shared to developers by stakeholders*
* While working in Spectra, a digital twin model viewer, an engineer handed his version of the design based on his conversations with the client.
    * It became a wonderful opportunity to **understand the engineer’s perspective on requirements and design**. 
    * In this case,  it was concerning the addition of a schedule to show the progress in construction, concurrent with the visualization in a Unity scene. 
    * **I was handed a sketch and told to make it look pretty**. And of course, I could make it look pretty, **but I could make it more intuitive and informative for the user**.  
        * In so I suggested 
            * Prioritize and organize content for users to quickly scan information needed to view the progress of the project
            * **Multiple indications of the status** of construction to correspond not only to highlights in the Unity scene when selecting an element, but solo next to the name to quickly see progress. 
            * Use of color and symbols to quickly gauge if the part is online or offline
            * An individual progress bar for each individual element to gauge the progress of construction.  
* While not being able to talk with potential users or clients, I was able to gain some insight from the engineer and optimize the design to be more intuitive and useful for users. 

![The San Juan Mountains are beautiful](/images/Lesson-14.png "San Juan Mountains")
###### Users will be able to know the status of the construction without having to click on the part.

![The San Juan Mountains are beautiful](/images/Lesson-15.png "San Juan Mountains")
###### Viewing the status both next to the part name and in the Unity scene. 