# MERN-TypeScript-7weeks

## Week 5 - Day 5 - Skills Based Assessment (SBA)

*Prerequisite Knowledge: Data Persistence with cookies, local storage, and MongoDB. Authentication with JWT and password hashing with BCrypt. Deployment to Heroku.*

Coding Challenge: Create a backend API for a Todo App which stores its data in MongoDB

### MVP
RESTful API

Using express and Node.js create a RESTful API to create, read, update, and delete todo items. The Todo list must be stored in a MongoDB database.  Testing can be done with Postman.

Here is an example todo: `{ content: 'Buy groceries' }`

Your API must have the following endpoints:

`GET /todos` - this returns an array of JSON objects representing all TODO items
`GET /todo/:id` - this returns a JSON object with information about a todo. Use the `_id` property which MongoDB automatically gives to all new documents.
`POST /todo` - creates a new TODO. Should contain JSON in the POSt request body with a todo item.
`PUT /todo/:id` - changes the content of an existing todo.
`DELETE /todo/:id` - deletes an existin todo.

### *Optional* Stretch Goals

1. Use Typescript
2. User accounts and auhtorization: New users should be able to create a new account and then login to see the Todo list. Saved passwords should be hashed using BCrypt. 
