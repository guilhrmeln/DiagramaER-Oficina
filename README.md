# Diagrama entidade relacionamento de um banco de dados de oficina automotiva

Este projeto é um dos desafios do curso "Formação SQL Database Specialist", do DIO, onde foi prescrito a modelagem de um diagrama entidade relacionamento para um banco de dados de uma oficina automotiva.

Os requisitos eram: 
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega;
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra;
- O valor de cada peça também irá compor a OS;
- O cliente autoriza a execução dos serviços;
- A mesma equipe avalia e executa os serviços;
- Os mecânicos possuem código, nome, endereço e especialidade;
- Cada OS possui n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

Sua elaboração foi feita com o auxílio da ferramenta de design do MySQL Workbench.