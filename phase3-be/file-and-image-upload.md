---
layout: topic
title: File & Image Upload
topic: Python
category: phase3-be
parent: Phase 3 Back End
nav_order: 11
published: false
---

## Objectives

- How to upload files with Django & DRF
- How to configure storage for production uploads

## 🎯 Continue the Collaborative Project

Your documentation should be done and delivered to the front end by now. For an example of what your documentation should look like, see the README for the DRF Library example.

👉 If your project does not yet meet minimum requirements, you should aim for meeting them **by midweek**.

## 📁 Handling requests that include attached files

#### Using Insomnia

- Select the right HTTP method for your endpoint.
- Choose binary file attachment from the body menu (where you normally put the body of a request)
- Set headers on the Headers tab (this example assumes an image file in jpeg format, named `profile-photo.jpg`):

  ```txt
  Content-Type: image/jpeg
  Content-Disposition: attachment; filename=profile-photo.jpg
  ```

For more information on these headers see References.

#### CORS for file upload

Assuming you are using `django-cors-headers`, you'll need to add the following to `settings.py` to allow the request headers necessary for file attachments:

```py
# in settings.py

from corsheaders.defaults import default_headers

CORS_ALLOW_HEADERS = list(default_headers) + [
    'content-disposition',
]
```

## 📖 Read | 📺 Watch | 🎧 Listen

### File Upload

- [Django File (and Image) Uploads Tutorial](https://learndjango.com/tutorials/django-file-and-image-uploads-tutorial) -> A good and very recent post from Will Vincent; he does not include all the necessary info to make file uploads work in production but otherwise it's a good overview.
- 📖 [File Upload with DRF](https://goodcode.io/articles/django-rest-framework-file-upload/)
- 🎧 + 📖 [Success with Static Files](https://www.mattlayman.com/django-riffs/success-static-files/)
- 📖 [What is Amazon S3?](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html) -> Skim this -- this is Amazon's documentation and it gets really in-depth.
    - 📺 [Introduction to S3](https://www.youtube.com/watch?v=77lMCiiMilo) -> Also from Amazon

### Search

- 📖 [Basic and Full-Text Search with Django and Postgres](https://testdriven.io/blog/django-search/)
- 📺 [Search from the Ground Up](https://www.youtube.com/watch?v=is3R8d420D4&list=PL2NFhrDSOxgXXUMIGOs8lNe2B-f4pXOX-&index=2) -> Will Vincent talk at DjangoCon 2019 explaining search in detail
- 📺 [Pretty Printed: How to Perform Full Text Searches in Django with Postgres](https://www.youtube.com/watch?app=desktop&v=139a0fm0YFY)
- 📺 [Full Text Search with Django and PostgreSQL: More Facets, Less Dependencies](https://youtu.be/QFs6qgvyTC4) -> Team 11 Momentum grad Jason Judkins is a co-presenter of this talk given at last month's DjangoCon! 🤩
- 📖 [If you want A LOT more detail about full-text search in Postgres and Django, this blog piece has you covered](https://pganalyze.com/blog/full-text-search-django-postgres)
- 📖 [Blog post with more on full-text search](https://www.netlandish.com/blog/2020/06/22/full-text-search-django-postgresql/)

## 🔖 References

- [DRF File Upload][file-upload]
- [CORS][cors]
- [HTTP Headers][http-headers]
- [Search][drf-search]

{% include reference_links.md %}
