# Outline

v0.0.7

### End Goal

Build a full-stack application with Node, Express, Postgres, React, and Redux.

### Example Code

Make sure to create a new directory on your machine called "node-workshop" to house all of your projects for these workshops. Each individual assignment should be placed within that directory. Make sure to add a git repo to each directory.

## Timeline

1. 02/26 - 7:30am to 11:30am
1. 03/05 - 8:00am to 2:30pm
1. 03/11 - 7:00am to 2:00pm
1. 03/19 - 8:00am to 4:00pm

## Day 0

1. [Pre-work](lessons/00-prework.md) (please complete before the first session)

## Day 1

### Info

- Topics: Review, Node/Express, CRUD
- Duration: 3 to 4 hours

### Objectives

By the end of this session, you should be able to...

1. Build a full-stack JavaScript application using the [Express Generator](https://expressjs.com/en/starter/generator.html) as a boilerplate
1. Customize the Express Generator scaffold
1. Develop a CRUD app with Node and Express
1. Utilize server-side templating with [Nunjucks](https://mozilla.github.io/nunjucks/)

### Outline

1. Stand-up:
  - How did the pre-work go?
  - Review, work through problems together
1. [Full-Stack App](lessons/01-fullstack-app.md)
1. Homework
  - Finish [node-jobs](exercises/node-jobs)
  - Refactor all of the [challenges](challenges/README.md) - refactor logic into a module (*helpers.js*), use promises, resolve promise from separate file (*app.js*), [example](challenges/promises-example)
  - Read [A Proper API Crash Course](https://github.com/james-gibson/apiTips)
  - Add a RESTful API to [node-jobs](exercises/node-jobs) - GET ALL jobs, get SINGLE job, add job, update job, delete job
  - Build a full-stack app, with server-side templating, from scratch
  - Review [herman-express-generator](https://github.com/mjhea0/generator-herman-express) - install, create boilerplate, review code, add comments

## Day 2

### Info

- Topics: Node/Express, RESTful APIs, Single Page Applications, jQuery
- Duration: 5 to 6 hours

### Objectives

By the end of this session, you should be able to...

1. Develop a RESTful API with Node and Express
1. Describe how the microservice architecture differs from the monolithic architecture along with how single page apps differ from multi page apps
1. Describe service oriented architecture
1. Add jQuery to client-side, build SPA

### Outline

1. Stand-up:
  - How did the homework go?
  - What did we cover last time?
1. [Microservices vs Monolithic Architecture](https://www.mulesoft.com/resources/api/microservices-vs-monolithic)
1. SPA Practice - add a [jQuery client-side](exercises/node-jobs-client)
1. Homework
  - Finish [node-jobs-client](exercises/node-jobs-client)
  - Go through [Test Driven Development With Node, Postgres, and Knex (Red/Green/Refactor)](http://mherman.org/blog/2016/04/28/test-driven-development-with-node)
  - Go through [Intro to React](https://github.com/mjhea0/react-intro)
  - Add server-side, integration tests to the [node-jobs-api](exercises/node-jobs-api)
  - Review as much of [30 Days of React](https://www.fullstackreact.com/30-days-of-react/) that you can get through (up to Redux)

## Day 3

### Info

- Topics: Postgres, Knex, React
- Duration: 6 to 7 hours

### Objectives

By the end of this session, you should be able to...

1. Set up a project with knex.js
1. Write schema migration files with knex to create new database tables
1. Generate database seed files with knex and apply the seeds to the database
1. Perform the basic CRUD functions on a RESTful resource with knex methods
1. Describe why you would want to use React
1. Create a React boilerplate with [Create-React-App](https://github.com/facebookincubator/create-react-app)
1. Develop a multi-component React app
1. Use Axious to make AJAX requests in a React component

### Outline

1. Stand-up:
  - How did the homework go?
  - What did we cover last time?
1. Postgres
1. Knex
1. React

## Day 4

Topics:

- Gulp
- Testing
- Redux
- Capstone planning
- Agile
- Feature branch workflow
