---
layout: topic
title: Search in React
topic: JavaScript
category: phase3-fe
parent: Phase 3 Front End
nav_order: 11
published: false
---

## Objectives

- Checking in on project progress 👀
- Adding search in your application 🔍

To implement search in your application, you will need to collect user input and then either make an API request or filter existing data on the page. It's often useful to have a text input so that your user can type in a search term, although you could use other types of inputs as well.

## 🎯 Project due

**Please include a README** in your project repo. The README should:

- be written in Markdown
- include a link to your production application
- have instructions for getting your application running locally, so that any developer could pull it down and run it.

👉 If your project meets minimum requirements today, HUZZAH! That is awesome. You should be working on **at least one additional or spicy feature**.

👉 If your project does not yet meet minimum requirements, your goal should be meeting them **by midweek**.


## Example Search Request with Query Params

Remember the [iTunes API](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/iTuneSearchAPI/Searching.html#//apple_ref/doc/uid/TP40017632-CH5-SW1)? You made a request to the API to get search results, and you needed to include query params that specified the search fields and terms you wanted to use for the search.

Here's how you might make a request that uses query params using [Axios](https://github.com/axios/axios#request-config). Note: this example depends on `searchTerm` and `token` being defined in your code.

```js
axios.get('https://drf-library-api.herokuapp.com/api/books',
  {
    params: {search: searchTerm},
    headers: {Authorization: `Token ${token}` }
  }
)
```

## 🔖 References

- [Search & Filtering][react-search]
- [Forms][react-forms]
- [useRef][react-useref]
- [custom hooks][react-custom-hooks]

{% include reference_links.md %}
