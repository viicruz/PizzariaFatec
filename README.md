# Servidor de Pizza

## Descrição do Projeto

Trabalho desenvolvido para a matéria do professor Eduardo.

## Como rodar a aplicação

No diretório do projeto, você pode executar:

`yarn install` ou `npm install` para instalar todas as depêndencias do projeto.

`npm/yarn prisma db push` para criar o banco de dados. Por padrão, o banco de dados é criado em um arquivo SQLite no diretório `./prisma/dev.db`.

`npm/yarn dev` para executar o servidor em modo de desenvolvimento. A aplicação estará disponível em [http://localhost:3333](http://localhost:3333).

Para executar os testes, você pode usar `npm/yarn test` ou `npm/yarn test:watch` para executar os testes em modo de observação.

Também é possível testar todas as rotas da API, para isso, com o servidor rodando, use `npm/yarn api-test` para executar os testes da API.
