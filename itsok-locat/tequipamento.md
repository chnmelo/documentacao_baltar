# Tag Equipamento

## Atributos

| Atributo       | Tipo        | Descrição                    |
| -------------- | ----------- | ---------------------------- |
| equipamento_id | Forigen Key | Chave da Relação equipamento |
| key            | string      | ID da tag                    |

## Requisições 

| tipo       | path                                                         | retorno |
| ---------- | ------------------------------------------------------------ | ------- |
| **GET**    | /api/tagEquipamento                                          |         |
| **GET**    | /api/tagEquipamento_null                                     |         |
| **GET**    | /api/tagEquipamento/<span style="color:blue">:id</span>      |         |
| **GET**    | /api/tagEquipamento/key/<span style="color:blue">:key</span> |         |
| **POST**   | /api/tagEquipamento                                          |         |
| **PUT**    | /api/tagEquipamento/<span style="color:blue">:id</span>      |         |
| **DELETE** | /api/tagEquipamento/<span style="color:blue">:id</span>      |         |

