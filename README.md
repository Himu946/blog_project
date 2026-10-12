# 📝 Blog Project

A single-page blog app where you can create, view, edit and delete blog posts, each with a title, an image and a description. Posts are stored through a REST API using [crudcrud.com](https://crudcrud.com).

## Features

- Create a post with a title, image URL and description
- List every post as a card
- Edit and delete posts
- Full CRUD over HTTP with Axios (`GET`, `POST`, `PUT`, `DELETE`)

## Tech stack

HTML · CSS · JavaScript (async/await) · Axios · REST API

## Run it locally

```bash
git clone https://github.com/Himu946/blog_project.git
cd blog_project
# open index.html in your browser
```

> **Note:** crudcrud.com endpoints expire after a while. If posts don't load, create a free endpoint at crudcrud.com and replace the API URL in `index.html`.

## What I learned

- Calling a REST API with Axios and `async`/`await`
- Rendering a list from API data and updating it after each change
- Handling errors from network requests
