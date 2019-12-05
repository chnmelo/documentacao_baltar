# Acesso

## Atributos

| Atributo        | Tipo         | Descrição                                                    |
| --------------- | ------------ | ------------------------------------------------------------ |
| equipamento_id  | Forigen Key  | Id do Equipamento da liberação                               |
| motorista_id    | Forigen Key  | Id do motorista que teve a liberação                         |
| Frentista_id    | Forigen Key  | Id do operador que criou a liberação                         |
| tarefa          | string       | tarefa a ser realizada por essa liberação                    |
| ajudantes_id    | array        | Lista com id de operadores ajudantes a sair com o equipamento |
| previsaoSaida   | Utc_datetime | Data e hora com previsão de saida para a liberação criada    |
| horaSaida       | utc_datetime | Data e hora com saida real do equipamento                    |
| previsaoRetorno | Utc_datetime | Data e hora com previsão de retorno do equipamento           |
| horaRetorno     | Utc_datetime | Data e hora com retorno real do equipamento                  |
| saida           | boolean      | Flag para equipamento ja saiu                                |
| retorno         | boolean      | Flag para equipamento retorno, e finalização da liberação    |

## Requisições

| tipo       | path                                                     | retorno |
| ---------- | -------------------------------------------------------- | ------- |
| **GET**    | /api/acesso                                              |         |
| **GET**    | /api/acesso/<span style="color:blue">:id</span>          |         |
| **GET**    | /api/acontroleDash                                       |         |
| **GET**    | /api/acesso/in/<span style="color:blue">:key</span>      |         |
| **GET**    | /api/acesso/out/<span style="color:blue">:key</span>     |         |
| **GET**    | /api/acesso/inTag/<span style="color:blue">:key</span>   |         |
| **GET**    | /api/acesso/outTag/<span style="color:blue">:key</span>  |         |
| **GET**    | /api/acesso/consult/<span style="color:blue">:key</span> |         |
| **POST**   | /api/acesso                                              |         |
| **DELETE** | /api/acesso/<span style="color:blue">:id</span>          |         |

