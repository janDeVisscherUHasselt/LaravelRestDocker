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
 
## phpMyAdmin
  1) Go to http://localhost:8001
  2) Go to laravelApp -> Accounts
  3) Insert
  4) Give id: 1, name: Jan, saldo: 100 -> Press GO
## Open the consumer
  1) ```cd frontend ```
  2) Open home.html
