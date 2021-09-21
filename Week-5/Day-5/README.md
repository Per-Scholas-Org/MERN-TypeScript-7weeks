# MERN-TypeScript-7weeks

## Week 5 - Day 5 - Skills Based Assessment (SBA)

*Prerequisite Knowledge: Data Persistence with cookies, local storage, and MongoDB. Authentication with JWT and password hashing with BCrypt. Deployment to Heroku.*

Coding Challenge: Create a Todo App that is username/password protected.

### MVP
RESTful API to Deployed Heroku

Create a RESTful API that allows users to create, read, update, and delete todo items. New users should be able to create a new account and then login to see the Todo list. Saved passwords should be hashed using BCrypt. The Todo list should be stored in a MongoDB database. Testing can be done with Postman.

### *Optional* Stretch Goal
Add a React Client.

Install a new application using `npx create-react-app client --template typescript` in the root directory. In the `client` directory, navigate to the `src` directory and create an application with CRUD functionality. The application should have a login page, a todo list page, and a form to create new todo items. The application should be deployed to Heroku.

### *Optional* SUPER Stretch Goal
Sign Out Functionality

Create a "Sign Out" button that clears the JWT cookie and redirects the user to the login page.
