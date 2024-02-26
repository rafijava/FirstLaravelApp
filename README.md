                                            **Laravel 9 Environment Setup**

## We Used...
# Local Server ==>> XAMPP
    After installation go to xampp => php => php.ini => serach gd. ;extension=gd    here, semicolon means comment out and gd means guard. remove ; and save file
# Create a Database named such as webtechnology.

# NodeJS    To check after installation ... Open the command prompt and type => node -v

# Editor ==>> Visual Studio Code / Sublime Text

# Mail Service ==>> mailtrap.io

## Laravel Installation
laravel.com => documentation => version 9.. => Installation via composer and then follow the command....

# Composer ==>> A dependency manager for PHP
getcomposer.org => Download => windows installer => composer-setup.exe
To check using cmd type => composer -v

# In xampp htdocs folder create a new folder named MyFirstProject => Inside search bar write down cmd and hit enter for open command prompt in right path.

# In cmd
...\MyFirstProject> run command line composer installation
Then, from laravel installation via composer run the command within MyFirstProject folder cmd
...\MyFirstProject> composer create-project laravel/laravel FirstLaravelApp

...\MyFirstProject> cd FirstLaravelApp
.
.
.
...\MyFirstProject\FirstLaravelApp> php artisan serve

Copy the laravel development server port and paste it on new tab

Drag and Drop FirstLaravelApp folder in VS Code / Sublime Text Editor

=>php artisan r:l    Here, r = route and l = list



### Important ###
In .env file change the DB_DATABASE=..... such as webtechnology

### BUGS ###
Vite manifest not found ...

In cmd
=>npm install --save-dev vite laravel-vite-plugin
Then we need to update our package.json file
"scripts":{"dev": "vite",
            "build": "vite build",
            and so on...}
=> npm run build

In addition, Within package.json file change dev Dependencies
"laravel-vite-plugin": "^0.8.1",
"vite": "^4.5.2"





