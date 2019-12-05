# Centro de Custo

# Atributos

| Atributo     | Tipo        | Descrição                                               |
| ------------ | ----------- | ------------------------------------------------------- |
| telContato   | String      | Contém telefone de contato do centro de custo           |
| nomeFantasia | string      | Contém nome do centro de custo                          |
| endereco     | strgin      | Contém endereço do centro de custo                      |
| cidade       | string      | Contém cidade onde o centro de custo esta localizado    |
| estado       | string      | Contem estado em que o centro de custoa esta localizado |
| responsavel  | string      | Contém o nome do responsavel pelo centro de custo       |
| observacao   | string      | Contém uma observação a respeito do centro de custo     |
| empresa_id   | Forigen Key | contem id da empresa responsavel pelo centro de custo   |

## Requisições

| tipo       | path                                                 | Descrição |
| ---------- | ---------------------------------------------------- | --------- |
| **GET**    | /api/centroCusto                                     |           |
| **GET**    | /api/centroCusto/<span style="color:blue">:id</span> |           |
| **POST**   | /api/centroCusto                                     |           |
| **PUT**    | /api/centroCusto/<span style="color:blue">:id</span> |           |
| **DELETE** | /api/centroCusto/<span style="color:blue">:id</span> |           |

