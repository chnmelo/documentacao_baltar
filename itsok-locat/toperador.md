# Tag Operador

## Atributos

| Atributo    | Tipo        | Descrição                 |
| ----------- | ----------- | ------------------------- |
| operador_id | Forigen Key | Chave da Relação operador |
| key         | string      | ID da tag                 |

## Requisições 

| tipo       | path                                                      | retorno |
| ---------- | --------------------------------------------------------- | ------- |
| **GET**    | /api/tagOperador                                          |         |
| **GET**    | /api/tagOperador_null                                     |         |
| **GET**    | /api/tagOperador/<span style="color:blue">:id</span>      |         |
| **GET**    | /api/tagOperador/key/<span style="color:blue">:key</span> |         |
| **POST**   | /api/tagOperador                                          |         |
| **PUT**    | /api/tagOperador/<span style="color:blue">:id</span>      |         |
| **DELETE** | /api/tagOperador/<span style="color:blue">:id</span>      |         |

