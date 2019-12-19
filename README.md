# heroku-cli

heroku cli for project 

## Heroku commands 

### Login to heroku

$ heroku login -i 

### Create a new Git repository
### Initialize a git repository in a new or existing directory

$ cd my-project/

$ git init

$ heroku git:remote -a shop-kart

### Deploy your application

### Commit your code to the repository and deploy it to Heroku using Git.

$ git add .

$ git commit -am "make it better"

$ git push heroku master

### Existing Git repository

### For existing repositories, simply add the heroku remote

$ heroku git:remote -a shop-kart
