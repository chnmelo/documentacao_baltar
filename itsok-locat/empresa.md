# Empresa

# Atributos

| Atributo     | Tipo   | Descrição                                    |
| ------------ | ------ | -------------------------------------------- |
| cnpj         | string | Contém cnpj da empresa                       |
| endFiscal    | string | Endereço da empresa                          |
| razaoSocial  | string | Nome da empresa                              |
| responsavel  | string | Responsavel pela empresa                     |
| telContato   | string | Telefone de contato do responsavel da empres |
| telEmpresa   | string | Telefone de contato da empresa               |
| nomeFantasia | string | Nome da empresa                              |

## Requisições

| tipo       | path                                             | retorno |
| ---------- | ------------------------------------------------ | ------- |
| **GET**    | /api/empresa                                     |         |
| **GET**    | /api/empresa/<span style="color:blue">:id</span> |         |
| **POST**   | /api/empresa                                     |         |
| **PUT**    | /api/empresa/<span style="color:blue">:id</span> |         |
| **DELETE** | /api/empresa/<span style="color:blue">:id</span> |         |

