# Laravel 9 & Vue 3 

The Docker include:

- Laravel 9
- Vue.js 3
- MySql
- PHP8.2
- Node
- Nginx
- Reddis

## Installation

- Clone this repository 
- Copy `.env` file: `cp .env.example .env`
- Set the environment variables in `.env` file
- Run command: `docker-compose up --build -d`
-  Run the container in bash mode: `docker exec -it ppro_app /bin/sh`
- Inside this container now you can run all the commands as if if you are on local environment:
- Install composer dependencies: `composer install`
- Generate key: `php artisan key:generate`
- Run migration: `php artisan migrate`
- Run seeder: `php artisan db:seed`
- Install javascript: `npm`
- Install javascript: `npm install`
- Compile the assets: `yarn dev` / `yarn watch`  / `dcoker-compose run npm run dev`
- You can access the project at: `http://localhost:8000`
- or
- Install composer dependencies: `docker-compose run php composer install`
- Install javascript dependencies: `docker-compose run npm install`
