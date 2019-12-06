# Equipamento

## Atributos

| Atributo        | Tipo        | Descrição                                        |
| --------------- | ----------- | ------------------------------------------------ |
| placa           | string      | Placa do equipamento                             |
| frota           | string      | Frota do equipamento                             |
| tipo            | string      | Tipo do equipamento: MAQUINA, VEICULO            |
| marca           | string      | Marca do equipamento                             |
| modelo          | string      | modelo do equipamento                            |
| ano             | string      | Ano do equipamento                               |
| numSerie        | string      | numero de serie do equipamento                   |
| nivelServico    | string      | nivel de serviço que o equipamento trabalha      |
| rangerDeConsumo | string      | Consumo do equipamento                           |
| volTanque       | float       | Volume do tanque do equipamento                  |
| empresa_id      | Forigen Key | Id da empresa dona do equipamento                |
| cc_veiculo      | string      | centro de custo do equipamento                   |
| limSuper        | float       |                                                  |
| limInfer        | float       |                                                  |
| particular      | Boolean     | Flag para indicar se é um equipamento particular |

## Requisições 

| tipo       | path                                                         | retorno |
| ---------- | ------------------------------------------------------------ | ------- |
| **GET**    | /api/equipamento                                             |         |
| **GET**    | /api/equipamentoLiberado                                     |         |
| **GET**    | /api/equipamento/tags                                        |         |
| **GET**    | /api/controleEquipamento                                     |         |
| **GET**    | /api/equipamento/<span style="color:blue">:id</span>         |         |
| **GET**    | /api/equipamento/placa/<span style="color:blue">:placa</span> |         |
| **POST**   | /api/equipamento                                             |         |
| **PUT**    | /api/equipamento/<span style="color:blue">:id</span>         |         |
| **DELETE** | /api/equipamento/<span style="color:blue">:id</span>         |         |

