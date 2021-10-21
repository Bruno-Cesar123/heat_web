<h1 align="center">NLW Heat - Web</h1>

<p align="center">
  <a href="#-descricao">Descrição</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-demonstracao">Demonstração</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar-backend">Como executar Backend</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar-frontend">Como executar Frontend</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

## Descrição

- Projeto frontend desenvolvido durante a semama NLW da Rocketseat.

> Obs.: Nesse projeto temos autenticação via OAuth usando o GitHub, envios de mensagem em tempo real com o socket.io.

## Demonstração

<img width="900px" alt="home" src="./.github/home.png">
<img width="900px" alt="dashboard" src="./.github/dashboard.png">

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Reactjs](https://pt-br.reactjs.org/)
- [Vite](https://vitejs.dev/)
- [SASS](https://sass-lang.com/)
- [Socket.IO](https://socket.io/)

## 🎲 Como executar Backend

```bash
# Clone este repositório
$ git clone https://github.com/Bruno-Cesar123/heat_server.git

# Acesse a pasta do projeto no terminal/cmd
$ cd server

# Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub

# Instale as dependências
$ npm install ou yarn

# Execute as migrations do Prisma
$ yarn prisma migrate dev

# Execute a aplicação em modo de desenvolvimento
$ $ npm run dev ou yarn dev

# O servidor inciará na porta:4000 - acesse <http://localhost:4000>
```

## 🎲 Como executar Frontend

```bash
# Clone este repositório
$ git clone https://github.com/Bruno-Cesar123/heat_web.git

# Acesse a pasta do projeto no terminal/cmd
$ cd web

# Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub

# Instale as dependências
$ npm install ou yarn

# Execute a aplicação em modo de desenvolvimento
$ $ npm run dev ou yarn dev

# O servidor inciará na porta:3000 - acesse <http://localhost:3000>
```
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](license) para mais detalhes.

---

Feito por **Bruno Cesar** [**LinkedIn**](https://www.linkedin.com/in/bruno-cesar-b0039715a/)