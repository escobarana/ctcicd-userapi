# Continuous Testing, Continuous Integration &amp; Continuous Delivery (Deployment) (CI/CD) of an User API

Basic NodeJS web application exposing REST API that creates and stores user parameters in a Redis database.

Set up GitHub Actions for CI/CD and a Heroku app for deployment (`https://cd-userapi.herokuapp.com/`) as can be seen in the github workflows folder `main.yaml` file. Every time there is a `push` action or `pull request` action to the repository the github workflow is triggered, once the tests are successfully passed the deployment is made to Heroku.

## Functionality

1. Start a web server
2. Create a user

## Local installation

1. Start your Redis database
2. From the root directory of the project, install dependencies and run tests:

```
npm install 
```

```
npm test
```

**12 tests should be passed**


3. Start the application:

```
npm start
```

It will start a web server available in your browser at http://localhost:3000
