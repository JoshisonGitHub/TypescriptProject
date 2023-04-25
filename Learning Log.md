# Learning Log

--- 

## Week 1 
#### Uploaded 16/02/2023

During week 1 I chose a group to work with, as I wanted to collaborate with other computer science students on a new project.

We began by brainstorming and documenting project ideas, linked [here](https://docs.google.com/document/d/13toE3SYV0K4IG2FPP6fhk4kCVGq5jh-FQ2uWeFDy4QU/edit).

--- 

## Week 2
#### Uploaded 16/02/2023

In week 2 our group agreed our project. We decided to use Typescript and brainstormed project ideas. Our first idea was a person-to-person messaging system, until we considered creating a "mock" banking website. Not only could we make the webiste a single page application, but we could also learn SQL for the back-end database in addition to learning typscript.

We therefore, chose as our project: **A mock banking website with an SQL database linked to the back-end**.

We then made a rough timeline of weekly tasks:

| Week     | Task |
| ----------- | ----------- |
| 3      | Learn typscript       |
| 4   |  Make front-end template and back-end template<br>Split front-end code into sections for each person to complete<br>Split back-end code into sections for each person to complete |
| 5   |  Finish front-end and link it to back-end |
| 6   |  Learn SQL for database |
| 7   |   Create database back-end and link to front-end |
| 8   |  Bug fixes<br>Polish front-end |

### Goals
The next step to achieving Goal 1, learn Typescript, is to use the next week to research Typescript.

---

## Week 3
#### Uploaded 18/02/2023

We began week 3 by structuring our tasklist more logically (eg to work on the back-end *after* learning SQL). See changes [here](https://docs.google.com/document/d/13toE3SYV0K4IG2FPP6fhk4kCVGq5jh-FQ2uWeFDy4QU/edit). 

However, the main focus was learning Typescript which I enjoyed, as it resolves issues I have with Javascript including:

1. **Readability**: I find it difficult to read other peoples code in Javascript. Typescript fixes this by adding types to each variable which improves legibility, as knowing the type of each variable makes it easier to understand the context of the input and ouput types and how the function will be used.
2. **Bug Fixes**: As Typescript forces all variables to have a type, errors caused by allocating a variable a wrong type will be spotted in the interface by Typescript, rather than being spotted late in the developer console when using Javascript.

By searching YouTube for Typescript videos for viewers with prior Javasciprt knowledge, I generated videos demonstrating the differences between them. I also created a notepad document to summerise my learning and record my sources, to assist me in documenting my learning steps when I later create my guide to learners. Finally, I created a Pratice Project following [this](https://www.youtube.com/watch?v=kSukGsJ0s9A) YouTube tutorial.

To summarize these videos taught me how:
* to install Typescript in vs code using node
* the packaging system works in node 
* files are created
* to apply types to variables
* to use interfaces in typscript
* to use functions using interfaces
* to use classes using interfaces 

### Goals

We completed our Goal 1, "learn Typscript". Next week we hope to complete Goal 2.

---

## Week 4
#### Uploaded 26/02/2023

Having overestimated the time available to us, we assigned more realistic completion dates to all tasks (see [here](https://docs.google.com/document/d/13toE3SYV0K4IG2FPP6fhk4kCVGq5jh-FQ2uWeFDy4QU/edit)). We also decided to use React for the front-end development, as it would allow us to write more Typescript. We also considered using SQL Lite as it is better for collaborative development, but will look into this further once we come to apply our SQL learning. We also created the website's front-end template. Next week we will complete the fronte-end using that template.

### Goals

No goals were completed this week, but we are one step closer to finishing the website's front-end.

---
## Week 5
#### Uploaded 05/03/2023

In week 5 we began working on the front-end using the template created in week 4. I started with the sidebar as I anticipated this would take the longest as we were new to React and Typescript. I started researching templates for creating sidebars. Most were created using Javascript and React only, not Typescript and so I examined them to better understand how the React libraries worked in order to create my own sidebar. Fortunately, I found a template that used React and Typescript, so I studied this template's code and tweeked it for our project (link to the webiste can be found [here](https://annysah.hashnode.dev/build-a-sidebar-menu-with-react-typescript-and-styled-components-ckwkykpm80hs7gns112nycvvy)).

I then tested the sidebar to see how it looked on our webpage. Unfortunately the test generated errors caused by missing libraries. I was unsure how to fix this as I had followed the tutorial, installed every React library listed and double-checked my work. 

Another team member, however, who was also working on a sidebar and pushed his branch to the main project branch. Although my work was no longer needed, I felt I had gained valuable knowledge on using React libraries in conjunction with Typescript to create functional, legible code.

### Goals

No goals were achieved this week, but as the front-end is completed we are one step closer to achieving Goal 4.

---
## Week 6
#### Uploaded 12/03/2023

This week our group learnt SQL and made an entity relationship diagram for the database (see [here](https://docs.google.com/document/d/13toE3SYV0K4IG2FPP6fhk4kCVGq5jh-FQ2uWeFDy4QU/edit)). However, due to other work commitments we have fallen behind schedule by a week: We should have already started the back-end development. 

Learning SQL and entity relationship diagrams in recent lectures assisted our understanding of basic SQL commands. 

### Goals

Goal 2 is completed.

### For completion next Week

We must make progress on the database and back-end, and, if time permits, the website's login system.

## Week 7 - 9
#### Uploaded 05/04/2023

During the past 3 weeks we have made significant progress on the website and agree that it is "finished". We focussed on:

1. New Front-end
2. Front-end Functionality 
3. Server (Back-end)
4. GET and POST Requests 
5. Database

### New Front-end

We redid the entire front-end so that it wasn't hardcoded in CSS and instead worked dynamically with different viewport sizes. Currently the website doesn't work on phone view, but could be implemented in the future.

### Front-end Functionality 

I implemented the front-end functionality, such as buttons to create and delete accounts, switch accounts, and transfer money. To do this I used modals and linked them to the sidebar. I was able to send the data from each input field to the back-end for all our functions we implemented, including account name, amount of money transfered. I did this using the React version of sending data with json.

### Server

Creating a server to host the webiste presented difficulties as the server had to run off a different port and communicate with the wepage rather than having direct access to it. We used paths to link them together.

### GET and POST Requests

We created GET and POST requests for all data that would be sent to the back-end from the website, such as creating new accounts, deleting accounts etc. These functions are all linked with the database so the input from the front-end gets added to it. Due to time constraints we were unable to make the webiste available to users via a login system and so user data in each GET and POST method is a template user.

### Database

The database is functionally complete and is the most complex part of this project as it even contains unused data such as the login system data including user ID and other user data. This is useful, as if we were to seriously develop this project we would not have to change the database, as the entity relationship diagram would remain valid.

### Goals

To summarise which Goals we achieved and which we fell short on:

* Goal 1: Learn Typescript
  * Achieved.
* Goal 2: Learn SQL
  * Achieved.
* Goal 3: Create legible code with comments that any coder will understand
  * I would argue that we achieved this goal, as even though we did not add too many comments to our code, we did however segment the code nicely and made variable names and functions that are easily understood.
* Goal 4: Create a functional Website linked with a database
  * Achieved: We created a functioning database, linked to a functional front-end webpage.
* Goal 5: Create a login system for the website
  * We fell short on this goal due to time constraints, although it would be easily implement it in the future as the database was created with a login system in mind.


### My final thoughts 

I felt this project went well and that we worked well as a team, supporting each other as needed. I was happy with how our project manager lead the team whilst simultaneously working on their own part of the project. Working with Git, although challenging, was rewarding and I now better understand how major project development would operate in a company. I gained valuable knowledge throughout the project and am glad I had the oportunity to learn new skills.