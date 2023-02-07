---
title: Wrapping Up the Collaborative Project
phase: 3
date: 2023-02-07
layout: daily_post
published: true
---

## 🎯 The Definition of Done

👉 If your project meets minimum requirements today, HUZZAH! That is awesome. You should be working on **at least one additional or spicy feature**.

👉 If your project does not yet meet minimum requirements, your goal should be meeting them **by the end of the day tomorrow**.

**Please include a README** in your project repo. The README should:

- be titled README.md and live at the root of your project repo
- be written in Markdown
- include a link to your production application
- have instructions for getting your application running locally, so that any developer could pull it down and run it
- Backend: your README must include documentation for your API's available endpoints

## Minimum Requirements for Social Cards

- A user is able to sign up/register to be a user of your app.
- A user is able to log in to the app, and log out.
- A user can see a list of all the cards from all users of the app.
- A user can see a list of all the cards they've created.
- A user can see the details of a single card (with front and back messages).
- A user can create a new card.
- A user can update a card they created.
- A user can delete a card they created.
- A user can follow another user.
- A user can unfollow another user.
- A user can see a list all cards created by a user that they follow.
- A user can see a list all the users they follow.
- Your repo includes a README with project documentation.
- Front end: your app is styled in a way that looks finished.

### Back-end Notes

Depending on how you've constructed your API, you might have separate endpoints for all of the above, or some of the functionality might be combined in a single endpoint (for instance, if you nested answers in the question detail endpoint, like `questions/4/answers`). What matters is that your front-end team can perform all the necessary actions to provide full functionality to the user and that your endpoints are accurately documented in your README.

⚠️ Be sure to test that you have implemented permissions-checking correctly for these endpoints. For example, your API should not allow a user who is not the creator of a card to update a card.
