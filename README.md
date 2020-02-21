# Laravel Heroku Deployment
A guide for deploying Laravel App from your github repo to Heroku.

### 1.  Create a Procfile
Add a file in your github repo name it as ```Procfile``` and add this code inside your Procfile\
```web: vendor/bin/heroku-php-apache2 public/```
### 2.  Create a New Heroku app
Login into your Heroku account and create a new app.
### 3.  Connect your Github Account to Heroku
Inside your newly created Heroku App to ```Deploy``` tab and at the ```Deployment Method``` section select ```Connect to Github```. (Github authorization will pop-up. Please do allow Heroku to connect on your Github account)
### 4.  Connect Github Repo to Your Heroku App
Still under the ```Deploy``` tab go to ```Connect to Github``` section and search for the repository that you want to connect to your new Heroku app. Just click the ```Connect``` button to connect your selected Github repository.
