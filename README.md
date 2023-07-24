# ecommerce-teste
Projeto de e-commerce

## Tecnologias utilizadas

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- React: Components, Props, Events, Hooks, Router, Axios
- Context API: Store, Reducers, Actions
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: Babel, Git, Github,

## Rodando o projeto localmente

### 1. Instalar o MongoDB

- Local MongoDB
  - Instale a partir daqui [here](https://www.mongodb.com/try/download/community)
  - Configuação do arquivo .env MONGODB_URI=mongodb://localhost/amazona

### 2. Rodar Backend

```
$ cd backend
$ npm install
$ npm start
```

### 3. Rodar Frontend

```
$ cd frontend
$ npm install
$ npm start
```

### 4. Checar usuários e produtos

- Abra no browser: http://localhost:4000/api/seed 
- A porta pode mudar, verifique no log de inicialização qual a porta utilizada

### 7. Admin Login

- Acesse http://localhost:3000/signin
- Entre com usuário e senha, que pode ser cadastrado

### 8. Sandbox Paypal
Esse projeto usa o Sandbox Paypal para teste de compras, o cadastro pode ser feito [aqui](https://developer.paypal.com/tools/sandbox/accounts/)

