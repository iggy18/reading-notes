## heroku

- prepare the application
- git clone the repository
- type in `heroku create`
- When you create an app, a git remote (called heroku) is also created and associated with your local git repository.
- type in `git push heroku main`
- the application is now deployed. check to make sure at least one instance is running.
- type in `heroku ps:scale web-1`
- visit the app at the URL generated
- typein `heroku open`
- check your logs by typing in `heroku logs --tail`

I've installed and deployed an app on heroku
