# Projeto de Banco de Dados com PostgreSQL


Este projeto utiliza PostgreSQL para gerenciar informações de uma loja fictícia, incluindo clientes, funcionários, produtos e vendas.

## Estrutura do Banco de Dados

### Tabelas Principais

- **clientes**: id_cliente, nome, email, telefone

- **funcionarios**: id_funcionario, nome, sexo, ativo, criado_em, modificado_em

- **produtos**: id_produto, nome, preco_de_venda, estoque

- **vendas**: id_venda, id_funcionario, id_cliente, data_venda

- **produto_venda**: id_produto_venda, id_venda, id_produto, quantidade, preco_unitario

### Funcionalidades

- **Constraints**: Garantem integridade de dados como sexo ('M' ou 'F') e status ativo ('true' ou 'false').

- **Procedures**: Automatizam inserções complexas, como adicionar funcionários e vendas.

- **Views**: Facilitam consultas, como total vendido por funcionário no ano de 2024.

### Scripts SQL

Encontre todos os scripts SQL no diretório sql/ para criar o esquema, tabelas, procedures e views.

### Execução

1. Instale PostgreSQL e crie um banco de dados.

2. Execute os scripts SQL para configurar o esquema e funcionalidades.

3. Use pgAdmin ou consultas SQL para interagir com o banco de dados.

