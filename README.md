# Projeto de Login com Conexão ao Banco de Dados

Este repositório contém um projeto Java que implementa uma funcionalidade de **autenticação de usuários**. O objetivo do projeto é gerenciar a **conexão com o banco de dados MySQL** e validar as **credenciais de login** fornecidas pelo usuário.

## Objetivo

O principal objetivo desse projeto é:

- Estabelecer uma conexão segura com o banco de dados MySQL.
- Verificar as credenciais de login do usuário para garantir a autenticidade e segurança.
- Realizar a documentação e testes do código, além de melhorias na segurança e robustez.

## Estrutura do Projeto

### Classe `User`
A classe **`User`** contém a lógica de autenticação de usuários e a conexão com o banco de dados. Os principais métodos são:

- **`conectarBD()`**: Estabelece a conexão com o banco de dados MySQL.
- **`verificarUsuario(String login, String senha)`**: Verifica as credenciais fornecidas pelo usuário.

### Funcionalidades

- **Autenticação**: O método `verificarUsuario` valida se as credenciais (login e senha) fornecidas pelo usuário são válidas ao consultar o banco de dados.
- **Conexão ao Banco de Dados**: A classe faz uso da classe `DriverManager` para conectar-se ao banco de dados MySQL.
