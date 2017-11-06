# heroku-never-sleep

Small script to prevent a Heroku application from sleeping.

### Deploy on Heroku

* Create an account to [Heroku](https://www.heroku.com/)
* Follow this [tutorial](https://devcenter.heroku.com/articles/getting-started-with-ruby#introduction) to deploy on Heroku
* Follow this [tutorial](https://devcenter.heroku.com/articles/config-vars) to add environment variable to Heroku. You can also use [Figaro](https://github.com/laserlemon/figaro)
    * Define which URLs you want to keep awake with `URLs` variable
* Follow this [tutorial](https://devcenter.heroku.com/articles/scheduler) to add a scheduled jobs on your app. I recommend running the application every 10 minutes
