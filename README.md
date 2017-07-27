# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## API Endpoints
This API will expose the following RESTful endpoints

|        Endpoints        |        Functionality        | Status |
|-------------------------|:---------------------------:|:------:|
| POST /signup            |                      Signup |   --   |
| POST /auth/login        |                       Login |   --   |
| GET /auth/logout        |                      Logout |   --   |
| GET /todos              |              List all todos |  Done  |
| POST /todos             |           Create a new todo |  Done  |
| GET /todos/:id          |                  Get a todo |  Done  |
| PUT /todos/:id          |               Update a todo |  Done  |
| DELETE /todos/:id       | Delete a todo and its items |  Done  |
| GET /todos/:id/items    |             Get a todo item |  Done  |
| PUT /todos/:id/items    |          Update a todo item |  Done  |
| DELETE /todos/:id/items |          Delete a todo item |  Done  |
