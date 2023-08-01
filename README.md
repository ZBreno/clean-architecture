## Clean Architecture

- **Casos de uso**: Os casos de uso tem como objetivo isolar as regras de negócios de determinada tarefa, através de um encapsulamento os casos de uso definem as entradas e saidas de uma operação. É muito usado como classes ou funções que ditam o fluxo de dados entre camadas.

- **Adaptadores**: Os adaptadores é responsável em trafegar a lógica entre os casos de uso e entidades com o "mundo externo", é também responsável por converter os dados para o formato mais conveniente para os casos de uso e entidades, vice-versa. O mundo externo que os **Controllers** lidam são as comunicações, ja os **Gateways** são responsáveis pela comunicação com banco de dados, models.

- **Entidades**: As entidades são onde estão as regras de negócios, as entidades irão ditar como o sistema faz determinada tarefa. As entidades e os casos de uso são os únicos lugares que devem ter regra de negócios.
