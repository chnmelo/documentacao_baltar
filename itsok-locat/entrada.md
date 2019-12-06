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

| tipo       | path                                                         | retorno |
| ---------- | ------------------------------------------------------------ | ------- |
| **GET**    | /api/entrada                                                 |         |
| **GET**    | /api/entrada/notify                                          |         |
| **GET**    | /api/entrada/<span style="color:blue">:id</span>             |         |
| **POST**   | /api/entrada                                                 |         |
| **POST**   | /api/entrada/justificar                                      |         |
| **PUT**    | /api/entrada/<span style="color:blue">:id</span>             |         |
| **DELETE** | /api/entrada/<span style="color:blue">:id</span>             |         |
| **GET**    | /api/reviews/entrada/empresa/<span style="color:blue">:empresa</span>/<span style="color:blue">:data_inicial</span>/<span style="color:blue">:data_final</span> |         |
| **GET**    | /api/reviews/entrada/postoAbastecimento/<span style="color:blue">:posto</span>/<span style="color:blue">:data_inicial</span>/<span style="color:blue">:data_final</span> |         |

