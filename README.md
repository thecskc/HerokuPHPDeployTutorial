# Deploying PHP apps on Heroku
Here's how you deploy a PHP app on Heroku easily. 



### 1)Add a composer.json file
In the main folder of your project, add a "composer.json" file whose contents look like this:

    {

    }

That's right, it's completely empty. This is to let Heroku know that it is handling a PHP app. 

### 2) Add a "Procfile"

Create another file and name it "Procfile". NO EXTENSIONS. JUST "Procfile". 

It's contents are as follows:

    web: vendor/bin/heroku-php-apache2

### 3) Add an index.php file

This file will be automatically run when Heroku runs your PHP app. 

### 4) Connect to Heroku

You can now open Heroku, connect your Heroku app to your respective GitHub repository and deploy the app. 

### NOTE: If you need to add any dependencies, do so in the composer.json file. 

## THE APP IS NOW LIVE!

