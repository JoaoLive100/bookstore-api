# Bookstore API

A simple Ruby on Rails RESTful API for managing a bookstore, featuring CRUD operations for books.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Database Setup](#database-setup)
  - [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Ensure you have the following installed on your machine:

- [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- [Ruby on Rails](https://rubyonrails.org/)
- [PostgreSQL](https://www.postgresql.org/download/)

## Getting Started

### Installation

Clone the repository:

```bash
git clone https://github.com/JoaoLive100/bookstore-api.git
cd bookstore-api
```

Install dependencies:

```bash
bundle install
```

### Database Setup

Make sure PostgreSQL is running. Create and migrate the database:

```bash
rails db:create
rails db:migrate
```

### Running the Application

Start the Rails server:

```bash
rails server
```

Your API will be available at http://localhost:3000.

## API Endpoints

### List Books:
`GET /books`

### Show a Book:
`GET /books/:id`

### Create a Book:
`POST /books`

### Update a Book:
`PUT /books/:id`

### Delete a Book:
`DELETE /books/:id`

Replace :id with the actual book ID.