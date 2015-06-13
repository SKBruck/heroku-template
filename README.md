# Instructions - Testing Websites with Heroku

This repo contains the files needed to test my websites locally and online. To begin:

1. Create a repo for the project (w/ a readme and node .gitignore)
2. Clone the repo to local directory
3. Copy index.js, package.json, and public into the local directory
4. Run `npm install` to install express
5. Commit the changes

**Project files should be created in/added to the public directory**

## To Test Static Files Locally

1. Run `npm start`
2. Navigate to localhost:5000/filename.html

## To Deploy to Heroku to Test/Share Site

1. Run `heroku create [APP-NAME]` to put the app on heroku
2. Run `git push heroku`
3. Navigate to https://app-name.herokuapp.com/