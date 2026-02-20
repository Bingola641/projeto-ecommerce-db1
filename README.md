 Projeto E-commerce DB

Este projeto simula um banco de dados de um e-commerce,
com controle de clientes, produtos e pedidos.

O sistema possui uma procedure chamada sp_venda,
que verifica o estoque antes de realizar uma venda.



RPO (Recovery Point Objective)

Se o banco de dados falhar, podemos perder até 24 horas de dados,
pois o backup é realizado diariamente através do arquivo .sql.



RTO (Recovery Time Objective)

O tempo estimado para restaurar o banco é de aproximadamente
5 minutos, executando o script backup_projeto.sql
em um ambiente MySQL.


 Simulação de Backup

O backup pode ser restaurado executando o arquivo
backup_projeto.sql em qualquer servidor MySQL,
recriando todas as tabelas, dados e procedures.
