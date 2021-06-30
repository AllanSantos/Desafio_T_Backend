# Desafio_T_Backend

## Tecnologias utilizadas:

- **Express**  
- **Cors**
- **Mongoose**
- **Axios**
- **Banco MongoDB**
- **Material-UI**
- **JWT**
- **bcryptjs**
- **moment**
- **yup**
- **sequelize**
- **nodemon**


## Comandos Projeto
- Rodar comando yarn(tanto no front quanto no back)
  > Para baixar as dependecias.

- Rodando servidor yarn dev
  > Para iniciar o servidor NodeJS.

## Ajustes
- Criar e ajustar o arquivo .env com os dados do mongoDB, Secret e ExpireIn do JWT
- Modelo do .ENV:

  ~~~JSON
  # mongo
  MONGO_URL=mongodb+srv://admin:<password>@cluster0.upjrq.mongodb.net/myFirstDatabase?retryWrites=true&w=majority

  # jwt
  APP_SECRET=''
  EXPIRE_IN=7d
  ~~~

## API's
Foram criadas 5 rotas na aplicação, que são:

  - **post('/signUp') :** Criação de usuario.
  - **post('/sessions') :** Gerar Token JWT.
  - **post('/client') :** Cadastro de cliente.
  - **get('/clients') :** Retorno de todos os clientes inadimplentes.
 
