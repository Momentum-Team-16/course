---
layout: topic
title: Endpoints
topic: Python
category: phase3-be
parent: Phase 3 Back End
nav_order: 9
published: false
---

## Objectives

- How are the projects coming along? 👀
- Documenting and testing your API's endpoints with Insomnia
- Pagination

## 🎯 Project

Keep on going. 💪 🚀

Today we need to get you past any blockers you may be experiencing and plan next steps for your application.

By now you should have provided your front end with **documented and functional endpoints** to be able to use application data.

You should have djoser installed so that your log in and log out endpoints are working. Make sure you are sharing the Djoser information with your front end. You should include the authentication endpoints in your API documentation or project README.

## Creating a properly hashed password

In order to save a properly hashed password when you create a new user in the Django Admin, make sure you are using `UserAdmin` in `admin.py` so that you have that option in the admin interface. If you don't do this and save an unhashed password, you will run into authentication errors.

```py
from django.contrib import admin
from django.contrib.auth.admin import UserAdmin
...
admin.site.register(User, UserAdmin)
```

You can also [change a password from the command line](https://docs.djangoproject.com/en/4.0/topics/auth/default/#changing-passwords).

## 🔖 References

- [Authentication with Djoser][drf-authentication]
- [DRF in Depth][deep-drf]

{% include reference_links.md %}
