# mean-app
Experimenting with MEAN Web Development using MongoDB, Express, AngularJS and Node.js

### Start app
- sudo service mongod restart
- node server

### Run Unit Tests
- npm install -g karma-cli
- NODE_ENV=test karma start

### Run E2E Tests
- npm install -g protractor
- webdriver-manager update
- NODE_ENV=test node server
- protractor