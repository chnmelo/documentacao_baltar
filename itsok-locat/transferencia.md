# Transferencia

## Atributos

| Atribtuo             | tipo         | Descrição                                           |
| -------------------- | ------------ | --------------------------------------------------- |
| centroCusto_id       | integer      | Chave da relação centro de custo                    |
| consistente          | boolean      | Flag para se a transferencia esta consistente       |
| destino_id           | integer      | Chave da relação Posto                              |
| fornecedor_id        | integer      | Chave da relação Posto                              |
| justificativa        | string       | Texto de justificate de alterações na transferencia |
| respJustificativa_id | integer      | Responsavel pela alteração                          |
| tipoJustificativa    | string       | Tipo de alteração                                   |
| refFinal             | float        |                                                     |
| refInicial           | float        |                                                     |
| quantidade           | float        | Quantidade de combustivel transferido               |
| data_transferencia   | utc_datetime | Data de transferencia                               |
| respFornecimento     | integer      | Chave da relação Operador                           |
| respDestino          | integer      | Chave da relação Operador                           |
| produto              | string       | Produto transferido                                 |

## Requisições 

