# Controle Equipamento

## Atributos

| Atributo       | Tipo        | Descrição                                         |
| -------------- | ----------- | ------------------------------------------------- |
| fora           | boolean     | Flag para se o equipamento esta em alguma tarefa. |
| equipamento_id | Forigen Key | id do equipamento                                 |

## Requisições 

| tipo     | path                                                         | retorno |
| -------- | ------------------------------------------------------------ | ------- |
| **GET**  | /api/controle                                                |         |
| **GET**  | /api/controle_disponiveis                                    |         |
| **GET**  | /api/controle_fora                                           |         |
| **GET**  | /api/controle/<span style="color:blue">:key</span>           |         |
| **GET**  | /api/controle/equipamento/<span style="color:blue">:id</span> |         |
| **POST** | /api/controle                                                |         |
| **PUT**  | /api/controle/<span style="color:blue">:id</span>            |         |

