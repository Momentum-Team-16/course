---
title: Completing Phase 3
phase: 3
date: 2023-02-06
layout: daily_post
---

To wrap up Phase 3, you'll finish the Social Cards project and create a short video walk-through of your code.

The project is due by EOD on {{ site.data.projects.collaborative_project.due_date | date:"%A, %B %-d" }}.

The video is due at 9:00 am ET {{ site.data.projects.phase_3_video_presentation.due_date | date:"%A, %B %-d" }}.

## ✅ Requirements for passing the phase (for both front-end and back-end)

1. Your application meets the minimum requirements detailed in the assignment.
2. Your application runs without errors in production.
3. Your application repo includes a README with a link to your production application and instructions for running the application locally.
4. Your presentation video meets the below requirements.

You might not pass the phase if:

- Your project is incomplete or does not meet the minimum requirements.
- Your project is not running in production.
- You have not made a substantive contribution to the project (i.e., you have committed meaningful code to the project).
- You cannot explain how your code works.
- You do not turn in a video.

### 📹 Video Presentations

Each of you (not each team, but each _individual_) will record a screencast on one of the topics listed below. The video should be **4-5 minutes long**, and no longer.

**Your target audience is a Momentum learner who is just at the beginning of Phase 3.** Imagine you are teaching them how to do what you've done in this project. Give them the benefit of your experience over these past several weeks.

**This video does not have to be polished, scripted, or edited.** But your viewer should be able to follow what you're saying and understand the points you are making.

If you don't already have a tool you're familiar with to record your video, [Loom](https://www.loom.com/) is very simple to use for screencasts and will let you share your video easily. The free account also limits your videos to 5 minutes, so it should help you with timing. You can record a screencast with or without your face showing; either way is fine.

- [Getting Started with Loom](https://support.loom.com/hc/en-us/articles/360015714197-Getting-Started-Video-Tutorials)
- [Loom Chrome Extension](https://www.loom.com/download)

Please post your video and submit the url for it using [this form](https://forms.gle/14ksHEXtGW2PGs1M7). **Your videos are due by 9:00 am ET on {{ site.data.projects.phase_3_video_presentation.due_date | date: "%A, %B %-d"}}.**

### Video Presentation Requirements

#### Back End

Your target audience is another beginner developer who is familiar with Django but not with DRF, Postgres, or deployment.

Your video should include a demo of your application via relevant requests in Insomnia and should show and walk through your code. **You must use the production endpoints in the demo**, not localhost.

Please focus on one of these topics.

1. Demo 1-3 endpoints in your application, explaining how you implemented them. Did you make any interesting decisions or customizations along the way? You might talk about some or all of these topics: the url patterns; the HTTP methods that are handled; serializers; permissions; querysets and any filtering you may have done.
2. Take one or more of the models you created for your project and explain their design. Why did you design your model(s) the way you did? Some things you probably want to talk about: the relationships a model has with other models, and why you need them; any custom methods you wrote for a model; any queries you did with your models that were tricky or interesting; anything you learned about how to work with models doing your project.
3. What is the most interesting specific feature or technical detail that you implemented for this project? Explain its functionality and implementation -- that is, what it does and how it does it.

#### Front End

Your target audience is another beginner developer who is familiar with JavaScript but not with React or deployment.

Your video should include a demo of the relevant part of your application running in the browser **in production**, not on localhost, and should show and walk through your code.

Please focus on one of these topics.

1. Walk us through the code for one of the components in your app and explain how it works. Topics you might touch on: what the purpose/responsibility of the component is; when and where it is rendered; what props it receives from its parent; any state the component has, what it's for, and how it changes; any events that component handles; any hooks used in the component besides useState (e.g., useEffect, useRef, useLocalStorageState).
2. Build a new teeny tiny React application from scratch and talk us through some of the basics, including components, state, and props. You can start _after_ creating a new create-react-app application and npm installing all the things. Your application should have at least one component that does something -- for example, you could show how to build an input form that echos whatever your user types and displays it on the page in real time. If you want to get fancier than this, you can -- just keep it to 5 minutes.
3. Explain how you have used React Router to implement routes in your app. What URLs can your app handle? How do you handle navigation from component to component?

## Peer Feedback

Peer feedback is often included in workplace review processes (sometimes it's called a 360º review), focusing on the collaborative nature of work. In software engineering, effective collaboration skills make you a valuable employee and contributor.

We're piloting an assessment of collaboration skills in Phase 3 that asks your teammates to evaluate the experience they have had working with you. Each person will be asked to fill out a form for other folks they have worked with throughout the course.

### How will the feedback be collected?

The feedback will be anonymous. I'll give you a Google form and assign you, privately, to the folks you will be asked to submit feedback for. I'll share the forms at the end of this week.

For each person, you'll be asked to provide feedback on a scale of 1-5, from strongly disagree to strongly agree, on the following collaboration skills:

- They communicate effectively.
    - If you communicate effectively, you do things like:
        - respond to messages on Slack promptly
        - check in with teammates often
        - proactively provide information that others need to know without waiting to be asked
        - let teammates know what you are working on
        - explain and share your ideas
- They collaborate effectively.
    - If you collaborate effectively, you:
        - ask what others think
        - listen carefully to other people's ideas
        - revise your ideas based on the ideas of others
        - compromise and seek consensus
        - find ways to share the work
- I can rely on them to do what they say they will do and to meet deadlines.
- They take on a fair or equal share of the work.
- They are considerate about not blocking the progress of others.
- They offer and provide help if needed and readily share what they know.
- They demonstrate that they care about delivering a great product.
- They treat me and others with respect.
- They show initiative and creativity in solving problems and finding solutions.
- I enjoy collaborating with them and would work with them again.

There is one open-ended question on the feedback form:

**What is the best thing about working with this person? What do you appreciate most about the work they do, or the way they work?**

👉 I'll share all the feedback about you with you.
