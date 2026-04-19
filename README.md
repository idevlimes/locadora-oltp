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

- `relatorio-locadora-oltp-izabela-caio.pdf` — documentação completa do projeto  
- `locadora-oltp-script.sql` — criação das tabelas do banco de dados (modelo físico)
- `dicionario_dados_locadora_iza_caio.pdf` - dicionario de dados do modelo do banco de dados
- `mod_conceitual_locadora_oltp.png` -  o modelo conceitual
- `mod_logico_locadora_oltp.png` - o modelo logico
- `relatorio_locadora_oltp-tex` - relatório do projeto em latex

## Observações

O modelo separa as entidades de **Reserva** e **Locação**, permitindo diferenciar intenção de aluguel da sua efetivação. 
Também inclui o controle de movimentação de veículos entre pátios.

## Autoria
Izabela Lima e Caio Meirelles.
Projeto desenvolvido como parte de disciplina de Big Data e Data Warehouse.
