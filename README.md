# Modelagem OLTP - Locadora de Veículos
Projeto de modelagem de banco de dados transacional (OLTP) desenvolvido para uma empresa fictícia de locação de veículos.

## Objetivo

Modelar um sistema capaz de gerenciar:
- Clientes
- Veículos
- Pátios
- Reservas
- Locações
- Pagamentos
- Movimentação de veículos entre pátios

## Estrutura do Projeto

O projeto inclui:
- Modelo Conceitual (MER)
- Modelo Lógico
- Modelo Físico (SQL)

## Tecnologias

- SQL (ANSI SQL / SQL99)
- Modelagem Entidade-Relacionamento

## Arquivos

- `locadora-oltp-relatorio-izabela-caio.pdf` — documentação completa do projeto  
- `locadora-oltp-script.sql` — criação das tabelas do banco de dados  

## Observações

O modelo separa as entidades de **Reserva** e **Locação**, permitindo diferenciar intenção de aluguel da sua efetivação. 
Também inclui o controle de movimentação de veículos entre pátios.

## Autoria
Izabela Lima e Caio Meirelles.
Projeto desenvolvido como parte de disciplina de Big Data e Data Warehouse.
