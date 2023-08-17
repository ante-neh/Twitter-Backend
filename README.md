# Twitter Clone Backend

This repository contains the backend architecture of a Twitter clone, built using Node.js, Express, Prisma, and TypeScript. It provides a Restful API for user authentication, registration, and various Twitter-like functionalities.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Features](#features)
- [API Endpoints](#api-endpoints)
- [Authentication](#authentication)
- [Database](#database)


 ## Getting Started

### Prerequisites

- Node.js: Make sure you have Node.js installed.

### Installation

1. Clone the repository:
   git clone https://github.com/ante-neh/Twitter-Backend.git

2. Install dependencies:

3. Set up environment variables:

4. Run the application:
    npm start


## Features

1. User registration and login
2. Email authentication for secure account management
3. Post creation, retrieval, and deletion
4. Like and comment on posts
5. Follow and unfollow users
6. User profile management


## API Endpoints

1. POST /api/auth/register: Register a new user.
2. POST /api/auth/login: Authenticate and login a user.
3. POST /api/posts: Create a new post.
4. GET /api/posts: Retrieve a list of posts.
5. GET /api/posts/:postId: Retrieve a specific post.

## Authentication

User authentication is implemented using email and password. Upon registration, users receive a confirmation email to verify their account

## Database

This project uses Prisma as the Object Relational Mapper (ORM) to model and manage the database. The database schema and migrations can be found in the prisma directory.