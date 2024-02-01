# PREX TEST PHP8 LARAVEL 10
This repository presents the implementation of APIS REST through OAUTH2 and the implementation of the Hexagonal architecture (DDD) in Laravel 10 with php 8.2.12 and Giphy Api


<!--suppress HtmlDeprecatedAttribute -->
<p align="center">
    <img src="https://github.com/JoseAndresTejerina97/aaxisTest/blob/main/public_html/assets/hexagon.jpg?raw=true" alt="hexagon">
</p>

## What's in the environment:

- [Nginx](https://www.nginx.com/)
- [Php Fpm](https://php.net/)
- [Phpmyadmin](https://www.phpmyadmin.net/)
- [Laravel](https://symfony.com/)
- [Mysql](https://www.mysql.com/)

## Prerequisites:

- [Install Docker](https://docs.docker.com/install/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

## How to use:

- Clone the repository
- Enter the repository folder 
- Run the `docker-compose up` command
  - if you want to run in background mode, run the command `docker-compose up -d`

### 🔥 Application execution

1. Enter "prexTest" folder. Install the backend dependencies: `composer install`. 
2. Run command `cp .env.example .env `
3. Create database & tables with `php artisan key:generate` then  `php artisan migrate --seed`

4. Run command `chmod 777 -R storage/*` `chmod 777 -R storage/logs/*`  and  `php artisan passport:install`

5. Access the address `http://localhost` to access the project and `http://localhost/api` for Api endpoints

 Access the address `http://localhost:8080` to access phpmyadmin
  -server prext.mysql
  - user: mysql
  - password: mysql
###  Testing
Run  `php artisan test` 
Feature test

### Doc
See in the docs folder UML diagrams

### POSTMAN COLLECTION

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://god.gw.postman.com/run-collection/17775459-3483b241-03ec-419d-aada-209ec862a0b6?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D17775459-3483b241-03ec-419d-aada-209ec862a0b6%26entityType%3Dcollection%26workspaceId%3Dc88bb1fc-7f13-4fa2-b026-c6f9667f9bf9)

## Comments:
To test the api:
email: andrestejerina97@gmail.com
password: prexTest

## License:

[MIT](https://opensource.org/licenses/MIT)
