## Docker Laravel Vue SSR with phpV8Js


### Config docker compose

- git clone https://github.com/sutin1234/docker-laravel-vue-ssr.git
- cd website folder
- clone laravel repository
- cp .env-example.env ==> config .env
- replace content of laravel into website
- run composer install
- php artisan preset vue
- npm install & npm run dev


### setup docker compose
- change environment in docker-compose.yml

### start docker
- docker-compose up -d

### run laravel
http://localhost/public

### run phpmyadmin
http://localhost:8888
