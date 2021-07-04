> **Mantenedor:** [Alan Christian](https://github.com/alangeek)

## Índice

- [Como funciona?](#como-funciona)
- [Primeiros passos](#primeiros-passos)

- [Licença](#licena)

## Primeiros passos

Pré-requisitos: Instale o [Git](http://git-scm.com/downloads) e o [NodeJS](http://nodejs.org/download/), caso você não os tenha ainda.

1. Instale [Git](http://git-scm.com/downloads) e [NodeJS](http://nodejs.org/download/), caso você não os tenha ainda.

2. Clone o repositório:

   ```sh
   $ git clone git://github.com/braziljs/conf-boilerplate.git
   ```

3. Vá para pasta do projeto:

   ```sh
   $ cd node-new
   ```

4. Instale todas as dependências:

   ```sh
   $ yarn install
   ```

5. Iniciar & Monitorar com nodemon watch mode do typescript:

   ```sh
   $ yarn start-dev
   ```

   Agora você irá ver o site rodando em `localhost` :D

## Estrutura

A estrutura básica do projeto se dá na seguinte forma:

```
.
|-- dist/
|   |-- indexjs
|-- src/
|   |-- index.ts
|-- .gitignore
|-- comands.txt
|-- package.json
|-- README.md
|-- tsconfgi.json
|-- yarn.lock
```

## Licença

[MIT License](http://braziljs.mit-license.org/) © pdp
