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

