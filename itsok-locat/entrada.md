# Entrada

## Atributos

| Atributo             | Tipo         | Descrição                                                    |
| -------------------- | ------------ | ------------------------------------------------------------ |
| centroCusto_id       | integer      | inteiro referente ao id do centro de custo para a entrada de combustivel |
| fornecedor_id        | integer      | inteiro referente ao id da relação Fornecedor                |
| frete                | float        | Valor de frete do combustivel                                |
| numFinal             | float        |                                                              |
| numInicial           | float        |                                                              |
| produto              | string       | Produto de entrada no tanque                                 |
| quantidade           | float        | Quantidade abastecida no tanque                              |
| destino_id           | integer      | Posto de destino da entrada de abastecimento                 |
| refFinal             | float        |                                                              |
| respDestino          | integer      | Responsavel pela entrada no posto                            |
| valorTotal           | float        |                                                              |
| valorUnit            | float        |                                                              |
| justificativa        | string       | Justificativa de modificação na entrada                      |
| respJustificativa_id | integer      | responsavel pela modificação na entrada                      |
| tipoJustificativa    | string       | tipo de justificativa                                        |
| data_entrada         | Utc_datetime | data que foi realizada a entrada                             |
| consistente          | boolean      | Flag para setar se a entrada esta consistente                |
| refInicial           | float        |                                                              |

## Requisições 

