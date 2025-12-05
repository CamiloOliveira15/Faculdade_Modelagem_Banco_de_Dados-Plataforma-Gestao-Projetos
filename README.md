# ProjetoFaculdade_Plataforma-Gestao-Projetos

TaskFlow - Plataforma de Gestão de Projetos Ágeis

Este repositório contém os scripts SQL e a documentação técnica para a implementação do banco de dados da plataforma TaskFlow. O projeto foi desenvolvido como parte da atividade prática de Modelagem de Banco de Dados e Implementação SQL.

📋 Descrição do Minimundo

O TaskFlow é uma plataforma web colaborativa destinada a equipes de desenvolvimento de software. O sistema gerencia:

Clientes: Empresas ou indivíduos contratantes.

Projetos: Iniciativas de desenvolvimento de software associadas a clientes.

Funcionários: Colaboradores da empresa, incluindo gerentes responsáveis pelos projetos.

🛠️ Tecnologias Utilizadas

Linguagem: SQL (Structured Query Language)

Banco de Dados Sugerido: MySQL / PostgreSQL (Scripts compatíveis com padrão ANSI SQL com ajustes menores)

Ferramenta de Desenvolvimento: MySQL Workbench / DBeaver / PGAdmin

📂 Estrutura do Repositório

taskflow_scripts.sql: Contém todos os comandos DDL (Criação de tabelas) e DML (Manipulação de dados: INSERT, SELECT, UPDATE, DELETE).

🚀 Como Executar

Abra sua ferramenta de banco de dados (ex: MySQL Workbench).

Crie um novo banco de dados (Schema):

CREATE DATABASE taskflow_db;
USE taskflow_db;


Abra o arquivo taskflow_scripts.sql contido neste repositório.

Execute todo o script para criar a estrutura e popular os dados iniciais.

📊 Estrutura Lógica (Resumo)

CLIENTS: Tabela de clientes.

EMPLOYEES: Tabela de funcionários.

PROJECTS: Tabela de projetos (possui chaves estrangeiras para Clients e Employees).

Desenvolvido para a Experiência Prática IV - Implementação e Manipulação de Dados.
