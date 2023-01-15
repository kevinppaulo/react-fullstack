# react-fullstack

Este projeto é desenvolvido com React no frontend e Spring Boot no backend. Utiliza React Router para gerenciamento de rotas e Redux para gerenciamento de estado. O backend utiliza Spring Data REST Repositories para acesso ao banco de dados. Nginx é utilizado para roteamento de requisições. O projeto está implantado com Docker para facilitar o deploy.

## Acesso ao App

Para acessar o app, visite: <https://react-fullstack.kevinpaulo.tech/>

## Requisitos
- Node.js
- Java 17
- Docker
- Nginx

## Instalação

1. Clone este repositório
2. Entre na pasta do projeto: `cd react-fullstack`
3. Entre na pasta do frontend: `cd student-crud-frontend`
4. Execute `npm install` para instalar as dependências do frontend
5. Execute `npm run build` para construir o projeto
6. Entre na pasta api: `cd ../student-crud-api`
7. Execute `./gradlew build` para construir o projeto no backend
8. Entre na pasta raiz do projeto: `cd ..`
9. Execute `docker-compose up` para iniciar o projeto
10. Acesse `http://localhost` no seu navegador

