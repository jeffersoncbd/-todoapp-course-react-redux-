<p align="center">
  <img src="https://raw.githubusercontent.com/jeffersoncbd/todoapp-course-react-redux/master/screen.jpg" width="600">
</p>

# TODOAPP

Este aplicativo foi criado seguindo os passos [deste curso](https://www.udemy.com/course/react-redux-pt) da [Udemy](https://www.udemy.com).
O meu objetivo com ele era aprender os conceitos básicos de [Redux](https://redux.js.org/), mas resolvi implementar ReactHooks (que não estão no curso) e no final acabou se tornando um belo app feito com [Material-ui](https://material-ui.com/).

## Como testar
1. Execute `yarn` dentro das pastas: backend e frontend
2. Copie o arquivo .env.example (que está dentro de backend) renomeando para .env e adicione as informações necessárias no novo arquivo (a porta de sua escolha e os dados de acesso à um banco mongodb - recomendo o [MongoDB Atlas](https://cloud.mongodb.com/user#/atlas/login))
3. Execute `yarn dev` na pasta backend e deixe rodando.
4. Edite o arquivo `frontend/src/services/api.js` adicionando a URL do backend.
5. Execute `yarn start` na pasta frontend.

## Package.json
### Backend
```js
{
  "cors": "^2.8.5",
  "dotenv": "^8.2.0",
  "express": "^4.17.1",
  "mongoose": "^5.8.9",
  "node-restful": "^0.2.6"
}
```

### Frontend
```js
{
  "@material-ui/core": "^4.9.0",
  "@material-ui/icons": "^4.5.1",
  "axios": "^0.19.2",
  "react": "^16.12.0",
  "react-redux": "^7.1.3",
  "redux": "^4.0.5",
  "redux-multi": "^0.1.12",
  "redux-promise": "^0.6.0",
  "redux-thunk": "^2.3.0"
}
```
