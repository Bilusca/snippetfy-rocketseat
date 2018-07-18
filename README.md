# Aplicação construída com base no curso de Node.JS da RocketSeat

A aplicação, feita em Node, serve para armazernar snippets de código.
A aplicação aborda todos os aspectos simples de um back-end, Usando o Sequelize como ORM, e fazendo conexão com bancos SQL.

## Configurando

Para ver em funcionamento, dê um `$ git clone` neste projeto, depois rode

```
$ npm install
```

Para configurar o banco, primeiro deve-se criar um banco de dados e fazer a conexão por meio do arquivo localizado em `config/database.js`.
Algumas `migrations` já estão criadas, para rodalas basta usar

```
$ node_modules/.bin/sequelize db:migrate
```

Depois de tudo pronto, basta usar

```
$ npm start
```
