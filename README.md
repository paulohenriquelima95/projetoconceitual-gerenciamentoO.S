# Diagrama Entidade Relacionamento - Projeto Gerenciamento de O.S - MySQL

## Objetivo
Este projeto consiste em criar o esquema conceitual para o contexto de gerenciamento de ordem de serviço de uma oficina mecânica com base na narrativa fornecida utilizando MySQL. O diagrama visa representar a estrutura do banco de dados do sistema, incluindo entidades, atributos e relacionamentos. O projeto faz parte do desafio do bootcamp Database Experience da DIO.

## Narrativa
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
- O diagrama ER é composto pelas seguintes entidades principais:

## Tecnologias Utilizadas
- MySQL
- Ferramenta de modelagem de banco de dados (por exemplo, MySQL Workbench, DB Designer.)

## Como Visualizar o Diagrama
1. Clone o repositório: `git clone https://github.com/paulohenriquelima95/projetoconceitual-gerenciamentoO.S.git`
2. Abra o arquivo do diagrama no seu software de modelagem de banco de dados preferido (por exemplo, MySQL Workbench).
3. Explore as entidades, atributos e relacionamentos no diagrama.

## Estrutura do Projeto
/projetoconceitual-gerenciamentoO.S
|-- projetoconceitual-gerenciamentoO.S.png
|-- projetoconceitual-gerenciamentoO.S.pdf
|-- README.md

csharp
Copy code

## Contribuição
Contribuições não são esperadas para este projeto, pois se trata apenas de um diagrama representativo da estrutura do banco de dados.

## Contato
### Paulo Henrique Lima
E-mail:  [paulohenrique-95@hotmail.com](paulohenrique-95@hotmail.com)
Linkedin:  [linkedin.com/in/paulohenriquelima95](www.linkedin.com/in/paulohenriquelima95)
