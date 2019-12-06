# Fornecedor

## Atributos

| Atributo    | Tipo        | Descrição                                             |
| ----------- | ----------- | ----------------------------------------------------- |
| cnpj        | string      | CNPJ do fornecedor de combustivel                     |
| financeiro  | string      |                                                       |
| razaoSocial | string      | Nome que denomina a empresa                           |
| telContato  | string      | Telefone de contato do fornecedor                     |
| vendedor    | string      | nome do fornecedor                                    |
| empresa_id  | Forigen Key | Chave de empresa a qual este fornecedor esta atrelado |

## Requisições 

| tipo       | path                                                | retorno |
| ---------- | --------------------------------------------------- | ------- |
| **GET**    | /api/fornecedor                                     |         |
| **GET**    | /api/fornecedor/<span style="color:blue">:id</span> |         |
| **POST**   | /api/fornecedor                                     |         |
| **PUT**    | /api/fornecedor/<span style="color:blue">:id</span> |         |
| **DELETE** | /api/fornecedor/<span style="color:blue">:id</span> |         |

