---
title: 'FE + BE Collaborative Project'
phase: 3
date: 2023-01-30
layout: daily_post
permalink: date
---

This week you will begin work on a project with both front- and back-end teammates. This project is due at the end of the Phase, on {{ site.data.projects.collaborative_project.due_date | date: "%A, %B %e" }}.

In order to successfully complete the phase:

- This project must be complete and meet the minimum requirements.
- It must be deployed and running without errors in production.
- Each team member must make a substantive contribution to the project (this is best demonstrated through frequent, well-formed commits).
- Each team member must be able to explain how the project works (that is, back-end devs know how the back-end works; front-end devs know how the front-end works).

The front-end will build a React application that will make AJAX requests to the back-end application built with Django and Django REST Framework. There are no strict rules about who works on front-end or back-end, so your team can decide how best to use your resources.

Your team can choose between two projects. They will _both_ give you practice doing what you have been doing (building an API or building a React application) but they present some different problems to solve.

Choose the one that sounds more fun or interesting to you.

We haven't yet covered everything you'll need to be able to do this project, so that will be our task this week and next.

## 🏗️ Project: Social Cards or QuestionBox


[🔗 GitHub Project Invitation Link](https://classroom.github.com/a/72vMj6Gn)

### How to accept the assignment and create the repos on GitHub

The back end will work in their own repo and the front end will work in their own repo, so for the same project there will be _two_ repos.

**One back-end dev** should accept the assignment invitation and create a new team; name the team something like "Team Yeti Back-end" (whatever your team name is!). Then the other back-end dev(s) should accept the assignment and choose the right team. All back-end folks on the team clone that same repo.

**One front-end dev** should accept the assignment invitation and create a new team; name the team something like "Team Yeti Front-end" (whatever your team name is!). Then the other front-end dev(s) should accept the assignment and choose the right team. All front-end folks on the team clone that same repo.

⚠️ You have to accept the invitation and join the team your teammate created in order to have write permissions to the repo.

**Today you should not need to commit or push any code since your main goal is planning**. Tomorrow you will learn how to work with others in a shared repo.

### The Teams

#### Team Clapton

- Jerome
- Jacob
{:.list--team}

#### Team Slash

- Lucian
- Cameron
- (Jacob on backend)
{:.list--team}

#### Team Hendrix

- Capel
- Daniel
- Marcus
- (Jerome on backend)
{:.list--team}

### How to work as one team
{:.section}

Even though you have separate codebases and separate applications, you're working together to ship a single product, on time. You can make product decisions together even though you will implement features separately.

We'll check in on the projects in class; front and back end teams will continue to meet separately. Come to your front-end or back-end meeting prepared to give progress reports and ask for help on what you're working on.

You are encouraged to work with the other front-end or back-end devs on other teams to share ideas, solutions, and resources.

### 🥅 Your Goals Today 🥅

- Read each project's README.
- Decide which project you want to do.
- Read your project's README again, carefully.
- Understand the project requirements thoroughly and discuss with your team what you need to build.
- Outline a detailed plan for how your team will implement the project requirements.
- **WRITE YOUR PLANS DOWN.** You can use any tools you like as long as the content you create is shareable. Some tools that might be useful: Trello, Google Docs, Excalidraw, Miro. Make sure everyone on your team has access to this documentation.

#### Front-end

You will need to sketch out the **[user flow](https://signalvnoise.com/posts/1926-a-shorthand-for-designing-ui-flows)** and [draw up some **wireframes**](https://xd.adobe.com/ideas/process/wireframing/wireframe-design-101/) for the application. It can help to ask questions like:

- What does our user see when they first land on our site?
- What will they need to do here?
- How will they accomplish that?
- What will happen next?
- If they click on a button or link, what happens?
- What does the UI look like after the user clicks on something / follows a link / submits a form?

##### By tomorrow front-end should have

- A detailed user flow plan/diagram
- Detailed wireframes
- A good initial plan of the components you think you will need

#### Back-end

You will need to draw ER diagrams to plan out the **models** and start a list of **endpoints** you think you will need. It can help to ask questions like:

- What are the _nouns_ in your project requirements? These are likely models.
- What data will you need to save in your database so you can look it up again later?
- What information will the front-end need so they can accomplish the UI that they are planning?
- What permissions will need to be in place?

##### By tomorrow back-end should have

- ER Diagrams for your models
- A list of endpoints
- A good initial plan for the JSON you think you will need to return

### Git Workflow

Working with other developers in a shared codebase means that the workflow you've been using so far will have to change. **We will cover this together on Tuesday.** If you want to get a head start, here are the slides for reference.

#### [Git Collaboration slide deck](https://slides.com/amy_nc/git-collaboration)
