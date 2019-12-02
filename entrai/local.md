# Local

## Atributos

| Atributo    | Tipo   | Descrição                                           |
| ----------- | ------ | --------------------------------------------------- |
| cnpj        | string | Contém o cnpj da empresa proprietária do local      |
| endereço    | string | Contém o endereço do local                          |
| nome        | string | Contém o nome reservado ao local                    |
| phone       | string | Contém um telefone de contato do local.             |
| tipo        | string | Determina o tipo do local                           |
| descricao   | string | Contém uma descrição a respeito do local            |
| crpt        | string | Contém a cripito de entrada do local                |
| calendar_id | string | Contém o id do calendario fornecido pelo google api |

# Requisições

| tipo     | path                   | retorno |
| -------- | ---------------------- | ------- |
| **GET**  | /api/local             |         |
| **GET**  | /api/local/crpt/<crpt> |         |
| **GET**  | /api/local/<id>        |         |
| **PUT**  | /api/local/<id>        |         |
| **POST** | /api/local             |         |

