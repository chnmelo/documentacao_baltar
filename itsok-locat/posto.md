# Posto

## Atributos

| Atributo     | Tipo    | Descrição                                  |
| ------------ | ------- | ------------------------------------------ |
| nomeFantasia | string  | Nome de referencai do posto                |
| tipo         | string  | tipo de posto (movel, fixo, ...)           |
| cnpj         | string  | cnpj do posto                              |
| endereco     | string  | Endereço do posto                          |
| responsavel  | string  | responsavel pelo posto                     |
| telContato   | string  | Telefone de contato do posto               |
| modeloTanque | integer | Chave do modelo do tanque que tem no posto |
| observacao   | string  | observação                                 |
| produto      | string  | que tipo de produto este posto fornece     |

## Requisições 

| tipo       | path                                                         | retorno |
| ---------- | ------------------------------------------------------------ | ------- |
| **GET**    | /api/postoAbastecimento                                      |         |
| **GET**    | /api/postoAbastecimento/<span style="color:blue">:id</span>  |         |
| **GET**    | /api/postoAbastecimento/cnpj/<span style="color:blue">:cnpj</span> |         |
| **POST**   | /api/postoAbastecimento                                      |         |
| **PUT**    | /api/postoAbastecimento/<span style="color:blue">:id</span>  |         |
| **DELETE** | /api/postoAbastecimento/<span style="color:blue">:id</span>  |         |

