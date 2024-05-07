# 📚 Node.js Syllabus

## Table of Contents

- [Basic](#basic)
- [Intermediate](#intermediate)
- [Advanced](#advanced)

## Basic

- [Introduction to Node.js](https://nodejs.org/en/about/)
- [Node.js Basics](https://nodejs.org/en/docs/guides/getting-started-guide/)
  - [Installing Node.js](https://nodejs.org/en/download/)
  - [Node.js REPL](https://nodejs.org/en/docs/guides/getting-started-guide/)
  - [Node.js Modules](https://nodejs.org/en/docs/guides/getting-started-guide/)
- [Node.js Core Modules](https://nodejs.org/en/docs/guides/getting-started-guide/)
  - fs (File System)
  - http
  - path
  - events
- [npm (Node Package Manager)](https://docs.npmjs.com/)
  - Installing packages
  - Creating and publishing packages
  - Managing dependencies
- [Asynchronous Programming in Node.js](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
  - Callbacks
  - Promises
  - Async/Await
- [Express.js Framework](https://expressjs.com/)
  - Routing
  - Middleware
  - Templating engines (e.g., EJS, Pug)
  - Error handling middleware
  - Static file serving middleware
  - Third-party middleware (e.g., body-parser)
- [Creating RESTful APIs with Express.js](https://expressjs.com/en/starter/basic-routing.html)
  - GET, POST, PUT, DELETE methods
  - Middleware for authentication and authorization
  - Validation middleware (e.g., Joi)
- [Working with Databases](https://node-postgres.com/)
  - Connecting to databases
  - Executing SQL queries
  - ORM (Object-Relational Mapping) with Sequelize or Mongoose
  - Database migrations
  - Database seeding
- [Authentication and Authorization](https://github.com/jaredhanson/passport)
  - Using Passport.js for authentication strategies
  - JWT (JSON Web Tokens)
  - OAuth authentication
- [Testing Node.js Applications](https://mochajs.org/)
  - Unit testing with Mocha
  - Assertion libraries (e.g., Chai)
  - Mocking with Sinon
  - Integration testing
  - End-to-end testing with tools like SuperTest
- [Logging and Monitoring](https://nodejs.org/en/docs/guides/debugging-getting-started/)
  - Logging libraries (e.g., Winston, Bunyan)
  - Application performance monitoring (APM) tools like New Relic or AppDynamics
  - Error tracking with tools like Sentry or Rollbar

## Intermediate

- [Asynchronous Patterns](https://blog.risingstack.com/node-js-async-best-practices-avoiding-callback-hell-node-js-at-scale/)
  - Callbacks
  - Promises
  - Async/Await
  - Event Emitters
- [Streams](https://nodejs.org/api/stream.html)
  - Readable streams
  - Writable streams
  - Transform streams
  - Piping streams
- [Middleware Development](https://expressjs.com/en/guide/writing-middleware.html)
  - Developing custom middleware
  - Middleware execution order
  - Error-handling middleware
  - Third-party middleware development
- [Debugging Node.js Applications](https://nodejs.org/en/docs/guides/debugging-getting-started/)
  - Using debugger statement
  - Debugging with Chrome DevTools
  - Profiling Node.js applications
- [Scaling Node.js Applications](https://blog.risingstack.com/scaling-node-js-applications/)
  - Load balancing strategies
  - Microservices architecture
  - Caching strategies
- [Security Best Practices](https://blog.risingstack.com/node-js-security-checklist/)
  - OWASP Top 10 vulnerabilities
  - Input validation and sanitation
  - Cross-Site Scripting (XSS) prevention
  - Cross-Site Request Forgery (CSRF) protection

## Advanced

- [Real-time Applications with Socket.IO](https://socket.io/get-started/chat/)
  - WebSocket protocol
  - Broadcasting events
  - Room-based communication
- [Dockerizing Node.js Applications](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)
  - Containerization basics
  - Docker-compose for multi-container setups
  - Optimizing Docker builds
- [Serverless Architectures with Node.js](https://serverless.com/framework/docs/providers/aws/guide/intro/)
  - AWS Lambda functions
  - Serverless framework
  - Event-driven architecture
- [GraphQL with Node.js](https://graphql.org/graphql-js/)
  - Schema definition
  - Resolvers
  - Apollo Server for GraphQL implementations
  - GraphQL subscriptions
- [CI/CD Pipelines for Node.js](https://circleci.com/blog/how-to-build-a-nodejs-ci-cd-pipeline-using-circleci/)
  - Continuous Integration (CI) with tools like CircleCI or Travis CI
  - Continuous Deployment (CD) strategies
  - Deployment pipelines
- [Authentication with OAuth2](https://oauth.net/2/)
  - OAuth2 protocol
  - Implementing OAuth2 authentication in Node.js applications
  - Using OAuth2 providers like Google, Facebook, or GitHub
- [Full-Text Search with Elasticsearch](https://www.elastic.co/)
  - Introduction to Elasticsearch
  - Setting up Elasticsearch in Node.js applications
  - Indexing and searching documents
- [Server-side Rendering (SSR) with Next.js](https://nextjs.org/)
  - Introduction to Next.js
  - Configuring server-side rendering
  - Optimizing for SEO
