# Controle Operador

## Atributos

| Atributo    | Tipo        | Descrição                                      |
| ----------- | ----------- | ---------------------------------------------- |
| fora        | boolean     | Flag para se o operador esta em alguma tarefa. |
| operador_id | Forigen Key | id do operador                                 |

## Requisições 

| tipo     | path                                                       | retorno |
| -------- | ---------------------------------------------------------- | ------- |
| **GET**  | /api/controleOperador                                      |         |
| **GET**  | /api/controleOperadorLiberado                              |         |
| **GET**  | /api/controleOperador/<span style="color:blue">:key</span> |         |
| **POST** | /api/controleOperador                                      |         |

