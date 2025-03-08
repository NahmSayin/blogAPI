# Blog API

A simple Django REST API for managing blog posts.

## Features
- List all blog posts
- Retrieve a specific blog post by ID
- Create a new blog post
- Update an existing blog post
- Delete a blog post

## Endpoints

- **GET** `/api/posts/` - List all blog posts
- **GET** `/api/posts/<id>/` - Retrieve a specific post by ID
- **POST** `/api/posts/` - Create a new post
- **PUT** `/api/posts/<id>/` - Update an existing post
- **DELETE** `/api/posts/<id>/` - Delete a post

## Technologies Used
- Django
- Django REST Framework