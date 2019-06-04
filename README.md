# scriptLaravel

scriptLaravel

This script will install any cloned laravel project.

What it does :
   - creates a database if needed, or use an existing one (created prior to the install)
   - prepares the .env file
   - installs composer
   - installs NPM packages
   - generates app key
   - launches migrations and seeds
   - launches npm run production to compile js and css
   - launches server

How to use it:
- copy the script in your project folder
- run it by typing in your project folder from your terminal : ./install-laravel