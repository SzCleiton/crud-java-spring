# Simple CRUD
This repository contains a simple CRUD project built using Java Spring. The aim of this repository is to practice and share how you can build all CRUD Methods using Java Spring.

## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [API Endpoints](#api-endpoints)
- [Database](#database)

## Installation

1. Clone the repository:

```bash
$ git clone https://github.com/SzCleiton/crud-java-spring.git
```

2. Install dependencies with Maven

## Usage

1. Start the application with Maven
2. The API will be accessible at http://localhost:8080


## API Endpoints
The API provides the following endpoints:

```markdown
GET /product - Retrieve a list of all data.

POST /product - Register a new data.

PUT /product - Alter data.

DELETE /product/{id} - Inactivate data.
```

## Database
The project uses PostgresSQL as the database. The necessary database migrations are managed using Flyway.

To install PostgresSQL locally you can [click here](https://www.postgresql.org/download/).

## Docker

You can run this project with Docker by running the following command:


```bash
$ docker-compose up
```
Run the application and access http://localhost:15432

Enter the email and password configured in [Docker file](./docker-compose.yml).

To install Docker locally you can [click here](https://www.docker.com/products/docker-desktop/).







## Translated:

# CRUD simples
Este repositório contém um projeto CRUD simples construído usando Java Spring. O objetivo deste repositório é praticar e compartilhar como você pode construir todos os métodos CRUD usando Java Spring.

## Índice

- [Instalação](#instalação)
- [Configuração](#configuração)
- [Pontos finais da API](#pontos finais da API)
- [Banco de dados](#banco de dados)

## Instalação

1. Clone o repositório:

```bash
$ git clone https://github.com/SzCleiton/crud-java-spring.git
```

2. Instale dependências com Maven

## Uso

1. Inicie o aplicativo com Maven
2. A API estará acessível em http://localhost:8080


## Terminais de API
A API fornece os seguintes endpoints:

```redução
GET /product – Recupera uma lista de todos os dados.

POST /produto - Cadastre um novo dado.

PUT /produto - Altera dados.

DELETE /product/{id} - Inativa dados.
```

## Base de dados
O projeto usa PostgresSQL como banco de dados. As migrações de banco de dados necessárias são gerenciadas usando Flyway.

Para instalar o PostgresSQL localmente você pode [clicar aqui](https://www.postgresql.org/download/).

## Docker

Você pode executar este projeto com Docker executando o seguinte comando:


```bash
$ docker-compose up
```
Execute a aplicação e acesse http://localhost:15432

Digite o e-mail e a senha configurados em [arquivo Docker](./docker-compose.yml).

Para instalar o Docker localmente você pode [clicar aqui](https://www.docker.com/products/docker-desktop/).