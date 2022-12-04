# LaravelRestDocker
## Clone repo
## Start docker
```
cd laravelApp
```
```
./vendor/bin/sail up
```
## Migrate database
### Option 1
  1) Go to http://0.0.0.0/api/accounts
  2) You will see a error, press RUN MIGRATION and refresh the page
### Option 2 (using docker dekstop)
  1) Go to the laravelApp container
  2) Open the shell of laravel.test-1 (Image: sail-8.1/app:latest)
  3) Run ``` php artisan migrate ```
 
