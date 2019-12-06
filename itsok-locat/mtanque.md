# Modelo Tanque

## Atributos

| Atributo       | Tipo   | Descrição                        |
| -------------- | ------ | -------------------------------- |
| altura         | float  | Altura do tanque                 |
| comprimento    | float  | Comprimento do tanque            |
| dataFabricacao | string | Data que o tanque foi fabricado  |
| disposição     | string |                                  |
| fabricante     | string | Fabricante do tanque             |
| formato        | string | Qual o formato que o tanque tem. |
| largura        | float  | Lagura do tanque                 |
| nomeFantasia   | string | Nome de indentificação do tanque |

## Requisições 

| tipo       | path                                                  | retorno |
| ---------- | ----------------------------------------------------- | ------- |
| **GET**    | /api/modeloTanque                                     |         |
| **GET**    | /api/modeloTanque/<span style="color:blue">:id</span> |         |
| **POST**   | /api/modeloTanque                                     |         |
| **PUT**    | /api/modeloTanque/<span style="color:blue">:id</span> |         |
| **DELETE** | /api/modeloTanque/<span style="color:blue">:id</span> |         |

