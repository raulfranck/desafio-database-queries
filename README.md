# Database queries challenge

## Detalhes do desafio

Nesse desafio precisei fazer consultas no banco de dados usando TypeORM das seguintes maneiras:

- ORM
- Query Builder
- Raw Query

Partindo de um template, precise aplicar as consultas dentro dos repositórios da aplicação.

A aplicação possui dois modulos: users e games, sendo que um usuário pode ter vários jogos.

## Estrutura do projeto

Para conseguir efeteuar os testes é necessário ter um banco PostgreSQL rodando rodando em um container do docker

Obs: É necessário a instalação do Docker na maquina.

## Tecnologias:

- Node
- Docker
- Jest
- TypeORM
- Postgres

## Como instalar o projeto ?

- git clone ```https://github.com/raulranck/ignite-database-queries.git```

- Navegue até a pasta: ```cd ignite-database-queries```

- Instale usando yarn ou npm: ```yarn```

- Inicie o container do docker com a imagem do postgres: ```docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres```

## Como rodar os testes ?

``` yarn test ``` ou ```npm run test```