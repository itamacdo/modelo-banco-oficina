# Projeto Conceitual de Banco de Dados – Oficina Mecânica

## Descrição do Projeto
Projeto de modelagem conceitual de banco de dados para um sistema de controle e
gerenciamento de ordens de serviço em uma oficina mecânica.

O modelo foi desenvolvido com base em uma narrativa de negócio, contemplando
clientes, veículos, ordens de serviço, equipes de mecânicos, serviços e peças.

## Objetivo
Criar um esquema conceitual completo a partir da narrativa fornecida.

## Considerações
- Um cliente pode possuir vários veículos
- Cada veículo pode gerar várias ordens de serviço
- Cada OS é atribuída a uma equipe de mecânicos
- A mesma equipe avalia e executa os serviços
- A OS possui status, datas e valor total

## Estrutura
- modelo/: documentação conceitual e lógica
- sql/: scripts SQL
