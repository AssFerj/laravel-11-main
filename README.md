
# Laravel 11 - Arquivo base com docker

## Subir os containers do projeto

`sudo docker-compose up -d`

## Criar o arquivo .env

`cp .env.example .env`

## Acessar o container app

`sudo docker-compose exec app bash`

## Instalar as dependências do projeto

`composer install`
