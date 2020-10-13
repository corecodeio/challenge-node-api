# Node API Challenge

## Instructions

### Task 1: Set Up The Project With Git

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Clone your OWN version of the repository locally.
- [ ] Create a new branch: git checkout -b `feat/users`.
- [ ] Implement the project on your newly created `feat/users` branch, committing changes regularly.
- [ ] Push commits: git push -u origin `feat/users`.

### Task 2: Minimum Viable Product

For this project you will use `Test Driven Development` to create a RESTful API using `Node.js` and `Express` that publishes a set of endpoints to manage _users_. The database can be in memory. The API should have the following functionalities:

- `/api/users` **POST** should create a new user in teh database
- `/api/users` **GET** should return a list of users in the database
- `/api/users/:id` **GET** should receive user `id` and return the user data


A _User_ should have the following schema:

```javascript
{
   id: String,
   firstName: String,
   lastName: String,
   email: String,
   password: String,
   permissionLevel: Number
}
```

## Requirements

- use `jest` and `supertest` to write the tests.
- Your API must be able to **create** and **delete** a _user_.
- Write a minimum of two tests per route handler.

### Task 3: Stretch Goals

The following goals are designed to stretch your knowledge and may require additional research beyond what was learned in class today.

- [ ] Integrate Mongoose as the database
- [ ] Complete the rest of the CRUD operations and write tests for them.
- [ ] Hash the user password using `sha256`

## Submission format

Follow these steps for completing your project.

- [ ] Submit a pull request to merge `feat/users` on this repo. **Please don't merge your own pull request**
