# boundlessBlog

A dynamic blog site where users can create accounts, write, edit, and delete posts, manage categories, and more.

## Introduction

Welcome to our blogging platform! This project is a Django-based web application that allows users to create accounts, publish and manage blog posts, organize content by categories, and more. It also integrates the powerful CKEditor for a seamless and feature-rich writing experience.

## Installation

Follow these steps to set up and run the blog locally on your machine.

## Prerequisites

Make sure you have the following installed:

Python,

Pip (Python package installer)

### Clone the Repository

`git clone https://github.com/your-username/your-blog-project.git`

### Navigate to the Project Directory

`cd your-blog-project`

### Create a Virtual Environment (Optional but recommended)

`python -m venv venv`

Activate the Virtual Environment

On Windows:

`venv\Scripts\activate`

### Install Dependencies

`pip install -r requirements.txt`

Apply Migrations

`python manage.py migrate`

Create Superuser (Optional)

`python manage.py createsuperuser`

Run the Development Server

`python manage.py runserver`

Visit http://localhost:8000/ in your web browser to access the blog.

### Usage

To start using the blog, follow these steps:

Create an Account:

Visit the registration page and create a new account.
Login:

Log in using your credentials.

Create a Post:

Navigate to the "Add Post" section to create a new blog post.
Edit and Delete Posts:

Manage your posts using the edit and delete functionalities.
Categories, Sorting, and Date/Time:

CKEditor Integration:

Enjoy a rich text editing experience with CKEditor while composing your blog posts.

## Features

### User Authentication (Signup/Login)

- Create,
- Edit,
- Delete
- Posts
- Category Management
- Sorting and Filtering
- Date and Time Display
- Integration of CKEditor

## Contributing

We welcome contributions! If you'd like to contribute to the development of this project, please follow the guidelines in CONTRIBUTING.md.
