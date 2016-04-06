# Deploying a Mean App

## Learning Objectives

- Understand the steps to deploy a MEAN stack app
- Determine how to specific development mongodb vs. production
- Use Heroku logs to address deployment errors
- Explain the use of Procfile
- Introduce other deployment options such as Digital Ocean


## Framing (5 mins)

At this point, you have deployed a few apps throughout the program. But, most (if not all) have been applications with a Rails backend. Heroku makes deploying a Rails app easy (right?). Minus a few complications, all it takes is `heroku create`, `git push heroku master`, and `heroku run rake db:migrate`. As long as your app is working locally, is should typically work in production.
MEAN apps require a little more work to deploy, as there is less "magic" built in compared to Rails. 
