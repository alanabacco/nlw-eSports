# NLW eSports - Server

## 💻 Sobre o projeto

Esse é o projeto Server que foi desenvolvido durante o NLW eSports da [Rocketseat](https://rocketseat.com.br/).

<!-- ### Funcionalidades -->

## 🛠️ Ferramentas e tecnologias utilizadas

- [Nodejs](https://nodejs.org/en/about/)
- [Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [SQLite](https://www.sqlite.org/index.html)
- [VS Code](https://code.visualstudio.com/)

## 🔥 Como executar o projeto localmente

Para executar o projeto de maneira local, execute os comandos:

```
> git clone https://github.com/alanabacco/nlw-eSports
> cd nlw-eSports
> cd server
> npm install
> npm run dev
```

## 🦶 Passo a passo da criação do projeto

- npm init -y
- npm install express
- pra rodar - npm src/server.mjs
- instalar typescript p/ desenvolvimento - npm i typescript -D
- criar arquivo de config p/ typescript - npx tsc --init
- instalar pacote typescript pra express - npm i @types/express -D
- instalar npm i ts-node-dev -D
- instalar npm i prisma -D
- npx prisma init --datasource-provider SQLite
- npx prisma migrate dev
- npx prisma studio -> interface gráfica pra visualizar o bd
- npm i @prisma/client
- npm i cors
- npm i @types/cors -D

<!-- - compilar projeto `npm run build`
- executar projeto `node build/server.js` -->

- rodar projeto `npm run dev`

<!-- ECMAscript Modules -->

### Notas

Na comunicação backend/frontend conseguimos trabalhar com tipos de parametros

- Query: vem através do ponto de interrogação
  - usado quando queremos persistir estado (coisas não sensíveis)
  - são nomeados
- Route: também da url
  - mas não são nomeados
  - usado geralmente quando quer fazer uma idetificação de um recurso
- Body: quando enviamos várias informações numa unica requisição
- geralmente pra envio de formulário
- mais recomendado pra informações sensíveis

---

Desenvolvido por [Alana Bacco](https://github.com/alanabacco). <br />
[![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/alana-bacco/)](https://www.linkedin.com/in/alana-bacco/)
