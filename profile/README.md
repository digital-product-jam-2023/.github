# Digital Product Jam

This repository holds Presentations and other learning materials for the Digital Product Jam course run as a joint course between the [Bezalel Academy of Art and Design](https://www.bezalel.ac.il/en), and the [Hebrew University](https://www.google.com/search?client=safari&rls=en&q=hebrew+universoity&ie=UTF-8&oe=UTF-8). These materials are designed for the development stream of the course, which includes an initial four weeks of web development fundamentals. Team work with the design class starts on week 5 and then the stream of activities largely merge.

## Course description

We all engage with digital products in daily life: we work with them, we express ourselves with them, we communicate through them, we discover information with them.

Students in the course will work in front of clients from the "real world" to learn about their audience as well as their business needs, in order to present solutions in the form of digital products, which they will design, develop, and deploy.

Students will work in teams of designers and developers and will experience product development processes, team work, and specifically dynamics between developers and designers in developing working products - just like in product development in the software industry.

## Course goals

- Experience of working in teams of designers and developers that is similar to "real" work in the software industry
- Experience of design, development and product management in front of "real" clients
- Experience of product development for "social good" organizations
- (Development stream) The application of web technologies towards the delivery of a working product
- (Design stream) The application of user interface design, branding and packaging toward the delivery of a working product

## Course discussion

[The discussion forum for the course is here](https://github.com/digital-product-jam/tasks/discussions).

## Submitting assignments {#assignments}

All assignments need to the submitted in the following way:

- All code must be commited to *your own* code repository (which is either a "copy" or a "fork" of an original codebase for the assignment), hosted on GitHub
- The application must be deployed and accessible via a public URL (this will happen automatically if Vercel is configured correctly for your application, but you should also verify on a per-assignment basis)
- On completion, submit your task by adding a comment with the following information to the open issue for the task [here](https://github.com/digital-product-jam/tasks/issues):
  - the URL to your GitHub repository
  - the public URL of the working application
- All tasks must be submitted by end of day on the Tuesday before the class (class is on Wednesday)

## Course outline

### Section 1: Development Fundamentals

**In this section of the course we will:**

- Learn about the web as a platform for digital products
- Learn about the process of product development
- Setup and work with a common set of development tools we will use for the whole course
- Develop and deploy web applications as learning and preparation for the teamwork in Section 2

#### Lesson 1 [[slides ↗]](https://digital-product-jam.vercel.app/01/)

*26th October, 2022* & *2nd November, 2022*

##### 🪑 Presentation

In the Digital Product Jam, students will experience working in teams - designers and developers - to plan, implement, and deploy working digital products for our collaborating organizations - a selection of Israeli "social good" not-for-profits.

Similarly to a real business environment, students will need to balance competing concerns that arise from working with a client, working in a team, and working with constraints like time. Technical skills are required, but in no way sufficient, for delivering a digital product.

We will illustrate this broader picture of working on digital products in a business context, and focus on the fundamentals of how the course will be run and graded, who is teaching, and what actually will be taught in the course.

##### 🏗 Workshop

We will get all students setup with the development environment we require for the course. This will mean installing apps and other development dependencies on student machines, creation of accounts on some web services we will use, and pulling, running, and deploying code to ensure everyone has a working environment.

##### 🏠 Home

Students will start from a template to develop and deploy their own "Profile" page. From the base we provide, students will make edits and enhancements that demonstrate:

- A working development environment
- A rudimentary understanding of HTML, CSS, and JavaScript

The task builds on the workshop done in class, and additional home reading on fundamental web technologies.

#### Lesson 2 [[slides ↗]](https://digital-product-jam.vercel.app/02/)

*9th November, 2022*

##### 🪑 Presentation

We are using the web as a delivery platform for our digital products in this course. What does that actually mean?

We will briefly review the history of the web in order to gain a basic understanding of the technologies we use to build web applications. Students will be exposed to fundamental web technologies, and shown how they are used to build applications via a series of demonstrations.

The purpose of the overview is to get a basic shared understanding of web technologies before we start using them to build increasingly more complex applications.

##### 🏗 Workshop

Each student will build an application that takes a dataset and presents it to a visitor. We will provide a list of data sources to choose from. The application needs to:

- Load data from an external source into an "internal" representation
- Render the data to the user interface, using some type of HTML structure
- Enhance the presentation of the data using CSS
- Allow some basic data interaction by the visitor

##### 🏠 Home

Students will finish the data application started in the class workshop.

Additionally, we provide home reading and walkthroughs for the more advanced "libraries" and "frameworks" that we will start using from next week.

#### Lesson 3 [[slides ↗]](https://digital-product-jam.vercel.app/03/)

*16th November, 2022*

##### 🪑 Presentation

The vast majority of professional applications do not use "raw" HTML, CSS and JS, but rather use higher-level "libraries" and "frameworks". We will briefly discuss why this is the case, and then get into specifics with the technologies we will adopt for our work going forward.

Our tools for building apps are based on [React](https://reactjs.org). We will overview React Components and Hooks, and specifically, managing state in React, and see how it all fits in context with [Next.js](https://nextjs.org) and [Supabase](https://supabase.com).

##### 🏗 Workshop

Each student will start building an application using our chosen libraries and frameworks. We will work on this same application over the coming weeks, **iterating** to add more functionality.

We will start by **re-implementing** our existing data application in the new framework. This basis will then be expanded on to introduce:

- Working with a database
- Authentication
- Access control
- Responsive design

##### 🏠 Home

Students will finish re-implementing their data application in the new framework. And, they will do an additional task of adding a contact form to learn how to work with a database from the application.

We provide further home reading and walkthroughs for React and Next.js.

#### Lesson 4 [[slides ↗]](https://digital-product-jam.vercel.app/04/)

*23th November, 2022*

_In this lesson we will start working with the design class._

##### 🪑 Presentation

With the development class, we will continue on aspects of building an application with Next.js.

We will then join the design class for introductions, and an overview of this next phase of the course.

##### 🏗 Workshop

With the development class, we will work with students to discuss challenges and approaches around their data application, and ensure the scope of work is something that can be finalized by next week.

With the merged class, we will have introductions and learn about scoping a product. We will use a "random startup generator" to seed ideas that we can experiemtn with.

##### 🏠 Home

Tasks on your data application.

With a team, take a product idea from the random generator and prepare a product deck.

### Section 2: Ship a working product in a team

**In this section of the course we will:**

- Learn about the clients we are working with for the course
- Work in teams to choose a client and define a "business problem" to present a product solution for
- Define a scope for the product solution, and the technical implementation of that scope, along with the design and user experience goals from the designers on the team
- Build and deploy a working product

#### Lesson 6

*30th November, 2022*

> 📝 **Milestone**: Developers can build and deploy a web app using our tech stack, with integrations for user authentication, database access, and API access.

> 📝 **Milestone**: We meet our clients and teams are formed.

##### 🪑 Presentation

Review of the home assignment.

Interactive session where we meet all of the "client" organizations who are working with us in the course. There will be plenty of time to ask questions and think about what type "business problems" could be addressed by "product solutions".

##### 🏠 Home

During this week we will form teams, and students will work in these teams going forward.

In preparation for that, the following needs to happen:

*By end of day Thursday December 1st*:

- Each student will submit her first and second choice of organizations to work with.
- Each student will submit names of students they would like to be teamed with (if any).

*By end of day Sunday 4th December*:

- All students will be notified of their team, and the client the team will work with.
- Each team prepares a document with ideas to bring to the next class, ready to start work.

_Additionally, if the development class needs further time or guidance on using React, we will set tasks and allocate teacher availability for this._

#### Lesson 7

*7th December, 2022*

##### 🪑 Presentation

All students sit in their teams.

We will work interactively on an ideation sprint.

##### 🏗 Workshop

Teams start work on their product decks and technical scope documents for the product solution they are working on.

##### 🏠 Home

Each team needs to finalize their product ideation deck and technical scope documents by end of day Monday 12th December. These will be submitted to the "clients" ahead of the next class.

#### Lesson 8

*14th December, 2022*

> 📝 **Milestone**: Review of a teams current product solution.

##### 🪑 Presentation

Each team will present their current work to the "client" and the teaching team, with a Q and A session. This gives the teams early client feedback to sharpen their understanding of what needs to be built.

##### 🏗 Workshop

A workshop session focussed on user research and personas.

A workshop session foccused on defining an MVP and strategic narrative for a digital product.

##### 🏠 Home

Teams should work together to lock down their product scope, via product ideation decks and technical documents.

Developers on each team get the basic skeleton of their project setup.

Teams should be able to come to the next class and be ready to start implementation work.

#### Lesson 9 - Holiday

*21st December, 2022*

#### Lesson 10

*28th December, 2022*

##### 🪑 Presentation

For this week, designers and developers are working seperately. For developers, a presentation on Figma and handoff of design to development teams.

##### 🏗 Workshop

We'll have open discussion on technical issues, scoping, organization of work. After any discussion, teams can work together on their solution.

In general, by this stage of the course the developers need to be ready with:

- What they need to build
- How to go about building it ( and, have already mapped out what you dont yet know how to do )
- A breakdown on how to split work with across their team
- Good alignment with the designers on their team - expectation management, appropriate scope, must haves vs nice to haves

For any aspects of the development that teams are unsure of how to tackle, they need to have written them up and shared with the teaching staff.

Also, developers should have a code repository setup and start using the issue tracker of the repository to break down development tasks.

##### 🏠 Home

Continue with team meetings and progress on the final project.

#### Lesson 11

*4th January, 2022*

> 📝 **Milestone**: Second review of work in progress product solutions.

##### 🪑 Presentation

TBD

##### 🏗 Workshop

TBD

##### 🏠 Home

Continue with team meetings and progress on the final project.

#### Lesson 12

*11th January, 2022*

> 📝 **Milestone**: Second review of work in progress product solutions.

##### 🪑 Presentation

TBD

##### 🏗 Workshop

Teams work together on their products. Teaching staff will work with teams to discuss challenges and approaches.

##### 🏠 Home

Continue with team meetings and progress on the final project.

#### Lesson 13

*18th January, 2022*

##### 🏗 Workshop

Teams work together on their products. Teaching staff will work with teams to discuss challenges and approaches.

##### 🏠 Home

Continue with team meetings and progress on the final project.

#### Lesson 14

*25th January, 2022*

> 📝 **Milestone**: Final review of product solutions.

##### 🪑 Presentation

Teams present their work to class and representatives of the clients.
