<h1 align=center> 🚀 Middleware Challenge </h1>


## 💻 Descrição

Desafio para bootcamp Node.JS lecionado pela Rocketseat. Nesse exercício foi necessário desenvolver middlewares para validar rotas de uma aplicação. 
A validação das rotas será feita em um app de todo no qual os usuários cadastrados no plano pro tem uma quantidade ilimitada de postagem e usuário normais só podem cadastrar até 10 todos

## 🛠️ Teste
- [x] Should be able to find user by username in header and pass it to request.user
- [x] Should not be able to find a non existing user by username in header
- [x] Should be able to let user create a new todo when is in free plan and have less than ten todos
- [x] Should not be able to let user create a new todo when is not Pro and already have ten todos
- [x] Should be able to let user create infinite new todos when is in Pro plan
- [x] Should be able to put user and todo in request when both exits
- [x] Should not be able to put user and todo in request when user does not exists
- [x] Should not be able to put user and todo in request when todo id is not uuid
- [x] Should not be able to put user and todo in request when todo does not exists
- [x] Should be able to find user by id route param and pass it to request.user
- [x] Should not be able to pass user to request.user when it does not exists

## ⭐ Clonando e rodando
```
$ git clone https://github.com/HenriqueGMen/middlewares-nodeJS.git
```

```
#install the dependencies
$ yarn
#start the server
$ yarn dev
```

### Visite meu linkedin:
  <a href="https://www.linkedin.com/in/carlos-henrique-gomes-mendon%C3%A7a-8614aa93/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;&nbsp;
