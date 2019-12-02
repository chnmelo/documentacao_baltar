# Sessão

## Atributos

| Atributo    | Tipo         | Descrição                          |
| ----------- | ------------ | ---------------------------------- |
| config      | string       | Token dos dados do acesso          |
| publicToken | string       | Token publica fornecida ao usuario |
| data_login  | utc_datetime | Data e hora da criação do acesso   |
| uid         | string       | Token do google firebase           |
| usuario     | Forigen key  | id do usuario que criou o acesso   |



## Requisições 

| tipo     | path              | retorno |
| -------- | ----------------- | ------- |
| **GET**  | /api/session/<tk> |         |
| **POST** | /api/session      |         |

