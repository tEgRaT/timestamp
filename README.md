# This is a simple RESTful API called Timestamp Microservice of freeCodeCamp
1. npm install -g express-generator
2. express TimeStampMicroService
3. cd TimeStampMicroService
4. npm install, this will install all the dependencies described in package.json
5. git init
6. create a new file called .gitignore, add node_modules to this file
7. git add .
8. git commit -m "initial commit"
9. unstall modules won't used in this project: npm uninstall --save body-parser cookie-parser serve-favicon jade, don't forget to install pug instead of jade
10. do some coding
11. npm start
Steps to deploy to heroku:
1. go to https://toolbelt.heroku.com and download
2. edit package.json, add "engines" property
3. create a new file called Procfile in the root directory of this project, tell heroku how to run your application: web: node ./bin/www
4. git commit -m 'configure for deployment'
5. heroku login
6. heroku create tegrattimestamp(your project name on heroku)
7. git push heroku master
8. done!