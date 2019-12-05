# Abastecimento

## Atributos

| Atributos            | Tipo         | Descrição                                                    |
| -------------------- | ------------ | ------------------------------------------------------------ |
| centroCusto_id       | inteiro      | Contém inteiro referenta a id do centro de custo do abastecimento |
| destino_id           | inteiro      | Contém inteiro referente a id do equipamento abastecido      |
| fornecedor_id        | inteiro      | Contém inteiro referente a id do posto que realizou o abastecimento |
| numFinal             | float        | Contém valor do odometro/horimetro do equipamento            |
| quantidade           | float        | Contém quantidade abastecida no equipamento                  |
| completo             | boolean      | Flag para se completou o tanque do equipamento               |
| respFornecimento     | inteiro      | Contém inteiro referente a id do operador frentista          |
| respDestino          | inteiro      | Contém inteiro referente a id do operador motorista          |
| justificativa        | string       | Contém justificativa de mudanças ou correções no abastecimento |
| respJustificativa_id | inteiro      | Contém inteiro referente a id do operador que realizar modificação no abastecimento |
| tipoJustificativa    | string       | Contém o tipo que foi a justificativa.                       |
| consistente          | boolean      | Flag para se o abastecimento é consistente ou contém algo errado |
| data_abastecimento   | Utc_datetime | Contém data em que o abastecimento foi realizado             |
| consumo              | float        | Contém calculo do consumo que o equipamento teve de um abastecimento anterior até este. |
| numInicial           | float        | Contém odômetro/horimetro do abastecimento anterior do equipamento. |
| produto              | string       | †ipo de combustivel utilizado no abastecimento               |



## Requisições

| tipo       | path                                                         | retorno |
| ---------- | ------------------------------------------------------------ | ------- |
| **GET**    | /api/abastecimento                                           |         |
| **GET**    | /api/abastecimento/notify                                    |         |
| **GET**    | /api/abastecimento/<span style="color:blue">:id</span>       |         |
| **PUT**    | /api/abastecimento/<span style="color:blue">:id</span>       |         |
| **PUT**    | /api/abastecimento/io/<span style="color:blue">:id</span>    |         |
| **POST**   | /api/abastecimento                                           |         |
| **POST**   | /api/abastecimento/justificar                                |         |
| **DELETE** | /api/abastecimento/<span style="color:blue">:id</span>       |         |
| **GET**    | /api/reviews/abastecimento/empresa/<span style="color:blue">:empresa_id</span>/<span style="color:blue">:data_inicial</span>/<span style="color:blue">:data_final</span> |         |
| **GET**    | /api/reviews/abastecimento/empresa/<span style="color:blue">:empresa_id</span>/<span style="color:blue">:data_dia</span> |         |
| **GET**    | /api/reviews/abastecimento/postoAbastecimento/<span style="color:blue">:posto_id</span>/<span style="color:blue">:data_inicial</span>/<span style="color:blue">:data_final</span> |         |
| **GET**    | /api/reviews/abastecimento/equipamento/<span style="color:blue">:equipamento_id</span>/<span style="color:blue">:data_inicial</span>/<span style="color:blue">:data_final</span> |         |
| **GET**    | /api/reviews/abastecimento/equipamento/<span style="color:blue">:equipamento_id</span>/<span style="color:blue">:data_inicial</span>/<span style="color:blue">:data_final</span> |         |

