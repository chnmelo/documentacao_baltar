# Pessoa

## Atributos

| Atributo | tipo   | Descrição                                                    |
| -------- | ------ | ------------------------------------------------------------ |
| birthday | date   | Contém data de aniversario da pessoa                         |
| cpf      | string | Contém CPF da pessoa                                         |
| nome     | object | Contém nome da pessoa: {"Primeiro":<value>, "Ultimo":<value>} |
| phone    | string | Contém telefone de contato da pessoa                         |
| rg       | string | Contém numero de RG da pessoa                                |



## Requisições

| tipo     | path                                | retorno |
| -------- | ----------------------------------- | ------- |
| **GET**  | /api/pessoa                         |         |
| **GET**  | /api/pessoa/<id>                    |         |
| **GET**  | /api/pessoa/cpf/<cpf>               |         |
| **GET**  | /api/pessoa/uid/<uid>               |         |
| **GET**  | /api/pessoa/key/<key>               |         |
| **GET**  | /api/pessoa/acesso/<key>/<local_id> |         |
| **PUT**  | /api/pessoa/<id>                    |         |
| **POST** | /api/pessoa                         |         |

