# Get Started 

This is a quick intro into how we got started in Part 1, so you can get the project working and ready to hack on.

## Check Requirements
Check your version of PHP (you'll need PHP 7.1.3 or higher): 
```php -v```

Make sure you have git installed on your machine:
```git -v```

Install or update Compoer (use the latest version, currently: 1.8.5):
https://getcomposer.org/download/
or
https://pilsniak.com/install-composer-mac-os/
and uninstalling (e.g. old versions):
https://stackoverflow.com/questions/30396451/remove-composer/30399584

## If you want to play around with the rough app.

### Clone this repo

Navigate to the directory on your system where you want to place the repo. Then enter the following command:
```git clone https://github.com/madisonphp/madtodos.git```

Navigate into the project directory:
```cd madtodos```

### Install the dependencies via Composer

Run:
```composer install```

### See the project working

Start the webserver by running:
```./bin/console server:run```

Go to the website in the respones, typically:
http://127.0.0.1:8000


### See all the cool stuff you can add to the project
In the madtodos directory run:
```php ./bin/console```

## If you want to add to this project

Click the "Fork" logo in the upper right of github. Select your github user from the popup. 

## Clone your fork of this repo to your local machine
Navigate to the directory on your system where you want to place the repo. Then enter the following command, filling in your user name for "USERNAME":
```git clone https://github.com/USERNAME/madtodos.git``` 

Update your local "upstream" remote branche to point at our group's original repo, so you can pull in the group's updates: 
```git remote add upstream https://github.com/madisonphp/madtodos```

## Create a feature branch for your work
In the local git directory for your fork, create a new branch, name it (example: feature/addDeleteButton) and check it out:
```git checkout -b feature/addDeleteButton```

Make changes.
Stage the changes, replacing FILE1, FILE2, etc. with the names of the actual files you want to add:
```git add FILE1 FILE2```

Commit changes and add a commit message:
```git commit -m "Add delete button"```  

Push commit to your fork's remote:
```git push```

## Ask to have your code added (Making a Pull Request)
Go to the pull request tab of the group's original repository:
https://github.com/madisonphp/madtodos/pulls

Click on the "New pull request" button on the right. Follow the directions on the next screen.