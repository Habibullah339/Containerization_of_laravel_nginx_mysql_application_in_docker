# Containarization of Lravel nginx mysql in docker using docker compose and Dockerfile.
This projects runs a laravel application on nginx and establish connection with mysql database.
## Step 01
##### Created these files and directories where laravel project files are located
##### 1-docker-compose.yml
##### 2-Dockerfile
##### 3-nginx/default.conf
##### 4-mysql/my.cnf
##### 5-php/local.ini
## Step 02
 Configurations to run PHP NGINX MYSQL using docker compose
`version: '3'
       .
       .
       .
`
## Step 03
Configurations of application in Dockerfile
`
FROM php:8.1-fpm
        .
        . 
        .
`
## Step 04
Nginx configuration setup
`
server {
       .
       .
       .
}     
`
## Step 05
Other files setup in this step.
## Step 06
Edit the `.env` file  env variables to make connection  with mysql
## Step 06
Build using `sudo docker-compose build` command
## Step 07
Running application using `sudo docker-compose up -d`

