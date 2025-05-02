# Desafio MV

Este projeto é composto por um backend em Java (Spring Boot) e um frontend em Angular. O objetivo é fornecer uma aplicação completa com API REST documentada via Swagger e interface web para uso.

## 🔧 Tecnologias Utilizadas

- **Backend:** Java 17, Spring Boot, Maven, PostgreSQL
- **Frontend:** Angular, TypeScript, HTML/CSS
- **Documentação da API:** Swagger
- **Gerenciamento de containers:** Docker + Docker Compose

## 🚀 Como rodar o projeto localmente

Siga os passos abaixo para executar o projeto localmente:

```bash
git clone https://github.com/seu-usuario/desafiomv.git
cd desafiomv

cd desafiomv-backend
mvn clean package
cd ..

cd desafiomv-frontend
npm install
cd ..

docker compose build
docker compose up
```

## Acesse o site
http://localhost:4200/

## Api local para fazer chamadas
http://localhost:8080

## Acesse a documentação

https://desafio-production.up.railway.app/swagger-ui/index.html
