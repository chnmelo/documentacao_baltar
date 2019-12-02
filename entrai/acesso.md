# Acesso

Relação que contem acessos realizados pelo sistema.

## Atributos

|  Atributo   |     Tipo     |                  Descrição                   |
| :---------: | :----------: | :------------------------------------------: |
| data_acesso | Utc_datetime |   Contém a data que foi realizado o acesso   |
|    local    | Forigen key  |        Contém o id do local acessado         |
|   Pessoa    | Forigen Key  | Contém o id do usuario que realizou o acesso |

## Requisições

| tipo     | path             | Retorno |
| -------- | ---------------- | ------- |
| **GET**  | /api/acesso      |         |
| **PUT**  | /api/acesso/<id> |         |
| **POST** | /api/acesso      |         |

