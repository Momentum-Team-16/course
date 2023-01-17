---
layout: topic
title: Queries and Using the Shell
topic: Python
category: phase3-be
parent: Phase 3 Back End
nav_order: 3
published: false
---

## Today's Topics

- Interacting with models in the shell
- Queries and more queries

## 🎯 Project: Still Working on Habit Tracker

You can do this! 💪 **What do you need to figure out in order to finish it?**

### 📖 Read | 📺 Watch | 🎧 Listen

- [Database Design for Beginners](https://youtu.be/1VsSXRPEBo0) _This is a talk from RailsConf, which is focused on Ruby on Rails (Rails is a framework for building web applications in Ruby, very similiar to Django). The talk is an excellent introduction to how to think about your data model -- that is, the logic that drives the decisions you make about the models in your code and the structure of your database. Please watch it all the way through; even though it uses Ruby examples you should be able to get the gist._

This rest of this section is material to prep for the topic we will begin next week: building APIs.

- [RESTful APIs](https://restful-api-design.readthedocs.io/en/latest/intro.html) Read up through the "Standard Methods" subsection of the section on "Methods". You can read more if you want to but it gets pretty deep.
- [Safia Abdullah, You and Me Learn All About HTTP](https://dev.to/captainsafia/you-and-me-learn-all-about-http-with-safia-abdalla-3nd0)
- [Web APIs Explained By Selling Goods From Your Farm](https://blog.codeanalogies.com/2018/02/27/web-apis-explained-by-selling-goods-from-your-farm/)

#### 🦄 PRO TIPS

- `django-debug-toolbar` has a SQL panel that will show you the queries you are running in the view.
- With `shell_plus`, you can see output of all the SQL queries if you run it like this:

```py
python manage.py shell_plus --print-sql
 ```

## 🔖 References

- [Models & Queries]({% link references/advanced-django-models-and-queries.md %})
- [Databases]({% link references/databases.md %})
