# Sessão

## Atributos

| Atributo     | Tipo    | Descrição                            |
| ------------ | ------- | ------------------------------------ |
| idUser       | integer | Chave de usuario que criou a sessão. |
| sessionToken | string  | Token privada de sessão.             |
| publicToken  | string  | Token publica do usuario.            |
| browser      | string  | browser de acesso.                   |

## Requisições 

| tipo     | path                                               | retorno |
| -------- | -------------------------------------------------- | ------- |
| **GET**  | /api/isauth/<span style="color:blue">:token</span> |         |
| **GET**  | /api/unauth/<span style="color:blue">:token</span> |         |
| **POST** | /api/auth                                          |         |

