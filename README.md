https://scotch.io/tutorials/how-to-deploy-a-node-js-app-to-heroku


To do:
Using a Current Heroku App

If you switch to a different computer and want to access an already existing project. The steps are simple.

Download the Heroku Toolbelt
Login: heroku login
Add your public key: heroku keys:add
Pull down your current application heroku git:clone -a app-name
Make your improvements
Git add and commit your changes
Push back to heroku: git push heroku master

With these simple steps, you can jump onto any computer and immediately grab your current projects.

End To do