# Teacher: Sandro Giacomozzi - Software engineer, TOTVS

# DESCRIÇÃO
Neste projeto você terá o desafio de desenvolver um conjunto de API’s utilizando Spring Boot para controlar um estacionamento de veículos. Serão controlados a entrada, saída e valor a ser cobrado do cliente. Iremos aplicar todas as boas práticas de desenvolvimento de API’s incluindo segurança com Spring Security e acesso a banco de dados PostgreSQL. Serão realizados testes e relatórios de cobertura de testes. Após finalizarmos a aplicação e termos enviado para o Github, vamos fazer o deploy na cloud do Heroku a fim de disponibilizar nossa API para a Internet.


# cloud-parking

## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

## Stop database
docker stop parking-db

## Start database
docker start parking-db
