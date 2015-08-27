---
title: Angular Authentication
type: lesson
duration: "1:25"
creator:
    name: Toneloke
    city: LA
competencies: Programming, Server Authentication with tokens
---

# Setting up authentication with Angular

### Objectives
*After this lesson, students will be able to:*

- Create their own auth service
- Understand how to store tokens using local storage
- Get an idea of how to setup your MEAN Stack applications
- Add the token to every request using Angular middleware

### Preparation
*Before this lesson, students should already be able to:*

- Create a MVC app with Express
- Create a schema with mongoose and create/read documents
- Create authentication server side using JWT
- Use Angular routes and understand SPAs


#### Authentication system

We've already implemented an authentication system in Express. For this lesson, we will use the previous backend api built with JWT.

For the beginning of this lesson we will be working out of the master branch. If you cannot keep up or have an error in the process, you can move to a branch and you should be caught up!

We will begin by taking a look at our folder structure and our backend.

Lets ensure everyone has a working api. We can send a post request to /api/sample , which will create a test user.

Test this out using postman. Play with token authentication explain how we use x-access-token in the header to send the jwt.

Start building the auth service, start with auth-token then auth-interceptor and finally auth which uses them.

Once the services are complete start to build out the mainController functionality. Ensure all services are added to the index.html and injected properly.

Build out the front end adding restriction to certain links and views based on the methods created in the mainController.
